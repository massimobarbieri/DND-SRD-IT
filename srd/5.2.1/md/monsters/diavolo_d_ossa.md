---
id: diavolo_d_ossa
nome: Diavolo d'ossa
tipo: Immondo
sottotipo: diavolo
dimensione: Grande
allineamento: legale malvagio

classe_armatura: 16
iniziativa:
  valore: 17
  bonus: 7
punti_ferita:
  media: 161
  formula: 17d10 + 68
velocita:
  camminata: 12 m
  volo: 12 m

caratteristiche:
  forza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 8
  destrezza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 5
  saggezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 6
  carisma:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 7

abilita:
  inganno: 7
  intuizione: 6

resistenze:
  - freddo

immunita_danni:
  - fuoco
  - veleno

immunita_condizioni:
  - avvelenato

sensi:
  percezione_passiva: 12
  scurovisione: 36 m
  dettagli_scurovisione: non ostacolata dall'oscurità magica

lingue:
  - Infernale
  - telepatia 36 m

grado_sfida:
  valore: 9
  punti_esperienza: 5000
  raw: 9 (PE 5.000; BC +4)

bonus_competenza: 4
---
## Tratti
### Resistenza alla magia
Il diavolo dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

### Ristoro diabolico
Se il diavolo muore al di fuori dei Nove Inferi, il suo corpo si dissolve in fumo sulfureo e ne acquisisce uno nuovo all'istante, tornando in vita con tutti i suoi punti ferita da qualche parte nei Nove Inferi.

## Azioni
### Multiattacco
Il diavolo effettua due attacchi Artiglio e un attacco Pungiglione infernale.

### Artiglio
*Tiro per colpire in mischia:* +8, portata 3 m. *Colpito:* 13 (2d8 + 4) danni taglienti.

### Pungiglione infernale
*Tiro per colpire in mischia:* +8, portata 3 m. *Colpito:* 15 (2d10 + 4) danni perforanti più 18 (4d8) danni da veleno, e il bersaglio è avvelenato fino all'inizio del turno successivo del diavolo. Finché è avvelenato, il bersaglio non può recuperare punti ferita.