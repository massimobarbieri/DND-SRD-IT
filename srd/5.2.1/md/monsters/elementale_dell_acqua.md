---
id: elementale_dell_acqua
nome: Elementale dell'acqua
tipo: Elementale
dimensione: Grande
allineamento: neutrale

classe_armatura: 14
iniziativa:
  valore: 12
  bonus: 2
punti_ferita:
  media: 114
  formula: 12d10 + 48
velocita:
  camminata: 9 m
  nuoto: 27 m

caratteristiche:
  forza:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  destrezza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  costituzione:
    punteggio: 18
    modificatore: 4
    tiro_salvezza: 4
  intelligenza:
    punteggio: 5
    modificatore: -3
    tiro_salvezza: -3
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 8
    modificatore: -1
    tiro_salvezza: -1

resistenze:
  - acido
  - fuoco

immunita_danni:
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
  percezione_passiva: 10
  scurovisione: 18 m

lingue:
  - Primordiale (Aquan)

grado_sfida:
  valore: 5
  punti_esperienza: 1800
  raw: 5 (PE 1.800; BC +3)

bonus_competenza: 3
---
## Tratti
### Congelamento
Se l'elementale subisce danni da freddo, la sua velocità è ridotta di 6 metri fino al termine del suo turno successivo.

### Forma d'acqua
L'elementale può entrare nello spazio di un nemico e fermarvisi. Può muoversi attraverso uno spazio stretto fino a 2,5 centimetri senza consumare movimento extra per farlo.

## Azioni
### Multiattacco
L'elementale effettua due attacchi Schianto.

### Schianto
*Tiro per colpire in mischia:* +7, portata 1,5 m. *Colpito:* 13 (2d8 + 4) danni contundenti. Se il bersaglio è una creatura di taglia Media o inferiore, cade a terra prono.

### Sommergere (ricarica 4-6)
*Tiro salvezza su Forza:* CD 15, ogni creatura nello spazio dell'elementale. *Fallimento:* 22 (4d8 + 4) danni contundenti. Se il bersaglio è una creatura di taglia Grande o inferiore, è afferrato (CD 14 per sfuggire). Finché la presa perdura, il bersaglio è trattenuto e soffoca (a meno che non sia in grado di respirare sott'acqua) e subisce 9 (2d8) danni contundenti all'inizio di ogni turno dell'elementale. Tramite Sommergere, l'elementale può afferrare una creatura di taglia Grande o un massimo di due creature di taglia Media o inferiore contemporaneamente. Con un'azione, una creatura entro 1,5 metri dall'elementale può tirare una creatura fuori da esso superando una prova di Forza (Atletica) con CD 14. *Successo:* danni dimezzati.