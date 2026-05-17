---
id: goblin_guerriero
nome: Goblin guerriero
gruppo: Goblin
tipo: Folletto
sottotipo: goblinoide
dimensione: Piccolo
allineamento: caotico neutrale

classe_armatura: 15
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 10
  formula: 3d6
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
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
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1

abilita:
  furtivita: 6

equipaggiamento:
  - arco corto
  - armatura di cuoio
  - scimitarra
  - scudo

sensi:
  percezione_passiva: 9
  scurovisione: 18 m

lingue:
  - Comune
  - Goblin

grado_sfida:
  valore: 0.25
  punti_esperienza: 50
  raw: 1/4 (PE 50; BC +2)

bonus_competenza: 2
---
## Azioni
### Scimitarra
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 5 (1d6 + 2) danni taglienti, più 2 (1d4) danni taglienti se il tiro per colpire è stato effettuato con vantaggio.

### Arco corto
*Tiro per colpire a distanza:* +4, gittata 24/96 m. *Colpito:* 5 (1d6 + 2) danni perforanti, più 2 (1d4) danni perforanti se il tiro per colpire è stato effettuato con vantaggio.

## Azioni bonus
### Fuga agile
Il goblin effettua l'azione di Disimpegno o Nascondersi.