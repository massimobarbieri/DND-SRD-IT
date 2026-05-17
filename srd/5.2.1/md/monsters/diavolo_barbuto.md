---
id: diavolo_barbuto
nome: Diavolo barbuto
tipo: Immondo
sottotipo: diavolo
dimensione: Medio
allineamento: legale malvagio

classe_armatura: 13
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 58
  formula: 9d8 + 18
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 5
  destrezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 4
  intelligenza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 4

resistenze:
  - freddo

immunita_danni:
  - fuoco
  - veleno

immunita_condizioni:
  - avvelenato
  - spaventato

sensi:
  percezione_passiva: 10
  scurovisione: 36 m non ostacolata dall'oscurità magica

lingue:
  - Infernale
  - telepatia 36 m

grado_sfida:
  valore: 3
  punti_esperienza: 700
  raw: 3 (PE 700; BC +2)

bonus_competenza: 2
---
## Tratti
### Resistenza alla magia
Il diavolo dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

## Azioni
### Multiattacco
Il diavolo effettua un attacco Barba e un attacco Falcione infernale.

### Barba
*Tiro per colpire in mischia:* +5, portata 1,5 m. *Colpito:* 7 (1d8 + 3) danni perforanti, e il bersaglio è avvelenato fino all'inizio del turno successivo del diavolo. Finché è avvelenato, il bersaglio non può recuperare punti ferita.

### Falcione infernale
*Tiro per colpire in mischia:* +5, portata 3 m. *Colpito:* 8 (1d10 + 3) danni taglienti. Se il bersaglio è una creatura e non ha già una ferita infernale, subisce il seguente effetto.

*Tiro salvezza su Costituzione:* CD 12.

*Fallimento:* il bersaglio subisce una ferita infernale. Finché è ferito, il bersaglio perde 5 (1d10) punti ferita all'inizio di ogni suo turno. La ferita si rimargina dopo 1 minuto, dopo che un incantesimo ripristina i punti ferita del bersaglio, o dopo che il bersaglio o una creatura entro 1,5 metri effettua un'azione per tamponare la ferita superando una prova di Saggezza (Medicina) con CD 12.