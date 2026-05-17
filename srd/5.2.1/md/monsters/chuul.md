---
id: chuul
nome: Chuul
tipo: Aberrazione
dimensione: Grande
allineamento: caotico malvagio

classe_armatura: 16

iniziativa:
  valore: 10
  bonus: 0

punti_ferita:
  medi: 76
  formula: 9d10 + 27

velocita:
  camminata: 9 m
  nuoto: 9 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  intelligenza:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3

abilita:
  percezione: 4

immunita_danni:
  - veleno
immunita_condizioni:
  - avvelenato  

sensi:
  percezione_passiva: 14
  scurovisione: 18 m

lingue:
  - Capisce il Gergo delle Profondità ma non lo parla  

grado_sfida:
  valore: 4
  punti_esperienza: 1.100
  raw: 4 (PE 1.100; BC +2)

bonus_competenza: 2
---
## Tratti
### Anfibio
Il chuul può respirare in aria e in acqua.

### Percezione della magia
Il chuul percepisce la magia entro 36 metri da sé. Sotto ogni altro aspetto, questo tratto funziona come l'incantesimo individuazione del magico, ma di per sé non è magico.

## Azioni
### Multiattacco
Il chuul effettua due attacchi Tenaglia e utilizza Tentacoli paralizzanti.

### Tenaglia
*Tiro per colpire in mischia:* +6, portata 3 m. *Colpito:* 9 (1d10 + 4) danni contundenti. Se il bersaglio è una creatura di taglia Grande o inferiore, è afferrato (CD 14 per sfuggire) da una delle due tenaglie.

### Tentacoli paralizzanti
*Tiro salvezza su Costituzione:* CD 13, una creatura afferrata dal chuul. *Fallimento:* il bersaglio è avvelenato e ripete il tiro salvezza alla fine del suo turno successivo e, se lo supera, l'effetto svanisce. Dopo 1 minuto, il tiro viene superato automaticamente. Finché è avvelenato, il bersaglio è paralizzato.