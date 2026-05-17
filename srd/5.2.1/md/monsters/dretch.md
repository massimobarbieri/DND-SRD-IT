---
id: dretch
nome: Dretch
tipo: Immondo
sottotipo: demone
dimensione: Piccolo
allineamento: caotico malvagio

classe_armatura: 11
iniziativa:
  valore: 10
  bonus: 0
punti_ferita:
  media: 18
  formula: 4d6 + 4
velocita:
  camminata: 6 m

caratteristiche:
  forza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
  destrezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
  intelligenza:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  carisma:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4

resistenze:
  - freddo
  - fulmine
  - fuoco

immunita_danni:
  - veleno

immunita_condizioni:
  - avvelenato

sensi:
  percezione_passiva: 9
  scurovisione: 18 m

lingue:
  - Abissale
  - telepatia 18 m (funziona solo con le creature che capiscono l'Abissale)

grado_sfida:
  valore: 0.25
  punti_esperienza: 50
  raw: 1/4 (PE 50; BC +2)

bonus_competenza: 2
---
## Azioni
### Squarcio
*Tiro per colpire in mischia:* +3, portata 1,5 m. *Colpito:* 4 (1d6 + 1) danni taglienti.

### Nube fetida (1/giorno)
*Tiro salvezza su Costituzione:* CD 11, tutte le creature in un'emanazione di 3 metri di cui il dretch è il punto di origine. *Fallimento:* il bersaglio è avvelenato fino al termine del proprio turno successivo. Finché è avvelenata, la creatura può effettuare nel suo turno un'azione o un'azione bonus, ma non entrambe, e non può effettuare reazioni.