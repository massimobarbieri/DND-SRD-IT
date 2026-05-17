---
id: drago_d_ottone_giovane
nome: Drago d'ottone giovane
gruppo: Draghi d'ottone
tipo: Drago
sottotipo: metallico
dimensione: Grande
allineamento: caotico buono

classe_armatura: 17
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 110
  formula: 13d10 + 39
velocita:
  camminata: 12 m
  scavo: 6 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 3
  costituzione:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 3
  intelligenza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 3
  carisma:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2

abilita:
  furtivita: 3
  percezione: 6
  persuasione: 5

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 16
  scurovisione: 36 m
  vista_cieca: 9 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 6
  punti_esperienza: 2300
  raw: 6 (PE 2.300; BC +3)

bonus_competenza: 3
---
## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire due attacchi con un utilizzo di Soffio di sonno.

### Squarcio
*Tiro per colpire in mischia:* +7, portata 3 m. *Colpito:* 15 (2d10 + 4) danni taglienti.

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 14, tutte le creature in una linea lunga 12 metri e larga 1,5 metri. *Fallimento:* 38 (11d6) danni da fuoco. *Successo:* danni dimezzati.

### Soffio di sonno
*Tiro salvezza su Costituzione:* CD 14, tutte le creature in un cono di 9 metri. *Fallimento:* il bersaglio è incapacitato fino al termine del proprio turno successivo, a quel punto ripete il tiro salvezza.

*Secondo fallimento:* il bersaglio cade privo di sensi per 1 minuto. Questo effetto termina se il bersaglio subisce danni o se una creatura entro 1,5 metri da esso esegue un'azione per svegliarlo.