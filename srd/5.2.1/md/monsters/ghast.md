---
id: ghast
nome: Ghast
tipo: Non morto
dimensione: Medio
allineamento: caotico malvagio

classe_armatura: 13
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 36
  formula: 8d8
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  destrezza:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 3
  costituzione:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 2
  carisma:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1

resistenze:
  - necrotico

immunita_danni:
  - veleno

immunita_condizioni:
  - affascinato
  - avvelenato
  - indebolimento

sensi:
  percezione_passiva: 10
  scurovisione: 18 m

lingue:
  - Comune

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Tratti
### Fetore
*Tiro salvezza su Costituzione:* CD 10, ogni creatura che inizi il suo turno in un'emanazione di 1,5 metri di cui il ghast è il punto di origine. *Fallimento:* il bersaglio è avvelenato fino all'inizio del proprio turno successivo. *Successo:* il bersaglio è immune a Fetore di questo ghast per 24 ore.

## Azioni
### Artiglio
*Tiro per colpire in mischia:* +5, portata 1,5 m. *Colpito:* 10 (2d6 + 3) danni taglienti. Se il bersaglio è una creatura diversa da un non morto, subisce il seguente effetto.

*Tiro salvezza su Costituzione:* CD 10. *Fallimento:* il bersaglio è paralizzato fino al termine del proprio turno successivo.

### Morso
*Tiro per colpire in mischia:* +5, portata 1,5 m. *Colpito:* 7 (1d8 + 3) danni perforanti più 9 (2d8) danni necrotici.