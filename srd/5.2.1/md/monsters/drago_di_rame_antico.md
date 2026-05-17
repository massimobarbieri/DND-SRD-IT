---
id: drago_di_rame_antico
nome: Drago di rame antico
gruppo: Draghi di rame
tipo: Drago
sottotipo: metallico
dimensione: Mastodontico
allineamento: caotico buono

classe_armatura: 21
iniziativa:
  valore: 25
  bonus: 15
punti_ferita:
  media: 367
  formula: 21d20 + 147
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
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 8
  costituzione:
    punteggio: 25
    modificatore: 7
    tiro_salvezza: 7
  intelligenza:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  saggezza:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 10
  carisma:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6

abilita:
  furtivita: 8
  inganno: 13
  percezione: 17

immunita_danni:
  - acido

sensi:
  percezione_passiva: 27
  scurovisione: 36 m
  vista_cieca: 18 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 21
  punti_esperienza: 33000
  punti_esperienza_tana: 41000
  raw: 21 (PE 33.000, o 41.000 nella tana; BC +7)

bonus_competenza: 7
---
## Tratti
### Resistenza leggendaria (4/giorno o 5/giorno nella tana)
Se il drago fallisce un tiro salvezza, può scegliere di superarlo comunque.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di (A) Soffio rallentante o (B) Incantesimi per lanciare aculeo mentale (di 5º livello).

### Squarcio
*Tiro per colpire in mischia:* +15, portata 4,5 m. *Colpito:* 19 (2d10 + 8) danni taglienti più 9 (2d8) danni da acido.

### Incantesimi
Il drago lancia uno dei seguenti incantesimi, senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 21):

*1/giorno ciascuno:*
- immagine maggiore
- immagine proiettata
- ristorare superiore

*A volontà:*
- aculeo mentale (di 5º livello)
- illusione minore
- individuazione del magico
- trasformazione (solo in forma di bestia o umanoide, senza punti ferita temporanei ottenuti dall'incantesimo, e senza richiedere concentrazione o punti ferita temporanei per mantenere l'incantesimo)

### Soffio di acido (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 22, tutte le creature in una linea lunga 27 metri e larga 3 metri. *Fallimento:* 63 (14d8) danni da acido. *Successo:* danni dimezzati.

### Soffio rallentante
*Tiro salvezza su Costituzione:* CD 22, tutte le creature in un cono di 27 metri. *Fallimento:* il bersaglio non può effettuare reazioni, la sua velocità è dimezzata e nel suo turno può effettuare un'azione o un'azione bonus, non entrambe. L'effetto dura fino al termine del proprio turno successivo.

## Azioni leggendarie
### Utilizzi di azioni leggendarie 3 (4 nella tana)
Subito dopo il turno di un'altra creatura, il drago può consumare un utilizzo per effettuare una delle seguenti azioni. Il drago recupera tutti gli utilizzi consumati all'inizio di ogni suo turno.

### Balzo
Il drago si muove fino a metà della sua velocità, ed effettua un attacco Squarcio.

### Magia ridacchiante
*Tiro salvezza su Carisma:* CD 21, una creatura che il drago è in grado di vedere entro 36 metri. *Fallimento:* 31 (9d6) danni psichici. Fino al termine del proprio turno successivo, il bersaglio tira 1d8 ogni volta che effettua una prova di caratteristica o un tiro per colpire e sottrae il risultato dalla prova con d20. *Fallimento o successo:* il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.

### Scossa mentale
Il drago usa Incantesimi per lanciare aculeo mentale (di 5º livello). Il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.