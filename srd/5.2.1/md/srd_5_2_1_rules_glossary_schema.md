# Schema Glossario Regole SRD 5.2.1 (Markdown -> JSON)

Scopo: strutturare le voci del glossario delle regole SRD 5.2.1 in termini consultabili, filtrabili e riutilizzabili.

## Regole globali

- Ogni voce inizia con `## Termine`.
- Ogni voce deve avere `**id:** valore`.
- Le voci sono separate da `---`.
- `descrittore` contiene il gruppo tra parentesi quadre quando presente nel PDF, per esempio `condizione`, `azione`, `area di effetto`, `atteggiamento`, `pericolo`.
- `lettera` contiene l'iniziale usata per la navigazione alfabetica.
- Il testo libero dopo i campi base diventa `descrizione`.
- Le sezioni `###` diventano `sezioni[]`.
- Le tabelle Markdown dentro una sezione `###` diventano `sezioni[].righe`.
- I blocchi `**Nome**` seguiti da testo diventano `sezioni[].blocchi`.
- I rimandi espliciti diventano `vedi_anche`.

---

## JSON standard atteso

```json
{
  "id": "string",
  "nome": "string",
  "lettera": "string",
  "descrittore": "string|null",
  "pagine_sorgente": "string|null",
  "descrizione": "string",
  "sezioni": [
    {
      "titolo": "string",
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
  ],
  "vedi_anche": ["string"]
}
```
