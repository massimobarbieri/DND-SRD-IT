---
id: cacciatore_invisibile
nome: Cacciatore invisibile
tipo: Elementale
dimensione: Grande
allineamento: neutrale

classe_armatura: 14

iniziativa:** +7
  valore: 22
  bonus: 7

punti_ferita:
  medi: 97
  formula: 13d10 + 26

velocita:
  camminata: 15 m
  volo: 15 m (fluttuare)

caratteristiche:
  forza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  destrezza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  carisma:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0

abilita:
  furtivita: 10
  percezione: 8

resistenze:
  - contundente
  - perforante
  - tagliente
immunita_danni:
  - veleno
immunita_condizioni:
  - afferrato
  - avvelenato
  - indebolimento
  - paralizzato
  - pietrificato
  - privo di sensi
  - prono
  - trattenuto 

sensi:
  percezione_passiva: 18
  scurovisione: 18 m  

lingue:
  - Comune
  - Primordiale (Auran)

grado_sfida:
  valore: 6
  punti_esperienza: 2.300
  raw: 6 (PE 2.300; BC +3)

bonus_competenza: 3
---
## Tratti
### Forma d'aria
Il cacciatore invisibile può entrare nello spazio di un nemico e fermarvisi. Può muoversi attraverso uno spazio stretto fino a 2,5 centimetri senza consumare movimento extra per farlo.

### Invisibilità
Il cacciatore è invisibile.

## Azioni
### Multiattacco
Il cacciatore invisibile effettua tre attacchi. Può sostituire un attacco con un utilizzo di Vortice.

### Colpo di vento
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 11 (2d6 + 4) danni da forza.

### Vortice
*Tiro salvezza su Costituzione:* CD 14, una creatura di taglia Grande o inferiore nello spazio del cacciatore. *Fallimento:* 7 (1d8 + 3) danni da tuono, e il bersaglio è afferrato (CD 13 per sfuggire). Finché la presa perdura, il bersaglio non può lanciare incantesimi con una componente verbale, e subisce 7 (2d6) danni da tuono all'inizio di ogni turno del cacciatore.