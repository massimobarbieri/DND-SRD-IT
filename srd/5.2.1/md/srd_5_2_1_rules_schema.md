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
- Quando una tabella ha intestazioni proprie nel PDF, salvarle in `sezioni[].colonne` e usare gli stessi nomi come chiavi di ogni riga. Non ridurre queste tabelle a coppie `Voce/Riepilogo`.
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
      "colonne": ["string"],
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

Per le tabelle multi-colonna il formato atteso e:

```json
{
  "titolo": "Progressione di classe",
  "colonne": ["Livello", "Bonus di competenza", "Privilegi di classe"],
  "righe": [
    {
      "Livello": "1",
      "Bonus di competenza": "+2",
      "Privilegi di classe": "Privilegio"
    }
  ],
  "blocchi": []
}
```
