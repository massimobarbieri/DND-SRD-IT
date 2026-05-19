---
id: mummia
nome: Mummia
gruppo: Mummie
tipo: Non morto
dimensione: Medio o Piccolo
allineamento: legale malvagio
classe_armatura: 11
iniziativa:
  valore: 9
  bonus: -1
punti_ferita:
  media: 58
  formula: 9d8 + 18
velocita:
  camminata: 6 m
caratteristiche:
  forza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  destrezza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 3
  carisma:
    punteggio: 12
    modificatore: 1
    tiro_salvezza: 1
immunita_danni:
- necrotico
- veleno
immunita_condizione:
- affascinato
- avvelenato
- indebolimento
- paralizzato
- spaventato
vulnerabilita:
- fuoco
sensi:
  percezione_passiva: 11
  scurovisione: 18 m
lingue:
- Comune più altre due lingue
grado_sfida:
  valore: 3
  punti_esperienza: 700
  raw: 3 (PE 700; BC +2)
bonus_competenza: 2
---
## Azioni

### Multiattacco
La mummia effettua due attacchi Pugno di putrefazione e usa Sguardo funesto.

### Pugno di putrefazione
*Tiro per colpire in mischia:* +5, portata 1,5 m *Colpito:* 8 (1d10 + 3) danni contundenti più 10 (3d6) danni necrotici. Se il bersaglio è una creatura, viene maledetto. Finché è maledetto, il bersaglio non può recuperare punti ferita, i suoi punti ferita massimi non tornano alla normalità al termine di un riposo lungo e sono ridotti di 10 (3d6) ogni 24 ore trascorse. Una creatura muore e si disintegra in polvere se viene ridotta a 0 punti ferita da questo attacco.

### Sguardo funesto
*Tiro salvezza su Saggezza:* CD 11, una creatura che la mummia è in grado di vedere entro 18 metri. *Fallimento:* il bersaglio è spaventato fino al termine del turno successivo della mummia. *Successo:* il bersaglio è immune allo Sguardo funesto di questa mummia per 24 ore.
