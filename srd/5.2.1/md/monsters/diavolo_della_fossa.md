---
id: diavolo_della_fossa
nome: Diavolo della fossa
tipo: Immondo
sottotipo: diavolo
dimensione: Grande
allineamento: legale malvagio

classe_armatura: 21
iniziativa:
  valore: 24
  bonus: 14
punti_ferita:
  media: 337
  formula: 27d10 + 189
velocita:
  camminata: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 26
    modificatore: 8
    tiro_salvezza: 8
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 8
  costituzione:
    punteggio: 24
    modificatore: 7
    tiro_salvezza: 7
  intelligenza:
    punteggio: 22
    modificatore: 6
    tiro_salvezza: 6
  saggezza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 10
  carisma:
    punteggio: 24
    modificatore: 7
    tiro_salvezza: 7

abilita:
  percezione: 10
  persuasione: 19

resistenze:
  - freddo

immunita_danni:
  - fuoco
  - veleno

immunita_condizioni:
  - avvelenato

sensi:
  percezione_passiva: 20
  vista_pura: 36 m

lingue:
  - Infernale
  - telepatia 36 m

grado_sfida:
  valore: 20
  punti_esperienza: 25000
  raw: 20 (PE 25.000; BC +6)

bonus_competenza: 6
---
## Tratti
### Aura di paura
Il diavolo della fossa irradia un'aura in un'emanazione di 6 metri fintanto che non è incapacitato.

*Tiro salvezza su Saggezza:* CD 21, qualsiasi nemico che inizi il suo turno all'interno dell'aura.

*Fallimento:* il bersaglio è spaventato fino all'inizio del proprio turno successivo.

*Successo:* il bersaglio è immune all'aura di questo diavolo della fossa per 24 ore.

### Resistenza alla magia
Il diavolo della fossa dispone di vantaggio ai tiri salvezza contro incantesimi e altri effetti magici.

### Resistenza leggendaria (4/giorno)
Se il diavolo della fossa fallisce un tiro salvezza, può scegliere di superarlo comunque.

### Ristoro diabolico
Se il diavolo della fossa muore al di fuori dei Nove Inferi, il suo corpo si dissolve in fumo sulfureo e ne acquisisce uno nuovo all'istante, tornando in vita con tutti i suoi punti ferita da qualche parte nei Nove Inferi.

## Azioni
### Multiattacco
Il diavolo della fossa effettua un attacco Morso, due attacchi Artiglio diabolico e un attacco Mazza fiammeggiante.

### Artiglio diabolico
*Tiro per colpire in mischia:* +14, portata 3 m. *Colpito:* 26 (4d8 + 8) danni necrotici.

### Mazza fiammeggiante
*Tiro per colpire in mischia:* +14, portata 3 m. *Colpito:* 22 (4d6 + 8) danni da forza più 21 (6d6) danni da fuoco.

### Morso
*Tiro per colpire in mischia:* +14, portata 3 m. *Colpito:* 18 (3d6 + 8) danni perforanti. Se il bersaglio è una creatura, deve effettuare il seguente tiro salvezza.

*Tiro salvezza su Costituzione:* CD 21.

*Fallimento:* il bersaglio viene avvelenato. Finché è avvelenato, il bersaglio non può recuperare punti ferita e subisce 21 (6d6) danni da veleno all'inizio di ogni suo turno; il bersaglio ripete il tiro salvezza al termine di ogni suo turno e, se lo supera, l'effetto svanisce. Dopo 1 minuto, la prova viene superata automaticamente.

### Incantesimi del fuoco infernale (ricarica 4-6)
Il diavolo della fossa lancia palla di fuoco (di 5º livello) due volte, senza bisogno di componenti materiali e utilizzando Carisma come caratteristica da incantatore (CD del tiro salvezza sull'incantesimo 21). Può sostituire un incantesimo palla di fuoco con blocca mostri (di 7º livello) o con muro di fuoco.