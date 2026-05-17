---
id: drago_d_oro_giovane
nome: Drago d'oro giovane
gruppo: Draghi d'oro
tipo: Drago
sottotipo: metallico
dimensione: Grande
allineamento: legale buono

classe_armatura: 18
iniziativa:
  valore: 16
  bonus: 6
punti_ferita:
  media: 178
  formula: 17d10 + 85
velocita:
  camminata: 12 m
  nuoto: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 6
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  saggezza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 5
  carisma:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5

abilita:
  furtivita: 6
  intuizione: 5
  percezione: 9
  persuasione: 9

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 19
  scurovisione: 36 m
  vista_cieca: 9 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 10
  punti_esperienza: 5900
  raw: 10 (PE 5.900; BC +4)

bonus_competenza: 4
---
## Tratti
### Anfibio
Il drago può respirare in aria e in acqua.

## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di Soffio indebolente.

### Squarcio
*Tiro per colpire in mischia:* +10, portata 3 m. *Colpito:* 17 (2d10 + 6) danni taglienti.

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 17, tutte le creature in un cono di 9 metri. *Fallimento:* 55 (10d10) danni da fuoco. *Successo:* danni dimezzati.

### Soffio indebolente
*Tiro salvezza su Forza:* CD 17, ogni creatura che al momento non è sotto l'effetto di questo soffio in un cono di 9 metri. *Fallimento:* il bersaglio subisce svantaggio alle prove con d20 basate sulla Forza e sottrae 3 (1d6) ai tiri per i danni. La creatura ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.