---
id: drago_d_argento_cucciolo
nome: Drago d'argento cucciolo
gruppo: Draghi d'argento
tipo: Drago
sottotipo: metallico
dimensione: Medio
allineamento: legale buono

classe_armatura: 17
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 45
  formula: 6d8 + 18
velocita:
  camminata: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 2
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
    tiro_salvezza: 2
  carisma:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2

abilita:
  furtivita: 2
  percezione: 4

immunita_danni:
  - freddo

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
## Azioni
### Multiattacco
Il drago effettua due attacchi Squarcio.

### Squarcio
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 9 (1d10 + 4) danni perforanti.

### Soffio di freddo (ricarica 5-6)
*Tiro salvezza su Costituzione:* CD 13, tutte le creature in un cono di 4,5 metri. *Fallimento:* 18 (4d8) danni da freddo. *Successo:* danni dimezzati.

### Soffio paralizzante
*Tiro salvezza su Costituzione:* CD 13, tutte le creature in un cono di 4,5 metri. *Primo fallimento:* il bersaglio è incapacitato fino al termine del proprio turno successivo. A quel punto, ripete il tiro salvezza. *Secondo fallimento:* il bersaglio è paralizzato e ripete il tiro salvezza alla fine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente.