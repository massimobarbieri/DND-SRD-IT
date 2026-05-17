---
id: drago_verde_cucciolo
nome: Drago verde cucciolo
gruppo: Draghi verdi
tipo: Drago
sottotipo: cromatico
dimensione: Medio
allineamento: legale malvagio

classe_armatura: 17
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 38
  formula: 7d8 + 7
velocita:
  camminata: 9 m
  nuoto: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 3
  costituzione:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  intelligenza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1

abilita:
  furtivita: 3
  percezione: 4

immunita_danni:
  - veleno

immunita_condizioni:
  - avvelenato

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
### Anfibio
Il drago può respirare in aria e in acqua.

## Azioni
### Multiattacco
Il drago effettua due attacchi Squarcio.

### Squarcio
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 7 (1d10 + 2) danni taglienti più 3 (1d6) danni da veleno.

### Soffio di veleno (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 11, tutte le creature in un cono di 4,5 metri. *Fallimento:* 21 (6d6) danni da veleno. *Successo:* danni dimezzati.