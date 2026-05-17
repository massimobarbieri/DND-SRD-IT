---
id: chimera
nome: Chimera
tipo: Mostruosità
dimensione: Grande
allineamento: caotico malvagio

classe_armatura: 14

iniziativa:
  valore: 10
  bonus: 0

punti_ferita:
  medi: 114
  formula: 12d10 + 48

velocita:
  camminata: 9 m
  volo: 18 m

caratteristiche:
  forza:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 11
    modificatore: 0
    tiro_salvezza: 0
  costituzione:
    punteggio: 19
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  carisma:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0

abilita:
  percezione: 8

sensi:
  percezione_passiva: 18
  scurovisione: 18 m

lingue:
  - Capisce il Draconico ma non lo parla

grado_sfida:
  valore: 6
  punti_esperienza: 2.300
  raw: 6 (PE 2.300; BC +3)

bonus_competenza: 3
---
## Azioni
### Multiattacco
La chimera effettua un attacco Sfondamento, un attacco Morso e un attacco Artiglio. Può sostituire l'attacco Artiglio con un utilizzo di Soffio di fuoco, se disponibile.

### Artiglio
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 7 (1d6 + 4) danni taglienti

### Morso
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 11 (2d6 + 4) danni perforanti, o 18 (4d6 + 4) danni perforanti se la chimera dispone di vantaggio al tiro per colpire.

### Sfondamento
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 10 (1d12 + 4) danni contundenti. Se il bersaglio è una creatura di taglia Media o inferiore, cade a terra prono.

### Soffio di fuoco (ricarica 5-6)
*Tiro salvezza su Destrezza:* CD 15, tutte le creature in un cono di 4,5 metri. *Fallimento:* 31 (7d8) danni da fuoco. *Successo:* danni dimezzati.