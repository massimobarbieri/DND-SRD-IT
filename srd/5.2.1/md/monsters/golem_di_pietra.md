---
id: golem_di_pietra
nome: Golem di pietra
tipo: Costrutto
dimensione: Grande
allineamento: senza allineamento

classe_armatura: 18
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 220
  formula: 21d10 + 105
velocita:
  camminata: 9 m

caratteristiche:
  forza:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6
  destrezza:
    punteggio: 9
    modificatore: -1
    tiro_salvezza: -1
  costituzione:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5

immunita_danni:
  - psichico
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
  scurovisione: 36 m

lingue:
  - capisce il Comune
  - altre due lingue
  - ma non le parla

grado_sfida:
  valore: 10
  punti_esperienza: 5900
  raw: 10 (PE 5.900; BC +4)

bonus_competenza: 4
---
## Tratti
### Forma immutabile
Il golem non può mutare forma.

### Resistenza alla magia
Il golem dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

## Azioni
### Multiattacco
Il golem effettua due attacchi, usando Schianto o Dardo vigoroso in qualsiasi combinazione.

### Schianto
*Tiro per colpire in mischia:* +10, portata 1,5 m. *Colpito:* 15 (2d8 + 6) danni contundenti più 9 (2d8) danni da forza.

### Dardo vigoroso
*Tiro per colpire a distanza:* +9, gittata 36 m. *Colpito:* 22 (4d10) danni da forza.

## Azioni bonus
### Lentezza (ricarica 5-6)
Il golem lancia l'incantesimo lentezza, senza bisogno di componenti e utilizzando Costituzione come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 17).