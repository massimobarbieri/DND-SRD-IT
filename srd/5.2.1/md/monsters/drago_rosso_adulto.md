---
id: drago_rosso_adulto
nome: Drago rosso adulto
gruppo: Draghi rossi
tipo: Drago
sottotipo: cromatico
dimensione: Enorme
allineamento: caotico malvagio

classe_armatura: 19
iniziativa:
  valore: 22
  bonus: 12
punti_ferita:
  media: 256
  formula: 19d12 + 133
velocita:
  camminata: 12 m
  scalata: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 27
    modificatore: 8
    tiro_salvezza: 8
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 6
  costituzione:
    punteggio: 25
    modificatore: 7
    tiro_salvezza: 7
  intelligenza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  saggezza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 7
  carisma:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 6

abilita:
  furtivita: 6
  percezione: 13

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 23
  scurovisione: 36 m
  vista_cieca: 18 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 17
  punti_esperienza: 18000
  punti_esperienza_tana: 20000
  raw: 17 (PE 18.000, o 20.000 nella tana; BC +6)

bonus_competenza: 6
---
## Tratti
### Resistenza leggendaria (3/giorno o 4/giorno nella tana)
Se il drago fallisce un tiro salvezza, può scegliere di superarlo comunque.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di Incantesimi per lanciare raggio rovente.

### Squarcio
*Tiro per colpire in mischia:* +14, portata 3 m. *Colpito:* 13 (1d10 + 8) danni taglienti più 5 (2d4) danni da fuoco.

### Incantesimi
Il drago lancia uno dei seguenti incantesimi, senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 20, +12 al tiro per colpire degli attacchi con incantesimo):

*1/giorno:*
- palla di fuoco

*A volontà:*
- comando (di 2º livello)
- individuazione del magico
- raggio rovente

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 21, tutte le creature in un cono di 18 metri. *Fallimento:* 59 (17d6) danni da fuoco. *Successo:* danni dimezzati.

## Azioni leggendarie
### Utilizzi di azioni leggendarie 3 (4 nella tana)
Subito dopo il turno di un'altra creatura, il drago può consumare un utilizzo per effettuare una delle seguenti azioni. Il drago recupera tutti gli utilizzi consumati all'inizio di ogni suo turno.

### Balzo
Il drago si muove fino a metà della sua velocità ed effettua un attacco Squarcio.

### Presenza imponente
Il drago usa Incantesimi per lanciare comando (di 2º livello). Il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.

### Raggi fiammeggianti
Il drago usa Incantesimi per lanciare raggio rovente. Il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.