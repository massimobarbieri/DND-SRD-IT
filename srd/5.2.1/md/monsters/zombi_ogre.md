---
id: zombi_ogre
nome: Zombi ogre
tipo: Non morto
dimensione: Grande
allineamento: neutrale malvagio
classe_armatura: 8
iniziativa:
  valore: 8
  bonus: -2
punti_ferita:
  media: 85
  formula: 9d10 + 36
velocita:
  camminata: 9 m
caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
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
- capisce il Comune e il Gigante ma non li parla
grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)
bonus_competenza: 2
---
## Tratti

### Tempra dei non morti
Se i danni riducono lo zombi a 0 punti ferita, esso effettua un tiro salvezza su Costituzione (CD pari a 5 più i danni subiti), a meno che non si tratti di danni radiosi o di un colpo critico. In caso di successo, scende invece a 1 punto ferita.

## Azioni

### Schianto
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 13 (2d8 + 4) danni contundenti.
