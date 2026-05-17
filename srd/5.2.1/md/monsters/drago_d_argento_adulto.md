---
id: drago_d_argento_adulto
nome: Drago d'argento adulto
gruppo: Draghi d'argento
tipo: Drago
sottotipo: metallico
dimensione: Enorme
allineamento: legale buono

classe_armatura: 19
iniziativa:
  valore: 20
  bonus: 10
punti_ferita:
  media: 216
  formula: 16d12 + 112
velocita:
  camminata: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 27
    modificatore: 8
    tiro_salvezza: 8
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 5
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
    tiro_salvezza: 6
  carisma:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6

abilita:
  furtivita: 5
  percezione: 11
  storia: 8

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
  valore: 16
  punti_esperienza: 15000
  punti_esperienza_tana: 18000
  raw: 16 (PE 15.000, o 18.000 nella tana; BC +5)

bonus_competenza: 5
---
## Tratti
### Resistenza leggendaria (3/giorno o 4/giorno nella tana)
Se il drago fallisce un tiro salvezza, può scegliere di superarlo comunque.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di (A) Soffio paralizzante o (B) Incantesimi per lanciare coltello di ghiaccio.

### Squarcio
*Tiro per colpire in mischia:* +13, portata 3 m. *Colpito:* 17 (2d8 + 8) danni taglienti più 4 (1d8) danni da freddo.

### Incantesimi
Il drago lancia uno dei seguenti incantesimi, senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 19, +11 al tiro per colpire degli attacchi con incantesimo):

*1/giorno ciascuno:*
- tempesta di ghiaccio (di 5º livello)
- zona di verità

*A volontà:*
- blocca mostri
- coltello di ghiaccio
- individuazione del magico
- trasformazione (solo in forma di bestia o umanoide, senza punti ferita temporanei ottenuti dall'incantesimo, e senza richiedere concentrazione o punti ferita temporanei per mantenere l'incantesimo)

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 20, tutte le creature in un cono di 18 metri. *Fallimento:* 54 (12d8) danni da freddo. *Successo:* danni dimezzati.

### Soffio paralizzante
*Tiro salvezza su Costituzione:* CD 20, tutte le creature in un cono di 18 metri.

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
*Tiro salvezza su Destrezza:* CD 19, tutte le creature in una linea lunga 18 metri e larga 3 metri. *Fallimento:* 14 (4d6) danni da freddo, e il bersaglio viene spinto in linea retta fino a un massimo di 9 metri lontano dal drago. *Successo:* danni dimezzati. *Fallimento o successo:* il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.