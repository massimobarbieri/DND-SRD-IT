---
id: capo_dei_banditi
nome: Capo dei Banditi
gruppo: Banditi
tipo: Umanoide
dimensione: Medio o Piccolo
allineamento: neutrale

classe_armatura:
  valore: 15

iniziativa:
  valore: 13
  bonus: 3

punti_ferita:
  media: 52
  formula: 8d8 + 16

velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 4
  destrezza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 5
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2

abilita:
  atletica: 4
  inganno: 4  

equipaggiamento:
  - armatura di cuoio borchiato
  - pistola
  - scimitarra

sensi:
  percezione_passiva: 10
lingue:
  - Comune
  - Gergo ladresco  

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Azioni
### Multiattacco
Il bandito effettua due attacchi, usando Scimitarra e Pistola in qualsiasi combinazione

### Pistola
*Tiro per colpire a distanza:* +5, gittata 9/27 m. *Colpito:* 8 (1d10 + 3) danni perforanti.

### Scimitarra
*Tiro per colpire in mischia:* +5, portata 1,5 m. *Colpito:* 6 (1d6 + 3) danni taglienti.

## Reazioni
### Parata
*Attivazione:* il bandito viene colpito da un tiro per colpire in mischia mentre tiene in mano un'arma. *Esito:* il bandito aggiunge 2 alla sua CA contro quell'attacco, aumentando le probabilità che il colpo non vada a segno.