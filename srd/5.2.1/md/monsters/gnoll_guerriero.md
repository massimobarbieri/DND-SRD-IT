---
id: gnoll_guerriero
nome: Gnoll guerriero
gruppo: Gnoll
tipo: Immondo
sottotipo:
dimensione: Medio
allineamento: caotico malvagio

classe_armatura: 15
iniziativa:
  valore: 11
  bonus: 1
punti_ferita:
  media: 27
  formula: 6d8
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
  costituzione:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 7
    modificatore: -2
    tiro_salvezza: -2

sensi:
  percezione_passiva: 10
  scurovisione: 18 m

lingue:
  - Gnoll

grado_sfida:
  valore: 0.5
  punti_esperienza: 100
  raw: 1/2 (PE 100; BC +2)

bonus_competenza: 2
---
## Azioni
### Squarcio
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 5 (1d6 + 2) danni perforanti.

### Arco d'ossa
*Tiro per colpire a distanza:* +3, gittata 45/180 m. *Colpito:* 6 (1d10 + 1) danni perforanti.

## Azioni bonus
### Furia (1/giorno)
Subito dopo aver inflitto danni a una creatura già sanguinante, lo gnoll si muove fino a metà della sua velocità ed effettua un attacco Squarcio.