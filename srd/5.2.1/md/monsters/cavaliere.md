---
id: cavaliere
nome: Cavaliere
tipo: Umanoide
dimensione: Medio o Piccolo
allineamento: neutrale

classe_armatura: 18

iniziativa:
  valore: 10
  bonus: 0

punti_ferita:
  medi: 52
  formula: 8d8 + 16

velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  destrezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 4
  intelligenza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2

equipaggiamento:
  - armatura a piastre
  - balestra pesante
  - spadone  

immunita_condizioni:
  - spaventato  
sensi:
  percezione_passiva: 10

lingue:
  - Comune più un'altra lingua

grado_sfida:
  valore: 23
  punti_esperienza: 700
  raw: 3 (PE 700; BC +2)

bonus_competenza: 2
---
## Azioni
### Multiattacco
Il cavaliere effettua due attacchi, usando Spadone o Balestra pesante in qualsiasi combinazione.

### Spadone
*Tiro per colpire in mischia:* +5, portata 1,5 m *Colpito:* 10 (2d6 + 3) danni taglienti più 4 (1d8) danni radiosi.

### Balestra pesante
*Tiro per colpire a distanza:* +2, gittata 30/120 m. *Colpito:* 11 (2d10) danni perforanti più 4 (1d8) danni radiosi.

## Reazioni
### Parata
*Attivazione:* il cavaliere viene colpito da un tiro per colpire in mischia mentre tiene in mano un'arma. *Esito:* il cavaliere aggiunge 2 alla sua CA contro quell'attacco, aumentando le probabilità che il colpo non vada a segno.