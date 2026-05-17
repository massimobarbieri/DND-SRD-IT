---
id: diavolo_cornuto
nome: Diavolo cornuto
tipo: Immondo
sottotipo: diavolo
dimensione: Grande
allineamento: legale malvagio

classe_armatura: 18
iniziativa:
  valore: 17
  bonus: 7
punti_ferita:
  media: 199
  formula: 19d10 + 95
velocita:
  camminata: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 10
  destrezza:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 7
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
  saggezza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 7
  carisma:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 8

resistenze:
  - freddo

immunita_danni:
  - fuoco
  - veleno

immunita_condizioni:
  - avvelenato

sensi:
  percezione_passiva: 13
  scurovisione: 45 m
  dettagli_scurovisione: non ostacolata dall'oscurità magica

lingue:
  - Infernale
  - telepatia 36 m

grado_sfida:
  valore: 11
  punti_esperienza: 7.200
  raw: 11 (PE 7.200; BC +4)

bonus_competenza: 4
---
## Tratti
### Resistenza alla magia
Il diavolo dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

### Ristoro diabolico
Se il diavolo muore al di fuori dei Nove Inferi, il suo corpo si dissolve in fumo sulfureo e ne acquisisce uno nuovo all'istante, tornando in vita con tutti i suoi punti ferita da qualche parte nei Nove Inferi.

## Azioni
### Multiattacco
Il diavolo effettua tre attacchi, utilizzando Forcone ardente o Scagliare fiamma in qualsiasi combinazione. Può sostituire un attacco con un utilizzo di Coda infernale.

### Forcone ardente
*Tiro per colpire in mischia:* +10, portata 3 m. *Colpito:* 15 (2d8 + 6) danni perforanti più 9 (2d8) danni da fuoco.

### Scagliare fiamma
*Tiro per colpire a distanza:* +8, gittata 45 m. *Colpito:* 26 (5d8 + 4) danni da fuoco. Se il bersaglio è un oggetto infiammabile che non è indossato o trasportato, inizia a bruciare.

### Coda infernale
*Tiro salvezza su Destrezza:* CD 17, una creatura che il diavolo è in grado di vedere entro 3 metri. *Fallimento:* 10 (1d8 + 6) danni necrotici, e il bersaglio subisce una ferita infernale se non ne ha già una. Finché è ferito, il bersaglio perde 10 (3d6) punti ferita all'inizio di ogni suo turno. La ferita si chiude dopo 1 minuto, dopo che un incantesimo ripristina i punti ferita del bersaglio, o dopo che il bersaglio o una creatura entro 1,5 metri effettua un'azione per tamponare la ferita superando una prova di Saggezza (Medicina) con CD 17.