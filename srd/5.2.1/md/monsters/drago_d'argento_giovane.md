---
id: drago_d_argento_giovane
nome: Drago d'argento giovane
gruppo: Draghi d'argento
tipo: Drago
sottotipo: metallico
dimensione: Grande
allineamento: legale buono

classe_armatura: 18
iniziativa:
  valore: 14
  bonus: 4
punti_ferita:
  media: 168
  formula: 16d10 + 80
velocita:
  camminata: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 4
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 4
  carisma:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4

abilita:
  furtivita: 4
  percezione: 8
  storia: 6

immunita_danni:
  - freddo

sensi:
  percezione_passiva: 18
  scurovisione: 36 m
  vista_cieca: 9 m

lingue:
  - Comune
  - Draconico

grado_sfida:
  valore: 9
  punti_esperienza: 5000
  raw: 9 (PE 5.000; BC +4)

bonus_competenza: 4
---
## Azioni
### Multiattacco
Il drago effettua tre attacchi Squarcio. Può sostituire un attacco con un utilizzo di Soffio paralizzante.

### Squarcio
*Tiro per colpire in mischia:* +10, portata 3 m. *Colpito:* 15 (2d8 + 6) danni taglienti.

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 17, tutte le creature in un cono di 9 metri. *Fallimento:* 49 (11d8) danni da freddo. *Successo:* danni dimezzati.

### Soffio paralizzante
*Tiro salvezza su Costituzione:* CD 17, tutte le creature in un cono di 9 metri.

*Primo fallimento:* il bersaglio è incapacitato fino al termine del proprio turno successivo. A quel punto, ripete il tiro salvezza.

*Secondo fallimento:* il bersaglio è paralizzato e ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.