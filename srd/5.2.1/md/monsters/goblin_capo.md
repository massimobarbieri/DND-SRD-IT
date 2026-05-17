---
id: goblin_capo
nome: Goblin capo
gruppo: Goblin
tipo: Folletto
sottotipo: goblinoide
dimensione: Piccolo
allineamento: caotico neutrale

classe_armatura: 17
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 21
  formula: 6d6
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  destrezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  carisma:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0

abilita:
  furtivita: 6

equipaggiamento:
  - arco corto
  - giaco di maglia
  - scimitarra
  - scudo

sensi:
  percezione_passiva: 9
  scurovisione: 18 m

lingue:
  - Comune
  - Goblin

grado_sfida:
  valore: 1
  punti_esperienza: 200
  raw: 1 (PE 200; BC +2)

bonus_competenza: 2
---
## Azioni
### Multiattacco
Il goblin effettua due attacchi, utilizzando Scimitarra o Arco corto in qualsiasi combinazione.

### Scimitarra
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 5 (1d6 + 2) danni taglienti, più 2 (1d4) danni taglienti se il tiro per colpire è stato effettuato con vantaggio.

### Arco corto
*Tiro per colpire a distanza:* +4, gittata 24/96 m. *Colpito:* 5 (1d6 + 2) danni perforanti, più 2 (1d4) danni perforanti se il tiro per colpire è stato effettuato con vantaggio.

## Azioni bonus
### Fuga agile
Il goblin effettua l'azione di Disimpegno o Nascondersi.

## Reazioni
### Sviare attacco
**Attivazione:** Una creatura che il goblin è in grado di vedere effettua un tiro per colpire contro di lui.

**Esito:** Il goblin sceglie un alleato di taglia Piccola o Media entro 1,5 metri da sé. Il goblin e l'alleato si scambiano di posto, facendo sì che quest'ultimo diventi il bersaglio dell'attacco al suo posto.