---
id: golem_di_ferro
nome: Golem di ferro
tipo: Costrutto
dimensione: Grande
allineamento: senza allineamento
classe_armatura: 20
iniziativa:
  valore: 19
  bonus: 9
punti_ferita:
  media: 252
  formula: 24d10 + 120
velocita:
  camminata: 9 m
caratteristiche:
  forza:
    punteggio: 24
    modificatore: 7
    tiro_salvezza: 7
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
immunita_danni:
- fuoco
- psichico
- veleno
immunita_condizione:
- affascinato
- avvelenato
- indebolimento
- paralizzato
- pietrificato
- spaventato
sensi:
  percezione_passiva: 10
  scurovisione: 36 m
lingue:
- capisce il Comune più altre due lingue ma non le parla
grado_sfida:
  valore: 16
  punti_esperienza: 15000
  raw: 16 (PE 15.000; BC +5)
bonus_competenza: 5
---
## Tratti
### Assorbimento del fuoco
Ogni volta che il golem subisce danni da fuoco, recupera un numero di punti ferita pari ai danni da fuoco inflitti.

### Forma immutabile
Il golem non può mutare forma.

### Resistenza alla magia
Il golem dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

## Azioni
### Multiattacco
Il golem effettua due attacchi, usando Braccio affilato o Dardo di fuoco in qualsiasi combinazione.

### Braccio affilato
*Tiro per colpire in mischia:* +12, portata 3 m. *Colpito:* 20 (3d8 + 7) danni taglienti più 10 (3d6) danni da fuoco.

### Dardo di fuoco
*Tiro per colpire a distanza:* +10, gittata 36 m. *Colpito:* 36 (8d8) danni da fuoco.

### Soffio di veleno (ricarica 6)
*Tiro salvezza su Costituzione:* CD 18, tutte le creature in un cono di 18 metri. *Fallimento:* 55 (10d10) danni da veleno. *Successo:* danni dimezzati.