# Schema Oggetti Magici SRD 5.2.1 (Markdown → JSON)

Scopo: garantire JSON omogeneo dagli oggetti magici anche dopo modifiche future al Markdown.

## Regole globali

- Ogni oggetto magico inizia con `## Nome Oggetto`.
- Ogni oggetto deve avere `**id:** valore`.
- Gli oggetti sono separati da `---`.
- I campi base usano sempre `**campo:** valore`.
- Il testo libero dopo i campi base diventa `descrizione`.
- Le sezioni `###` diventano elementi dell'array `sezioni`.
- Le tabelle Markdown dentro una sezione `###` diventano `sezioni[].righe`.
- I blocchi in grassetto dentro la descrizione diventano `proprieta`.
- Campi mancanti ma previsti dallo schema devono essere emessi come `null` o array vuoto.
- Il parser deve tollerare righe accidentalmente unite, per esempio:
  `**id:** valore**tipo:** valore`
  e dividerle in due campi.

---

## Struttura Markdown

```md
## Nome Oggetto
**id:** string
**tipo:** string
**rarita:** string

Descrizione libera dell'oggetto.

**Nome proprietà**
Descrizione proprietà.

### Nome tabella o sezione

| Colonna A | Colonna B |
| --- | --- |
| valore | valore |

**Voce**
Descrizione voce.
```

---

## Note di normalizzazione

- Se `tipo` contiene `(richiede sintonia)`, il JSON deve impostare `richiede_sintonia: true`.
- Se `rarita` contiene `(richiede sintonia)`, il JSON deve impostare `richiede_sintonia: true` e ripulire `rarita`.
- `tipo_base` può essere derivato dalla prima parte di `tipo`, per esempio `Anello`, `Arma`, `Armatura`, `Oggetto meraviglioso`.

---

## JSON standard atteso

```json
{
  "id": "string",
  "nome": "string",
  "tipo": "string",
  "tipo_base": "string|null",
  "rarita": "string",
  "richiede_sintonia": false,
  "descrizione": "string",
  "proprieta": [
    {
      "nome": "string",
      "descrizione": "string"
    }
  ],
  "sezioni": [
    {
      "titolo": "string",
      "righe": [
        {
          "chiave": "string|null",
          "valore": "string"
        }
      ]
    }
  ],
  "riferimenti": {
    "incantesimi": ["id_incantesimo"],
    "mostri": ["id_mostro"]
  }
}
```

## Riferimenti

Quando nella descrizione compaiono nomi di incantesimi o creature, il parser può popolare `riferimenti.incantesimi` e `riferimenti.mostri` solo se trova una corrispondenza certa negli altri JSON.
