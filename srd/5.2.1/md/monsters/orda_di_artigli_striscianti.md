---
id: orda_di_artigli_striscianti
nome: Orda di artigli striscianti
gruppo: Artiglio strisciante
tipo: Sciame
dimensione: Medio
sottotipo: non morti
sottodimensione: Minuscoli
allineamento: neutrale malvagio

classe_armatura:
  valore: 12

iniziativa:
  bonus: 2
  valore: 12

punti_ferita:
  media: 49
  formula: 11d8

velocita:
  camminare: 9 m
  scalare: 9 m

caratteristiche:
  forza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 4
    modificatore: -3
    tiro_salvezza: -3

resistenze:
  - contundente
  - perforante
  - tagliente

immunita_danni:
  - necrotico
  - veleno

immunita_condizione:
  - affascinato
  - afferrato
  - avvelenato
  - incapacitato
  - indebolimento
  - paralizzato
  - pietrificato
  - prono
  - spaventato
  - stordito
  - trattenuto

sensi:
  percezione_passiva: 10
  vista_cieca: 9 m

lingue:
  comprensione:
    - Comune
  parla: false

grado_sfida:
  valore: 3
  punti_esperienza: 700
  raw: 3 (PE 700; BC +2)

bonus_competenza: 2
---
## Tratti
### Sciame
L'orda può occupare lo spazio di un'altra creatura e viceversa, e può muoversi attraverso qualsiasi apertura sufficientemente larga da far passare una creatura di taglia Minuscola. L'orda non può recuperare punti ferita o ottenere punti ferita temporanei.

## Azioni
### Orda di mani afferranti
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 20 (4d8 + 2) danni necrotici, o 11 (2d8 + 2) danni necrotici se l'orda è sanguinante. Se il bersaglio è una creatura di taglia Media o inferiore, cade a terra prono. 