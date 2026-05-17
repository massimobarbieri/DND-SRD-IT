---
id: drago_d_oro_cucciolo
nome: Drago d'oro cucciolo
gruppo: Draghi d'oro
tipo: Drago
sottotipo: metallico
dimensione: Medio
allineamento: legale buono

classe_armatura: 17
iniziativa:
  valore: 14
  bonus: 4
punti_ferita:
  media: 60
  formula: 8d8 + 24
velocita:
  camminata: 9 m
  nuoto: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 4
  costituzione:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 3
  intelligenza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3

abilita:
  furtivita: 4
  percezione: 4

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 14
  scurovisione: 18 m
  vista_cieca: 3 m

lingue:
  - Draconico

grado_sfida:
  valore: 3
  punti_esperienza: 700
  raw: 3 (PE 700; BC +2)

bonus_competenza: 2
---
## Tratti
### Anfibio
Il drago può respirare in aria e in acqua.

## Azioni
### Multiattacco
Il drago effettua due attacchi Squarcio.

### Squarcio
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 9 (1d10 + 4) danni taglienti.

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 13, tutte le creature in un cono di 4,5 metri. *Fallimento:* 22 (4d10) danni da fuoco. *Successo:* danni dimezzati.

### Soffio indebolente
*Tiro salvezza su Forza:* CD 13, ogni creatura che al momento non è sotto l'effetto di questo soffio in un cono di 4,5 metri. *Fallimento:* il bersaglio subisce svantaggio alle prove con d20 basate sulla Forza e sottrae 2 (1d4) ai tiri per i danni. La creatura ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.