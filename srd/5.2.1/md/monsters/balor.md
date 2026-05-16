---
id: balor
nome: Balor
tipo: Immondo
sottotipo: demone
dimensione: Enorme
allineamento: caotico malvagio

classe_armatura:
  valore: 19

iniziativa:
  valore: 24
  bonus: 14

punti_ferita:
  media: 287
  formula: 23d12 + 138

velocita:
  camminata: 12 m
  volo: 24 m

caratteristiche:
  forza:
    punteggio: 26
    modificatore: 8
    tiro_salvezza: 8
  destrezza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 12
  intelligenza:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  saggezza:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 9
  carisma:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6

abilita:
  percezione: 9

resistenze:** freddo, fulmine  
immunita_danni:** fuoco, veleno  
immunita_condizioni:
  - affascinato
  - avvelenato
  - spaventato 

sensi:
  percezione_passiva: 19
  vista_pura: 36 m  

lingue:
  - Abissale
  - telepatia 36 m  

grado_sfida:
  valore: 19
  punti_esperienza: 22.000
  raw: 19 (PE 22.000; BC +6)

bonus_competenza: 6
---
## Tratti
### Aura di fuoco
Al termine di ogni turno del balor, tutte le creature in un'emanazione di 1,5 metri di cui il balor è il punto di origine subiscono 13 (3d8) danni da fuoco.

### Resistenza alla magia
Il balor dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

### Resistenza leggendaria (3/giorno)
Se il balor fallisce un tiro salvezza, può scegliere di superarlo comunque.

### Spasmi di morte
Quando il balor muore, esplode. *Tiro salvezza su Destrezza:* CD 20, tutte le creature in u n'emanazione di 9 metri di cui il balor è il punto di origine. *Fallimento:* 31 (9d6) danni da fuoco più 31 (9d6) danni da forza. *Successo:* danni dimezzati. Fallimento o successo: se il balor muore al di fuori dell'Abisso, acquisisce un corpo nuovo all'istante, tornando in vita con tutti i suoi punti ferita da qualche parte nell'Abisso.

## Azioni
### Multiattacco
Il balor effettua un attacco Frusta fiammeggiante e un attacco Lama fulminante.

### Frusta fiammeggiante
*Tiro per colpire in mischia:* +14, portata 9 m. *Colpito:* 18 (3d6 + 8) danni da forza più 17 (5d6) danni da fuoco. Se il bersaglio è una creatura di taglia Enorme o inferiore, il balor trascina il bersaglio in linea retta verso di sé fino a 7,5 metri, e il bersaglio cade a terra prono.

### Lama fulminante
*Tiro per colpire in mischia:* +14, portata 3 m. *Colpito:* 21 (3d8 + 8) danni da forza più 22 (4d10) danni da fulmine, e il bersaglio non può effettuare reazioni fino all'inizio del turno successivo del balor.

## Azioni bonus
### Teletrasporto
Il balor teletrasporta se stesso (o un demone consenziente entro 3 metri da sé) fino a 18 metri in uno spazio libero che il balor è in grado di vedere.