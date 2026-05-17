---
id: golem_di_carne
nome: Golem di carne
tipo: Costrutto
dimensione: Medio
allineamento: neutrale

classe_armatura: 9
iniziativa:
  valore: 9
  bonus: -1
punti_ferita:
  media: 127
  formula: 15d8 + 60
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3

immunita_danni:
  - fulmine
  - veleno

immunita_condizioni:
  - affascinato
  - avvelenato
  - indebolimento
  - paralizzato
  - pietrificato
  - spaventato

sensi:
  percezione_passiva: 10
  scurovisione: 18 m

lingue:
  - Capisce il Comune e un'altra lingua ma non le parla

grado_sfida:
  valore: 5
  punti_esperienza: 1800
  raw: 5 (PE 1.800; BC +3)

bonus_competenza: 3
---
## Tratti
### Assorbimento del fulmine
Ogni volta che il golem subisce danni da fulmine, recupera un numero di punti ferita pari ai danni da fulmine inflitti.

### Avversione al fuoco
Se il golem subisce danni da fuoco, subisce svantaggio ai tiri per colpire e alle prove di caratteristica fino al termine del proprio turno successivo.

### Berserk
Ogni volta che il golem inizia il suo turno sanguinante, tira 1d6. Se esce 6, il golem entra in uno stato di berserk. A ogni suo turno, finché è in stato di berserk, il golem attacca la creatura più vicina che è in grado di vedere. Se nessuna creatura è abbastanza vicina per essere attaccata, il golem si scaglia contro un oggetto. Una volta che il golem entra in stato di berserk, rimane in questo stato finché non viene distrutto o non è più sanguinante. Il creatore del golem, se si trova entro 18 metri dal golem in stato di berserk, può cercare di calmarlo eseguendo un'azione per effettuare una prova di Carisma (Persuasione) con CD 15. Il golem deve essere in grado di udire il suo creatore. Se la prova ha successo, il golem esce dallo stato di berserk fino all'inizio del proprio turno successivo; a quel punto, se è ancora sanguinante, riprende a effettuare il tiro del tratto Berserk.

### Forma immutabile
Il golem non può mutare forma.

### Resistenza alla magia
Il golem dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

## Azioni
### Multiattacco
Il golem effettua due attacchi Schianto.

### Schianto
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 13 (2d8 + 4) danni contundenti più 4 (1d8) danni da fulmine.