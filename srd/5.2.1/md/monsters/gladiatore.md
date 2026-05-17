---
id: gladiatore
nome: Gladiatore
tipo: Umanoide
dimensione: Medio o Piccolo
allineamento: neutrale

classe_armatura: 16
iniziativa:
  valore: 15
  bonus: 5
punti_ferita:
  media: 112
  formula: 15d8 + 45
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 7
  destrezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 5
  costituzione:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 6
  intelligenza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 4
  carisma:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2

abilita:
  atletica: 10
  intrattenere: 5

equipaggiamento:
  - armatura di cuoio borchiato
  - lance (3)
  - scudo

sensi:
  percezione_passiva: 11

lingue:
  - Comune

grado_sfida:
  valore: 5
  punti_esperienza: 1800
  raw: 5 (PE 1.800; BC +3)

bonus_competenza: 3
---
## Azioni
### Multiattacco
Il gladiatore effettua tre attacchi Lancia. Può sostituire un attacco con un utilizzo di Scudo da sfondamento.

### Lancia
*Tiro per colpire in mischia o a distanza:* +7, portata 1,5 m o gittata 6/18 m. *Colpito:* 11 (2d6 + 4) danni perforanti.

### Scudo da sfondamento
*Tiro salvezza su Forza:* CD 15, una creatura entro 1,5 metri che il gladiatore è in grado di vedere. *Fallimento:* 9 (2d4 + 4) danni contundenti. Se il bersaglio è una creatura di taglia Media o inferiore, cade a terra prono.

## Reazioni
### Parata
*Attivazione:* il gladiatore viene colpito da un tiro per colpire in mischia mentre tiene in mano un'arma.

*Esito:* il gladiatore aggiunge 3 alla sua CA contro quell'attacco, aumentando le probabilità che il colpo non vada a segno.