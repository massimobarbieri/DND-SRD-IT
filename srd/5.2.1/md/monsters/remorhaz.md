---
id: remorhaz
nome: Remorhaz
tipo: Mostruosità
dimensione: Enorme
allineamento: senza allineamento
classe_armatura: 17
iniziativa:
  valore: 15
  bonus: 5
punti_ferita:
  media: 195
  formula: 17d12 + 85
velocita:
  camminata: scavo 9 m
caratteristiche:
  forza:
    punteggio: 24
    modificatore: 7
    tiro_salvezza: 7
  destrezza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 4
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
immunita_danni:
- freddo
- fuoco
sensi:
  percezione_passiva: 10
  percezione_tellurica: 18 m
  scurovisione: 18 m
lingue:
- nessuna
grado_sfida:
  valore: 11
  punti_esperienza: 7200
  raw: 11 (PE 7.200; BC +4)
bonus_competenza: 4
---
## Tratti

### Aura di calore
Al termine di ogni turno del remorhaz, tutte le creature in un'emanazione di 1,5 metri di cui il remorhaz è il punto di origine subiscono 16 (3d10) danni da fuoco.

## Azioni

### Morso
*Tiro per colpire in mischia:* +11, portata 3 m. *Colpito:* 18 (2d10 + 7) danni perforanti più 14 (4d6) danni da fuoco. Se il bersaglio è una creatura di taglia Grande o inferiore, è afferrato (CD 17 per sfuggire), ed è trattenuto finché la presa perdura.

## Azioni bonus

### Inghiottire
*Tiro salvezza su Forza:* CD 19, una creatura di taglia Grande o inferiore afferrata dal remorhaz (può inghiottire fino a due creature per volta). *Fallimento:* il bersaglio viene inghiottito dal remorhaz, e non è più afferrato. Una creatura inghiottita è accecata e trattenuta, beneficia di copertura totale contro attacchi e altri effetti al di fuori del remorhaz, e subisce 10 (3d6) danni da acido più 10 (3d6) danni da fuoco all'inizio di ogni turno del remorhaz. Se il remorhaz subisce 30 o più danni in un singolo turno da una creatura al suo interno, deve superare un tiro salvezza su Costituzione con CD 15 alla fine di quel turno, altrimenti rigurgita tutte le creature inghiottite, ognuna delle quali cade a terra prona in uno spazio entro 1,5 metri dal remorhaz. Se il remorhaz muore, qualsiasi creatura inghiottita non è più trattenuta e può fuggire dal cadavere usando 4,5 metri di movimento, uscendo prona.
