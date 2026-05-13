# Schema Regole SRD 5.2.1 (Markdown -> JSON)

Scopo: strutturare le regole generali del SRD 5.2.1 in voci consultabili dall'app.

## Regole globali

- Ogni voce regola inizia con `## Nome regola`.
- Ogni voce deve avere `**id:** valore`.
- Le voci sono separate da `---`.
- I campi base usano sempre `**campo:** valore`.
- Il testo libero dopo i campi base diventa `descrizione`.
- Le sezioni `###` diventano elementi dell'array `sezioni`.
- Le tabelle Markdown dentro una sezione `###` diventano `sezioni[].righe`.
- I blocchi `**Nome**` seguiti da testo diventano `sezioni[].blocchi`.

---

## Struttura Markdown

```md
## Nome regola

**id:** string
**capitolo:** string
**categoria:** string
**pagine_sorgente:** string

Descrizione libera della regola.

### Nome sezione

| Chiave | Valore |
| --- | --- |
| valore | valore |

**Nome blocco**
Descrizione blocco.
```

---

## JSON standard atteso

```json
{
  "id": "string",
  "nome": "string",
  "capitolo": "string",
  "categoria": "string",
  "pagine_sorgente": "string|null",
  "descrizione": "string",
  "sezioni": [
    {
      "titolo": "string",
      "descrizione": "string|null",
      "righe": [
        {
          "chiave": "string|null",
          "valore": "string"
        }
      ],
      "blocchi": [
        {
          "nome": "string|null",
          "descrizione": "string"
        }
      ]
    }
  ]
}
```
