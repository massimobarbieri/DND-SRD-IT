# Schema Mostri SRD (MD → JSON)

## Struttura globale

# Titolo documento (ignorato)

## Nome Mostro
...contenuto...

---

## Nome Mostro
...contenuto...


## Blocco base

## Nome Mostro
**id:** string

**gruppo:** string (opzionale)

**tipo:** string
**dimensione:** string
**sottotipo:** string (opzionale)
**sottodimensione:** string (opzionale)
**allineamento:** string

**classe_armatura:** string|number
**iniziativa:** string
**punti_ferita:** string
**velocita:** string


## Caratteristiche

**caratteristiche:**
- forza: number (mod)
- destrezza: number (mod)
- costituzione: number (mod)
- intelligenza: number (mod)
- saggezza: number (mod)
- carisma: number (mod)


## Tiri salvezza

**tiri_salvezza_base:**
- forza: mod
- destrezza: mod
- costituzione: mod
- intelligenza: mod
- saggezza: mod
- carisma: mod


## Campi opzionali

**abilita:** string
**attrezzatura:** string
**resistenze:** string
**immunita_danni:** string
**immunita_condizione:** string
**sensi:** string
**lingue:** string
**grado_sfida:** string|number|null
**punti_esperienza:** string
**bonus_competenza:** string
**grado_sfida_raw:** string


## Sezioni

### Tratti
**Nome tratto**
Descrizione

### Azioni
**Nome azione**
Descrizione

### Azioni bonus
**Nome azione bonus**
Descrizione

### Reazioni
**Nome reazione**
Descrizione

### Azioni leggendarie
**Utilizzi di azioni leggendarie:** string

**Nome azione leggendaria**
Descrizione


## Regole

- Usare sempre formato **campo:** valore
- Non cambiare nomi dei campi
- Usare sempre gli stessi titoli di sezione
- Separare i mostri con ---
