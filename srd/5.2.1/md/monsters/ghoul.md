---
id: ghoul
nome: Ghoul
tipo: Non morto
dimensione: Medio
allineamento: caotico malvagio
classe_armatura: 12
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 22
  formula: 5d8
velocita:
  camminata: 9 m
caratteristiche:
  forza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  destrezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 7
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
immunita_danni:
- veleno
immunita_condizione:
- affascinato
- avvelenato
- indebolimento
sensi:
  percezione_passiva: 10
  scurovisione: 18 m
lingue:
- Comune
grado_sfida:
  valore: 1
  punti_esperienza: 200
  raw: 1 (PE 200; BC +2)
bonus_competenza: 2
---
## Azioni
### Multiattacco
Il ghoul effettua due attacchi Morso.

### Artiglio
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 4 (1d4 + 2) danni taglienti. Se il bersaglio è una creatura diversa da un non morto o da un elfo, subisce il seguente effetto.

*Tiro salvezza su Costituzione:* CD 10. *Fallimento:* il bersaglio è paralizzato fino al termine del proprio turno successivo.

### Morso
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 5 (1d6 + 2) danni perforanti più 3 (1d6) danni necrotici.