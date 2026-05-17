---
id: fungo_viola
nome: Fungo viola
gruppo: Funghi
tipo: Vegetale
dimensione: Medio
allineamento: senza allineamento

classe_armatura: 5
iniziativa:
  valore: 5
  bonus: -5
punti_ferita:
  media: 18
  formula: 4d8
velocita:
  camminata: 1,5 m

caratteristiche:
  forza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  destrezza:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
  costituzione:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
  saggezza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5

immunita_condizioni:
  - accecato
  - affascinato
  - assordato
  - spaventato

sensi:
  percezione_passiva: 6
  vista_cieca: 9 m

lingue: []

grado_sfida:
  valore: 0.25
  punti_esperienza: 50
  raw: 1/4 (PE 50; BC +2)

bonus_competenza: 2
---
## Azioni
### Multiattacco
Il fungo effettua due attacchi Tocco marcescente.

### Tocco marcescente
*Tiro per colpire in mischia:* +2, portata 3 m. *Colpito:* 4 (1d8) danni necrotici.