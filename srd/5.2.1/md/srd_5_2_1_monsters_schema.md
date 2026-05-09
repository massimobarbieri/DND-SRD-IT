# Schema Mostri SRD 5.2.1 (Markdown → JSON)

Scopo: garantire che ogni conversione futura da Markdown a JSON produca sempre la stessa struttura dati.

## Regole globali

- Ogni mostro inizia con `## Nome Mostro`.
- Ogni mostro deve avere `**id:** valore`.
- I mostri sono separati da `---`.
- I campi base usano sempre `**campo:** valore`.
- Le liste strutturate usano sempre `- chiave: valore`.
- Le sezioni ammesse sono solo quelle elencate in questo schema.
- Campi mancanti ma previsti dallo schema devono essere emessi nel JSON come `null` o array vuoto.
- Il parser deve normalizzare:
  - `imminita_condizione` → `immunita_condizione`
  - `immunita_condizioni` → `immunita_condizione`
  - `immunità_danni` → `immunita_danni`

---

## Struttura Markdown

```md
## Nome Mostro
**id:** string
**gruppo:** string                    # opzionale
**tipo:** string
**dimensione:** string
**sottotipo:** string                 # opzionale
**sottodimensione:** string           # opzionale
**allineamento:** string

**classe_armatura:** string
**iniziativa:** string
**punti_ferita:** string
**velocita:** string

**caratteristiche:**
- forza: number (mod)
- destrezza: number (mod)
- costituzione: number (mod)
- intelligenza: number (mod)
- saggezza: number (mod)
- carisma: number (mod)

**tiri_salvezza_base:**
- forza: mod
- destrezza: mod
- costituzione: mod
- intelligenza: mod
- saggezza: mod
- carisma: mod

**abilita:** string                   # opzionale
**attrezzatura:** string              # opzionale
**resistenze:** string                # opzionale
**immunita_danni:** string            # opzionale
**immunita_condizione:** string       # opzionale
**sensi:** string
**lingue:** string
**grado_sfida:** string|number|null
**punti_esperienza:** string
**bonus_competenza:** string
**grado_sfida_raw:** string

### Tratti
**Nome tratto**
Descrizione.

### Azioni
**Nome azione**
Descrizione.

### Azioni bonus
**Nome azione bonus**
Descrizione.

### Reazioni
**Nome reazione**
Descrizione.

### Azioni leggendarie
**Utilizzi di azioni leggendarie:** string
**Nome azione leggendaria**
Descrizione.
```

---

## JSON standard atteso

```json
{
  "id": "string",
  "nome": "string",
  "gruppo": null,
  "tipo": "string",
  "dimensione": "string",
  "sottotipo": null,
  "sottodimensione": null,
  "allineamento": "string",
  "statistiche": {
    "classe_armatura": "string",
    "iniziativa": "string",
    "punti_ferita": "string",
    "velocita": "string"
  },
  "caratteristiche": {
    "forza": { "valore": 0, "modificatore": "+0" },
    "destrezza": { "valore": 0, "modificatore": "+0" },
    "costituzione": { "valore": 0, "modificatore": "+0" },
    "intelligenza": { "valore": 0, "modificatore": "+0" },
    "saggezza": { "valore": 0, "modificatore": "+0" },
    "carisma": { "valore": 0, "modificatore": "+0" }
  },
  "tiri_salvezza_base": {
    "forza": "+0",
    "destrezza": "+0",
    "costituzione": "+0",
    "intelligenza": "+0",
    "saggezza": "+0",
    "carisma": "+0"
  },
  "abilita": null,
  "attrezzatura": null,
  "resistenze": null,
  "immunita_danni": null,
  "immunita_condizione": null,
  "sensi": "string",
  "lingue": "string",
  "grado_sfida": "string|number|null",
  "punti_esperienza": "string",
  "bonus_competenza": "string",
  "grado_sfida_raw": "string",
  "tratti": [
    { "nome": "string", "descrizione": "string" }
  ],
  "azioni": [
    { "nome": "string", "descrizione": "string" }
  ],
  "azioni_bonus": [
    { "nome": "string", "descrizione": "string" }
  ],
  "reazioni": [
    { "nome": "string", "descrizione": "string" }
  ],
  "azioni_leggendarie": {
    "utilizzi": "string|null",
    "azioni": [
      { "nome": "string", "descrizione": "string" }
    ]
  }
}
```
