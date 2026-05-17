---
id: drago_bianco_adulto
nome: Drago bianco adulto
gruppo: Draghi bianchi
tipo: Drago
sottotipo: cromatico
dimensione: Enorme
allineamento: caotico malvagio

classe_armatura: 18
iniziativa:
  valore: 20
  bonus: 10
punti_ferita:
  media: 200
  formula: 16d12 + 96
velocita:
  camminata: 12 m
  nuoto: 12 m
  scavo: 9 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 5
  costituzione:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6
  intelligenza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  saggezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 6
  carisma:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1

abilita:
  furtivita: 5
  percezione: 11

immunita_danni:
  - freddo

sensi:
  percezione_passiva: 21
  scurovisione: 36 m
  vista_cieca: 18 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 13
  punti_esperienza: 10000
  punti_esperienza_tana: 11500
  raw: 13 (PE 10.000, o 11.500 nella tana; BC +5)

bonus_competenza: 5
---
## Tratti
### Camminare sul ghiaccio
Il drago può muoversi sulle superfici di ghiaccio e scalarle senza bisogno di effettuare una prova di caratteristica. Inoltre, un terreno difficile costituito da ghiaccio o neve non gli costa alcun movimento aggiuntivo.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio.

### Squarcio
*Tiro per colpire in mischia:* +11, portata 3 m. *Colpito:* 13 (2d6 + 6) danni taglienti più 4 (1d8) danni da freddo.

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 19, tutte le creature in un cono di 18 metri. *Fallimento:* 54 (12d8) danni da freddo. *Successo:* danni dimezzati.

## Azioni leggendarie
### Utilizzi di azioni leggendarie 3 (4 nella tana)
Subito dopo il turno di un'altra creatura, il drago può consumare un utilizzo per effettuare una delle seguenti azioni. Il drago recupera tutti gli utilizzi consumati all'inizio di ogni suo turno.

### Esplosione congelante
*Tiro salvezza su Costituzione:* CD 14, tutte le creature in una sfera di 9 metri di raggio centrata su un punto che il drago è in grado di vedere entro 36 metri. *Fallimento:* 7 (2d6) danni da freddo, e la velocità del bersaglio è pari a 0 fino al termine del turno successivo del bersaglio. *Fallimento o successo:* il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.

### Presenza terrificante
Il drago lancia paura senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 14). Il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.

### Balzo
Il drago si muove fino a metà della sua velocità ed effettua un attacco Squarcio.