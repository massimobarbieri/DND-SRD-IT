---
id: fuoco_fatuo
nome: Fuoco fatuo
tipo: Non morto
dimensione: Minuscolo
allineamento: caotico malvagio

classe_armatura: 19
iniziativa:
  valore: 19
  bonus: 9
punti_ferita:
  media: 27
  formula: 11d4
velocita:
  camminata: 1,5 m
  volo: 15 m
  dettagli_volo: fluttuare

caratteristiche:
  forza:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
  destrezza:
    punteggio: 28
    modificatore: 9
    tiro_salvezza: 9
  costituzione:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  intelligenza:
    punteggio: 13
    modificatore: 1
    tiro_salvezza: 1
  saggezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  carisma:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0

resistenze:
  - acido
  - contundente
  - freddo
  - fuoco
  - necrotico
  - perforante
  - tagliente

immunita_danni:
  - fulmine
  - veleno

immunita_condizioni:
  - afferrato
  - avvelenato
  - indebolimento
  - paralizzato
  - pietrificato
  - privo di sensi
  - prono
  - trattenuto

sensi:
  percezione_passiva: 12
  scurovisione: 36 m

lingue:
  - Comune
  - un'altra lingua

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Tratti
### Effimero
Il fuoco fatuo non può indossare o trasportare niente.

### Illuminazione
Il fuoco fatuo emana luce intensa in un raggio di 6 metri e luce fioca per altri 6 metri.

### Movimento incorporeo
Il fuoco fatuo può muoversi attraverso altre creature e oggetti come se fossero terreno difficile. Se termina il suo turno all'interno di un oggetto, subisce 5 (1d10) danni da forza.

## Azioni
### Folgore
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 11 (2d8 + 2) danni da fulmine.

## Azioni bonus
### Assorbire vita
*Tiro salvezza su Costituzione:* CD 10, una creatura vivente che il fuoco fatuo è in grado di vedere entro 1,5 metri con 0 punti ferita. *Fallimento:* il bersaglio muore, e il fuoco fatuo recupera 10 (3d6) punti ferita.

### Svanire
Il fuoco fatuo e la luce che emana sono invisibili finché la sua concentrazione non termina su tale effetto; l'effetto cessa immediatamente dopo che il fuoco fatuo effettua un tiro per colpire o usa Assorbire vita.