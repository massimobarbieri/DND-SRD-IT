---
id: drago_d_oro_antico
nome: Drago d'oro antico
gruppo: Draghi d'oro
tipo: Drago
sottotipo: metallico
dimensione: Mastodontico
allineamento: legale buono

classe_armatura: 22
iniziativa:
  valore: 26
  bonus: 16
punti_ferita:
  media: 546
  formula: 28d20 + 252
velocita:
  camminata: 12 m
  nuoto: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 30
    modificatore: 10
    tiro_salvezza: 10
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 9
  costituzione:
    punteggio: 29
    modificatore: 9
    tiro_salvezza: 9
  intelligenza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  saggezza:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 10
  carisma:
    punteggio: 28
    modificatore: 9
    tiro_salvezza: 9

abilita:
  furtivita: 9
  intuizione: 10
  percezione: 17
  persuasione: 16

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 27
  scurovisione: 36 m
  vista_cieca: 18 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 24
  punti_esperienza: 62000
  punti_esperienza_tana: 75000
  raw: 24 (PE 62.000, o 75.000 nella tana; BC +7)

bonus_competenza: 7
---
## Tratti
### Anfibio
Il drago può respirare in aria e in acqua.

### Resistenza leggendaria (4/giorno o 5/giorno nella tana)
Se il drago fallisce un tiro salvezza, può scegliere di superarlo comunque.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di (A) Incantesimi per lanciare dardo tracciante (di 4º livello) o (B) Soffio indebolente.

### Squarcio
*Tiro per colpire in mischia:* +17 al tiro per colpire, portata 4,5 m. *Colpito:* 19 (2d8 + 10) danni taglienti più 9 (2d8) danni da fuoco.

### Incantesimi
Il drago lancia uno dei seguenti incantesimi, senza bisogno di componenti materiali, utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 24, +16 al tiro per colpire degli attacchi con incantesimo):

*1/giorno ciascuno:*
- colpo infuocato (versione di 6º livello)
- parola del ritiro
- zona di verità

*A volontà:*
- dardo tracciante (di 4º livello)
- individuazione del magico
- trasformazione (solo in forma di bestia o umanoide, senza punti ferita temporanei ottenuti dall'incantesimo, e senza richiedere concentrazione o punti ferita temporanei per mantenere l'incantesimo)

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 24, tutte le creature in un cono di 27 metri. *Fallimento:* 71 (13d10) danni da fuoco. *Successo:* danni dimezzati.

### Soffio indebolente
*Tiro salvezza su Forza:* CD 24, ogni creatura che al momento non è sotto l'effetto di questo soffio in un cono di 27 metri. *Fallimento:* il bersaglio subisce svantaggio alle prove con d20 basate sulla Forza e sottrae 5 (1d10) ai tiri per i danni. La creatura ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.

## Azioni leggendarie
### Utilizzi di azioni leggendarie 3 (4 nella tana)
Subito dopo il turno di un'altra creatura, il drago può consumare un utilizzo per effettuare una delle seguenti azioni. Il drago recupera tutti gli utilizzi consumati all'inizio di ogni suo turno.

### Balzo
Il drago si muove fino a metà della sua velocità, ed effettua un attacco Squarcio.

### Luce guida
Il drago usa Incantesimi per lanciare dardo tracciante (di 4º livello).

### Ostracismo
*Tiro salvezza su Carisma:* CD 24, una creatura che il drago è in grado di vedere entro 36 metri. *Fallimento:* 24 (7d6) danni da forza, il bersaglio è incapacitato e viene trasportato su un semipiano sicuro fino all'inizio del turno successivo del drago, durante cui riappare in uno spazio libero a scelta del drago entro 36 metri da quest'ultimo. *Fallimento o successo:* il drago non può ripetere quest'azione fino all'inizio del proprio turno successivo.