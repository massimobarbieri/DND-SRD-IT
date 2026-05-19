---
id: zombi
nome: Zombi
tipo: Non morto
dimensione: Medio
allineamento: neutrale malvagio
classe_armatura: 8
iniziativa:
  valore: 8
  bonus: -2
punti_ferita:
  media: 15
  formula: 2d8 + 6
velocita:
  camminata: 6 m
caratteristiche:
  forza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  destrezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  costituzione:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: 0
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
immunita_danni:
- veleno
immunita_condizione:
- avvelenato
- indebolimento
sensi:
  percezione_passiva: 8
  scurovisione: 18 m
lingue:
- capisce il Comune più un'altra lingua ma non le parla
grado_sfida:
  valore: 0.25
  punti_esperienza: 50
  raw: 1/4 (PE 50; BC +2)
bonus_competenza: 2
---
## Tratti

### Tempra dei non morti
Se i danni riducono lo zombi a 0 punti ferita, esso effettua un tiro salvezza su Costituzione (CD pari a 5 più i danni subiti), a meno che non si tratti di danni radiosi o di un colpo critico. In caso di successo, scende invece a 1 punto ferita.

## Azioni

### Schianto
*Tiro per colpire in mischia:* +3, portata 1,5 m. *Colpito:* 5 (1d8 + 1) danni contundenti.
