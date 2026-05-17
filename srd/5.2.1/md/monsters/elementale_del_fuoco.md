---
id: elementale_del_fuoco
nome: Elementale del fuoco
tipo: Elementale
dimensione: Grande
allineamento: neutrale

classe_armatura: 13
iniziativa:
  valore: 13
  bonus: 3
punti_ferita:
  media: 93
  formula: 11d10 + 33
velocita:
  camminata: 15 m

caratteristiche:
  forza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  destrezza:
    punteggio: 17
    modificatore: 3
    tiro_salvezza: 3
  costituzione:
    punteggio: 16
    modificatore: 3
    tiro_salvezza: 3
  intelligenza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  saggezza:
    punteggio: 10
    modificatore: 0
    tiro_salvezza: 0
  carisma:
    punteggio: 7
    modificatore: -2
    tiro_salvezza: -2

resistenze:
  - contundente
  - perforante
  - tagliente

immunita_danni:
  - fuoco
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
  - Primordiale (Ignan)

grado_sfida:
  valore: 5
  punti_esperienza: 1800
  raw: 5 (PE 1.800; BC +3)

bonus_competenza: 3
---
## Tratti
### Aura di fuoco
Alla fine di ogni turno dell'elementale, tutte le creature in un'emanazione di 3 metri di cui l'elementale è il punto di origine subiscono 5 (1d10) danni da fuoco. Le creature e gli oggetti infiammabili che si trovano nell'emanazione iniziano a bruciare.

### Forma di fuoco
L'elementale può muoversi attraverso uno spazio stretto fino a 2,5 centimetri senza consumare movimento extra per farlo, e può entrare nello spazio di una creatura e fermarvisi. La prima volta che entra nello spazio di una creatura in un turno, quella creatura subisce 5 (1d10) danni da fuoco.

### Illuminazione
L'elementale emana luce intensa in un raggio di 9 metri e luce fioca per altri 9 metri.

### Suscettibilità all'acqua
Per ogni 1,5 metri di cui l'elementale si muove nell'acqua o per ogni 4 litri d'acqua versatigli addosso, l'elementale subisce 3 (1d6) danni da freddo.

## Azioni
### Multiattacco
L'elementale effettua due attacchi Bruciatura.

### Bruciatura
*Tiro per colpire in mischia:* +6, portata 1,5 m. *Colpito:* 10 (2d6 + 3) danni da fuoco. Se il bersaglio è una creatura o un oggetto infiammabile, inizia a bruciare.