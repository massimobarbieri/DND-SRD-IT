---
id: bulette
nome: Bulette
tipo: Mostruosità
dimensione: Grande
allineamento: senza allineamento

classe_armatura: 17

iniziativa:
  valore: 10
  bonus: 0

punti_ferita:
  medi: 94
  formula: 9d10 + 45

velocita:
  camminata: 12 m
  scavo: 12 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 2
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3

abilita:
  percezione: 6

sensi:
  percezione_passiva: 16
  percezione_tellurica: 36 m
  scurovisione: 18 m

lingue:
  - Nessuna

grado_sfida:
  valore: 5
  punti_esperienza: 1.800
  raw: 5 (PE 1.800; BC +3)

bonus_competenza: 3
---
## Azioni
### Multiattacco
Il bulette effettua due attacchi Morso.

### Morso
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 17 (2d12 + 4) danni perforanti.

### Balzo letale
Il bulette usa 1,5 metri di movimento per saltare in uno spazio entro 4,5 metri che contiene una o più creature di taglia Grande o inferiore. *Tiro salvezza su Destrezza:* CD 15, tutte le creature nello spazio di destinazione del bulette. *Fallimento:* 19 (3d12) danni contundenti, e il bersaglio è prono. *Successo:* danni dimezzati, e il bersaglio viene spinto a 1,5 metri di distanza dal bulette.

## Azioni bonus
### Balzo
Il bulette salta fino a un massimo di 9 metri usando 3 metri di movimento.