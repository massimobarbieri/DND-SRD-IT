# Schema Incantesimi SRD 5.2.1 (Markdown → JSON)

Scopo: garantire JSON omogeneo dagli incantesimi anche dopo modifiche future al Markdown.

## Regole globali

- Ogni incantesimo inizia con `## Nome Incantesimo`.
- Ogni incantesimo deve avere `**id:** valore`.
- Gli incantesimi sono separati da `---`.
- I campi base usano sempre `**campo:** valore`.
- Il testo libero dopo i campi base diventa `descrizione`.
- Le sezioni `###` diventano elementi dell'array `sezioni`.
- `### Scaling` deve essere normalizzato nel campo JSON `scaling`.
- Se esiste `**creatura_evocata:** id_creatura`, il valore è un riferimento all'`id` di una creatura nel JSON dei mostri.
- Se esiste un blocco con `**tipo_blocco:** creatura_evocata`, quel blocco va convertito come creatura locale e collegato all'incantesimo.
- Campi mancanti ma previsti dallo schema devono essere emessi come `null`, stringa vuota o array vuoto secondo il tipo.

---

## Struttura Markdown

```md
## Nome Incantesimo

**id:** string
**pagine_sorgente:** string
**tipo:** incantesimo|trucchetto
**livello:** number
**scuola:** string
**classi:** classe1, classe2

**tempo_lancio:** string
**gittata:** string
**componenti:** string
**durata:** string
**creatura_evocata:** id_mostro        # opzionale

Descrizione libera dell'incantesimo.

### Scaling

**Nome scaling**
Descrizione scaling.

### Nome sezione libera

**Nome sottosezione**
Descrizione.
```

---

## Blocco creatura evocata locale

```md
### Nome Creatura

**tipo_blocco:** creatura_evocata
**nome:** string
**tipo:** string
**dimensione:** string                 # opzionale
**allineamento:** string
**classe_armatura:** string
**punti_ferita:** string
**velocita:** string
```

---

## JSON standard atteso

```json
{
  "id": "string",
  "nome": "string",
  "pagine_sorgente": "string|null",
  "tipo": "incantesimo|trucchetto",
  "livello": 0,
  "scuola": "string",
  "classi": ["string"],
  "tempo_lancio": "string",
  "gittata": "string",
  "componenti": "string",
  "durata": "string",
  "descrizione": "string",
  "creatura_evocata": {
    "id": "string|null",
    "fonte": "mostri",
    "risoluzione": "lookup_by_id"
  },
  "creature_evocate_inline": [
    {
      "id": "string|null",
      "nome": "string",
      "tipo_blocco": "creatura_evocata",
      "statblock": {}
    }
  ],
  "scaling": [
    {
      "nome": "string",
      "descrizione": "string"
    }
  ],
  "sezioni": [
    {
      "titolo": "string",
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
