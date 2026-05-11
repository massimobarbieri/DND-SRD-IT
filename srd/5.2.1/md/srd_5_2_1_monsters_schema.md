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
- I campi `tiri` e `ricarica` sono opzionali e devono essere emessi solo quando il dato è ad alta confidenza.
- Se `tiri` o `ricarica` sono assenti o incompleti, le applicazioni devono poter tornare al parsing della descrizione testuale.

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
**vulnerabilita:** string       # opzionale
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

**tiri:**                       # opzionale, solo per azioni/tratti/reazioni con dato certo
- tipo: attacco
  modalita: mischia|distanza|incantesimo|null
  bonus: number
  portata: string|null
  gittata: string|null
  danni:
    - formula: string
      media: number|null
      tipo: string|null
      contesto: string|null
  confidenza: alta|media|bassa
- tipo: salvezza
  caratteristica: string
  cd: number
  bersaglio: string|null
  fallimento:
    danni:
      - formula: string
        media: number|null
        tipo: string|null
        contesto: string|null
    effetti: []
  successo:
    danni: meta|null
    effetti: []
  confidenza: alta|media|bassa

**ricarica:**                   # opzionale
- formula: 1d6
- successo: [5, 6]
- testo: Ricarica 5-6

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
    {
      "nome": "string",
      "descrizione": "string",
      "tiri": [],
      "ricarica": null
    }
  ],
  "azioni": [
    {
      "nome": "string",
      "descrizione": "string",
      "tiri": [
        {
          "tipo": "attacco",
          "modalita": "mischia|distanza|incantesimo|null",
          "bonus": 0,
          "portata": "string|null",
          "gittata": "string|null",
          "danni": [
            {
              "formula": "string",
              "media": 0,
              "tipo": "string|null",
              "contesto": "string|null"
            }
          ],
          "confidenza": "alta"
        },
        {
          "tipo": "salvezza",
          "caratteristica": "string",
          "cd": 0,
          "bersaglio": "string|null",
          "fallimento": {
            "danni": [
              {
                "formula": "string",
                "media": 0,
                "tipo": "string|null",
                "contesto": "string|null"
              }
            ],
            "effetti": []
          },
          "successo": {
            "danni": "meta|null",
            "effetti": []
          },
          "confidenza": "alta"
        }
      ],
      "ricarica": {
        "formula": "1d6",
        "successo": [5, 6],
        "testo": "Ricarica 5-6"
      }
    }
  ],
  "azioni_bonus": [
    { "nome": "string", "descrizione": "string", "tiri": [], "ricarica": null }
  ],
  "reazioni": [
    { "nome": "string", "descrizione": "string", "tiri": [], "ricarica": null }
  ],
  "azioni_leggendarie": {
    "utilizzi": "string|null",
    "azioni": [
      { "nome": "string", "descrizione": "string", "tiri": [], "ricarica": null }
    ]
  }
}
```

---

## Regole per tiri strutturati

- `tiri` può comparire su tratti, azioni, azioni bonus, reazioni e azioni leggendarie.
- Negli elementi non arricchiti, `tiri` e `ricarica` possono essere omessi.
- Ogni elemento di `tiri` deve avere `tipo: attacco` oppure `tipo: salvezza`.
- Per gli attacchi, `bonus` è numerico e `danni[].formula` contiene solo formule di dado tirabili, per esempio `2d6 + 5`.
- Per i tiri salvezza, `cd` è numerico, `caratteristica` è il nome della caratteristica e i danni del fallimento stanno in `fallimento.danni`.
- `successo.danni` può essere `meta` quando il testo dice che il bersaglio subisce danni dimezzati.
- `ricarica` descrive solo meccaniche esplicite di ricarica su `1d6`; `successo` contiene i risultati validi del dado.
- `confidenza: alta` va usata quando bonus, CD, formula e contesto sono estratti senza ambiguità dal testo SRD.
- In caso di ambiguità, non generare `tiri`: la descrizione testuale resta la fonte primaria.
