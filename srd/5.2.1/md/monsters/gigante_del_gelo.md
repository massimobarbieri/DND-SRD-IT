---
id: gigante_del_gelo
nome: Gigante del gelo
gruppo: Giganti
tipo: Gigante
dimensione: Enorme
allineamento: neutrale malvagio

classe_armatura: 15
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 149
  formula: 13d12 + 65
velocita:
  camminata: 12 m

caratteristiche:
  forza:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 21
    modificatore: 5
    tiro_salvezza: 8
  intelligenza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 3
  carisma:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 4

abilita:
  atletica: 9
  percezione: 3

immunita_danni:
  - freddo

sensi:
  percezione_passiva: 13

lingue:
  - Gigante

grado_sfida:
  valore: 8
  punti_esperienza: 3900
  raw: 8 (PE 3.900; BC +3)

bonus_competenza: 3
---
## Azioni
### Multiattacco
Il gigante effettua due attacchi, usando Ascia del gelo o Grande arco in qualsiasi combinazione.

### Ascia del gelo
*Tiro per colpire in mischia:* +9, portata 3 m. *Colpito:* 19 (2d12 + 6) danni taglienti più 9 (2d8) danni da freddo.

### Grande arco
*Tiro per colpire a distanza:* +9, gittata 45/180 m. *Colpito:* 17 (2d10 + 6) danni perforanti più 7 (2d6) danni da freddo, e la velocità del bersaglio è ridotta di 3 metri fino al termine del proprio turno successivo.

## Azioni bonus
### Grido di battaglia (ricarica 5-6)
Il gigante o una creatura a sua scelta che il gigante è in grado di vedere o di sentire ottiene 16 (2d10 + 5) punti ferita temporanei e dispone di vantaggio ai tiri per colpire fino all'inizio del turno successivo del gigante.