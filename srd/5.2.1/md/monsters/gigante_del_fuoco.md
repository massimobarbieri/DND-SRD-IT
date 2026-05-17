---
id: gigante_del_fuoco
nome: Gigante del fuoco
gruppo: Giganti
tipo: Gigante
dimensione: Enorme
allineamento: legale malvagio

classe_armatura: 18
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 162
  formula: 13d12 + 78
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 25
    modificatore: 7
    tiro_salvezza: 7
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: 3
  costituzione:
    punteggio: 23
    modificatore: 6
    tiro_salvezza: 10
  intelligenza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  carisma:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 5

abilita:
  atletica: 11
  percezione: 6

immunita_danni:
  - fuoco

sensi:
  percezione_passiva: 16

lingue:
  - Gigante

grado_sfida:
  valore: 9
  punti_esperienza: 5000
  raw: 9 (PE 5.000; BC +4)

bonus_competenza: 4
---
## Azioni
### Multiattacco
Il gigante effettua due attacchi, usando Spada di fiamme o Lancio di martello in qualsiasi combinazione.

### Spada di fiamme
*Tiro per colpire in mischia:* +11, portata 3 m. *Colpito:* 21 (4d6 + 7) danni taglienti più 10 (3d6) danni da fuoco.

### Lancio di martello
*Tiro per colpire a distanza:* +11, portata 18/72 m. *Colpito:* 23 (3d10 + 7) danni contundenti più 4 (1d8) danni da fuoco, il bersaglio viene spinto in linea retta fino a un massimo di 4,5 metri di distanza dal gigante, e subisce svantaggio al tiro per colpire successivo che effettua prima del termine del proprio turno successivo.