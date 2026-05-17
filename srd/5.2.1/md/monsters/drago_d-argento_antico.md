---
id: drago_d_argento_antico
nome: Drago d'argento antico
gruppo: Draghi d'argento
tipo: Drago
sottotipo: metallico
dimensione: Mastodontico
allineamento: legale buono

classe_armatura: 22
iniziativa:
  valore: 24
  bonus: 14
punti_ferita:
  media: 468
  formula: 24d20 + 216
velocita:
  camminata: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 30
    modificatore: 10
    tiro_salvezza: 10
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 7
  costituzione:
    punteggio: 29
    modificatore: 9
    tiro_salvezza: 9
  intelligenza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  saggezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 9
  carisma:
    punteggio: 26
    modificatore: 8
    tiro_salvezza: 8

abilita:
  furtivita: 7
  percezione: 16
  storia: 11

immunita_danni:
  - freddo

sensi:
  percezione_passiva: 26
  scurovisione: 36 m
  vista_cieca: 18 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 23
  punti_esperienza: 50000
  punti_esperienza_tana: 62000
  raw: 23 (PE 50.000, o 62.000 nella tana; BC +7)

bonus_competenza: 7
---
## Tratti
### Resistenza leggendaria (4/giorno o 5/giorno nella tana)
Se il drago fallisce un tiro salvezza, può scegliere di superarlo comunque.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di (A) Soffio paralizzante o (B) Incantesimi per lanciare coltello di ghiaccio (di 2º livello).

### Squarcio
*Tiro per colpire in mischia:* +17, portata 4,5 m. *Colpito:* 19 (2d8 + 10) danni taglienti più 9 (2d8) danni da freddo.

### Incantesimi
Il drago lancia uno dei seguenti incantesimi, senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 23, +15 al tiro per colpire degli attacchi con incantesimo):

1/giorno ciascuno:
- controllare tempo atmosferico
- teletrasporto
- tempesta di ghiaccio (di 7º livello)
- zona di verità

A volontà:
- blocca mostri
- coltello di ghiaccio (di 2º livello)
- individuazione del magico
- trasformazione (solo in forma di bestia o umanoide, senza punti ferita temporanei ottenuti dall'incantesimo, e senza richiedere concentrazione o punti ferita temporanei per mantenere l'incantesimo)

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 24, tutte le creature in un cono di 27 metri. *Fallimento:* 67 (15d8) danni da freddo. *Successo:* danni dimezzati.

### Soffio paralizzante
*Tiro salvezza su Costituzione:* CD 24, tutte le creature in un cono di 27 metri.

*Primo fallimento:* il bersaglio è incapacitato fino al termine del proprio turno successivo. A quel punto, ripete il tiro salvezza.

*Secondo fallimento:* il bersaglio è paralizzato e ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.

## Azioni leggendarie
### Utilizzi di azioni leggendarie 3 (4 nella tana)
Subito dopo il turno di un'altra creatura, il drago può consumare un utilizzo per effettuare una delle seguenti azioni. Il drago recupera tutti gli utilizzi consumati all'inizio di ogni suo turno.

### Assideramento
Il drago usa Incantesimi per lanciare blocca mostri. Il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.

### Balzo
Il drago si muove fino a metà della sua velocità, ed effettua un attacco Squarcio.

### Bufera
*Tiro salvezza su Destrezza:* CD 23, tutte le creature in una linea lunga 18 metri e larga 3 metri. *Fallimento:* 14 (4d6) danni da freddo, e il bersaglio viene spinto in linea retta fino a un massimo di 9 metri lontano dal drago. *Successo:* danni dimezzati. *Fallimento o successo:* il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.