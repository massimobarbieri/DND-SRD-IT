---
id: cubo_gelatinoso
nome: Cubo gelatinoso
tipo: Melma
dimensione: Grande
allineamento: senza allineamento
classe_armatura: 6
iniziativa:
  valore: 6
  bonus: -4
punti_ferita:
  media: 63
  formula: 6d10 + 30
velocita:
  camminata: 5 m
caratteristiche:
  forza:
    punteggio: 14
    modificatore: 2
    tiro_salvezza: 2
  destrezza:
    punteggio: 3
    modificatore: -4
    tiro_salvezza: -4
  costituzione:
    punteggio: 20
    modificatore: 5
    tiro_salvezza: 5
  intelligenza:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
  saggezza:
    punteggio: 6
    modificatore: -2
    tiro_salvezza: -2
  carisma:
    punteggio: 1
    modificatore: -5
    tiro_salvezza: -5
immunita_danni:
- acido
immunita_condizione:
- accecato
- affascinato
- assordato
- indebolimento
- prono
- spaventato
sensi:
  percezione_passiva: 8
  vista_cieca: 18 m
lingue:
- nessuna
grado_sfida:
  valore: 2
  punti_esperienza: 450
  raw: 2 (PE 450; BC +2)
bonus_competenza: 2
---
## Tratti
### Cubo di melma
Il cubo occupa il suo intero spazio ed è trasparente. Le altre creature possono entrare in quello spazio, ma la creatura che lo fa è soggetta all'azione del cubo Avviluppare e subisce svantaggio al tiro salvezza. Le creature all'interno del cubo beneficiano di copertura totale, e il cubo può contenere una creatura di taglia Grande o fino a quattro creature di taglia Media o Piccola contemporaneamente. Con un'azione, una creatura entro 1,5 metri dal cubo può tirare fuori dal cubo una creatura o un oggetto superando una prova di Forza (Atletica) con CD 12, e chi esegue questa azione subisce 10 (3d6) danni da acido.

### Trasparente
Anche quando il cubo è in piena vista, una creatura deve superare una prova di Saggezza (Percezione) con CD 15 per avvistare il cubo se la creatura non ha visto il cubo muoversi o agire in un altro modo.

## Azioni
### Pseudopode
*Tiro per colpire in mischia:* +4, portata 1,5 m. *Colpito:* 12 (3d6 + 2) danni da acido.

### Avviluppare
Il cubo si muove fino alla sua velocità massima senza provocare attacchi di opportunità. Il cubo può muoversi nello spazio di creature di taglia Grande o inferiore se, al suo interno, ha spazio sufficiente a contenerle (vedi il tratto Cubo di melma).

*Tiro salvezza su Destrezza:* CD 12, tutte le creature nel cui spazio il cubo entra per la prima volta durante questo movimento.

*Fallimento:* 10 (3d6) danni da acido, e il bersaglio è avviluppato. Un bersaglio avviluppato soffoca, non può lanciare incantesimi con una componente Verbale, è trattenuto e subisce 10 (3d6) danni da acido all'inizio di ogni turno del cubo. Quando il cubo si muove, il bersaglio avviluppato si muove insieme a esso. Un bersaglio avviluppato può tentare di sfuggire usando un'azione per effettuare una prova di Forza (Atletica) con CD 12. Se la prova viene superata, il bersaglio sfugge ed entra nello spazio libero più vicino.

*Successo:* danni dimezzati, e il bersaglio si sposta in uno spazio libero entro 1,5 metri dal cubo. Se non c'è alcuno spazio libero, il bersaglio fallisce la prova.