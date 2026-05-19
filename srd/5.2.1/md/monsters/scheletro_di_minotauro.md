---
id: scheletro_di_minotauro
nome: Scheletro di minotauro
gruppo: Scheletri
tipo: Non morto
dimensione: Grande
allineamento: legale malvagio
classe_armatura: 12
iniziativa:
  valore: 10
  bonus: 0
punti_ferita:
  media: 45
  formula: 6d10 + 12
velocita:
  camminata: 12 m
caratteristiche:
  forza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
immunita_danni:
- veleno
immunita_condizione:
- avvelenato
- indebolimento
vulnerabilita:
- contundente
sensi:
  percezione_passiva: 9
  scurovisione: 18 m
lingue:
- capisce l'Abissale ma non lo parla
grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)
bonus_competenza: 2
---
## Azioni

### Schianto
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 15 (2d10 + 4) danni contundenti.

### Trafiggere
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 11 (2d6 + 4) danni perforanti. Se il bersaglio è una creatura di taglia Grande o inferiore e lo scheletro si è mosso di 6 metri o più in linea retta verso di esso subito prima del colpo, il bersaglio subisce 9 (2d8) danni perforanti extra e cade a terra prono.
