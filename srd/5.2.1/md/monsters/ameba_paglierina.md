---
id: ameba_paglierina
nome: Ameba Paglierina
tipo: Melma
dimensione: Grande
allineamento: senza allineamento

classe_armatura:
  valore: 8
iniziativa: 
  valore: 8
  bonus: -2

punti_ferita: 
  media: 52
  formula: 7d10 + 14

velocita:
  camminata: 6 m
  scalata: 6 m

caratteristiche:
  forza:
    punteggio: 15
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  costituzione:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  intelligenza:
    punteggio: 2
    modificatore: -4
    tiro_salvezza: -4
  saggezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5

resistenze: 
  - acido  
immunita_danni:
  - fulmine
  - tagliente 
immunita_condizione:
  - affascinato
  - afferrato
  - assordato
  - indebolimento
  - prono
  - spaventato
  - trattenuto
sensi:
  percezione_passiva: 8
  vista_cieca: 18 m 

lingue:
  - Nessuna

grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)

bonus_competenza: 2
---
## Tratti
### Amorfo
L'ameba può muoversi attraverso uno spazio stretto fino a 2,5 centimetri senza consumare movimento extra per farlo.

### Movimenti del ragno
L'ameba può scalare le superfici difficili, compresi i soffitti, senza effettuare una prova di caratteristica.

## Azioni
### Pseudopode
*Tiro per colpire in mischia:* +4, portata 1,5 m *Colpito:* 12 (3d6 + 2) danni da acido.

## Reazioni
### Scindersi
*Attivazione:* l'ameba, finché è di taglia Grande o Media e ha 10 punti ferita o più, diventa sanguinante o è soggetta a danni da fulmine o taglienti. *Esito:* l'ameba paglierina si scinde in due nuove amebe paglierine. Ogni nuova ameba è inferiore di una taglia rispetto all'ameba originale, e agisce di propria iniziativa. I punti ferita dell'ameba originale sono divisi equamente tra le due nuove amebe (arrotondati per difetto).
