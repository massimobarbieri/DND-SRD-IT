---
id: centauro_combattente
nome: Centauro combattente
gruppo: Centauro
tipo: Folletto
dimensione: Grande
allineamento: neutrale buono

classe_armatura: 16

iniziativa:
  valore: 12
  bonus: 2

punti_ferita:
  medi: 45
  formula: 6d10 + 12

velocita:
  camminata: 15 m

caratteristiche:
  forza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  saggezza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  carisma:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0

abilita:
  atletica: 6
  percezione: 3

equipaggiamento:
  - arco lungo
  - corazza di piastre
  - picca  

sensi:
  percezione_passiva: 13

lingue:
  - Elfico
  - Silvano

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Azioni
### Multiattacco
Il centauro effettua due attacchi, utilizzando Picca o Arco lungo in qualsiasi combinazione.

### Picca
*Tiro per colpire in mischia:* +6, portata 3 m. *Colpito:* 9 (1d10 + 4) danni perforanti.

### Arco lungo
*Tiro per colpire a distanza:* +4, gittata 45/180 m. *Colpito:* 6 (1d8 + 2) danni perforanti.

## Azioni bonus
### Carica travolgente (Ricarica 5-6)
Il centauro si muove fino alla sua velocità massima senza provocare attacchi di opportunità e può attraversare gli spazi di qualsiasi creatura di taglia Media o inferiore. Ogni creatura il cui spazio viene invaso dal centauro viene bersagliata una volta dal seguente effetto. *Tiro salvezza su Forza:* CD 14 *Fallimento:* 7 (1d6 + 4) danni contundenti, e il bersaglio è prono.