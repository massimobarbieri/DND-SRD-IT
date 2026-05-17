---
id: drago_di_rame_cucciolo
nome: Drago di rame cucciolo
gruppo: Draghi di rame
tipo: Drago
sottotipo: metallico
dimensione: Medio
allineamento: caotico buono

classe_armatura: 16
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 22
  formula: 4d8 + 4
velocita:
  camminata: 9 m
  scalata: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 3
  costituzione:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  intelligenza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1

abilita:
  furtivita: 3
  percezione: 4

immunita_danni:
  - acido

sensi:
  percezione_passiva: 14
  scurovisione: 18 m
  vista_cieca: 3 m

lingue:
  - Draconico

grado_sfida:
  valore: 1
  punti_esperienza: 200
  raw: 1 (PE 200; BC +2)

bonus_competenza: 2
---
## Azioni
### Squarcio
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 7 (1d10 + 2) danni taglienti.

### Soffio di acido (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 11, tutte le creature in una linea lunga 6 metri e larga 1,5 metri. *Fallimento:* 18 (4d8) danni da acido. *Successo:* danni dimezzati.

### Soffio rallentante
*Tiro salvezza su Costituzione:* CD 11, tutte le creature in un cono di 4,5 metri. *Fallimento:* il bersaglio non può effettuare reazioni, la sua velocità è dimezzata e nel suo turno può effettuare un'azione o un'azione bonus, non entrambe. L'effetto dura fino al termine del proprio turno successivo.