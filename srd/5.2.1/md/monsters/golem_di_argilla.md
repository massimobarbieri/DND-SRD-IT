---
id: golem_di_argilla
nome: Golem di argilla
tipo: Costrutto
dimensione: Grande
allineamento: senza allineamento
classe_armatura: 14
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 123
  formula: 13d10 + 52
velocita:
  camminata: 9 m
caratteristiche:
  forza:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
resistenze:
- contundente
- perforante
- tagliente
immunita_danni:
- acido
- psichico
- veleno
immunita_condizione:
- affascinato
- avvelenato
- indebolimento
- paralizzato
- pietrificato
- spaventato
sensi:
  percezione_passiva: 9
  scurovisione: 18 m
lingue:
- Comune più un'altra lingua
grado_sfida:
  valore: 9
  punti_esperienza: 5000
  raw: 9 (PE 5.000; BC +4)
bonus_competenza: 4
---
## Tratti
### Assorbimento dell'acido
Ogni volta che il golem riceve danni da acido, non subisce danni, recuperando un numero di punti ferita pari ai danni da acido a lui inflitti.

### Berserk
Ogni volta che il golem inizia il suo turno sanguinante, tira 1d6. Se esce 6, il golem entra in uno stato di berserk. A ogni suo turno, finché è in stato di berserk, il golem attacca la creatura più vicina che è in grado di vedere. Se nessuna creatura è abbastanza vicina per essere attaccata, il golem si scaglia contro un oggetto. Una volta che il golem entra in stato di berserk, rimane in questo stato finché non viene distrutto o non è più sanguinante.

### Forma immutabile
Il golem non può mutare forma.

### Resistenza alla magia
Il golem dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

## Azioni
### Multiattacco
Il golem effettua due attacchi Schianto, o effettua tre attacchi Schianto se ha usato Fretta nello stesso turno.

### Schianto
*Tiro per colpire in mischia:* +9, portata 1,5 m. *Colpito:* 10 (1d10 + 5) danni contundenti più 6 (1d12) danni da acido, e i punti ferita massimi del bersaglio sono ridotti di un ammontare pari ai danni da acido subiti.

## Azioni bonus
### Fretta (ricarica 5-6)
Il golem effettua le azioni di Disimpegno e Scatto.