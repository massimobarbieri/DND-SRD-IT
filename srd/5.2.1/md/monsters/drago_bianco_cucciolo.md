---
id: drago_bianco_cucciolo
nome: Drago bianco cucciolo
gruppo: Draghi bianchi
tipo: Drago
sottotipo: cromatico
dimensione: Medio
allineamento: caotico malvagio

classe_armatura: 16
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 32
  formula: 5d8 + 10
velocita:
  camminata: 9 m
  nuoto: 9 m
  scavo: 4,5 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 2
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0

abilita:
  furtivita: 2
  percezione: 4

immunita_danni:
  - freddo

sensi:
  percezione_passiva: 14
  scurovisione: 18 m
  vista_cieca: 3 m

lingue:
  - Draconico

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Tratti
### Camminare sul ghiaccio
Il drago può muoversi sulle superfici di ghiaccio e scalarle senza bisogno di effettuare una prova di caratteristica. Inoltre, un terreno difficile costituito da ghiaccio o neve non gli costa alcun movimento aggiuntivo.

## Azioni
### Multiattacco
Il drago effettua due attacchi Squarcio.

### Squarcio
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 6 (1d8 + 2) danni taglienti più 2 (1d4) danni da freddo.

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 12, tutte le creature in un cono di 4,5 metri. *Fallimento:* 22 (5d8) danni da freddo. *Successo:* danni dimezzati.