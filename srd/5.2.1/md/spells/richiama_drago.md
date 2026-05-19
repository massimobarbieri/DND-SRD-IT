---
id: richiama_drago
nome: Richiama drago
tipo: incantesimo
livello: 5
scuola: Evocazione
classi: 
  - mago
tempo_lancio: azione
gittata: 18 metri
componenti: V, S, M (un oggetto su cui è incisa l'immagine di un drago, del valore di 500 mo o più)
durata: concentrazione, fino a 1 ora
pagine_sorgente: 180-181
creatura_evocata: 
  id: spirito_draconico
  fonte: mostri
  risoluzione: lookup_by_id

creature_evocate_inline: 
  - id: null
    nome: Spirito draconico
    tipo_blocco: creatura_evocata
    statblock: 
      tipo: Drago
      dimensione: null
      allineamento: Neutrale
      classe_armatura: 14 + livello_incantesimo
      punti_ferita: "50 + 10 per livello sopra il 5°"
      velocita: 9 m, volo 18 m, nuoto 9 m
      caratteristiche: 
        forza: 
          valore: 19
          modificatore: +4

        destrezza: 
          valore: 14
          modificatore: +2

        costituzione: 
          valore: 17
          modificatore: +3

        intelligenza: 
          valore: 10
          modificatore: +0

        saggezza: 
          valore: 14
          modificatore: +2

        carisma: 
          valore: 14
          modificatore: +2


      tiri_salvezza_base: 
        forza: null
        destrezza: null
        costituzione: null
        intelligenza: null
        saggezza: null
        carisma: null

      immunita_danni: null
      immunita_condizioni: ""
      sensi: ""
      lingue: draconico, comprende le lingue parlate dal personaggio GS nessuno (PE 0; BC pari al bonus di competenza del personaggio)
      grado_sfida: null
      bonus_competenza: null
      azioni: 
        - nome: Multiattacco
          descrizione: Lo spirito effettua un numero di attacchi Squarcio pari alla metà del livello dell'incantesimo (arrotondando per difetto) e usa Soffio.
        - nome: Squarcio
          descrizione: ""
        - nome: Soffio
          descrizione: "---"
      sezioni: 
        - titolo: Tratti
          blocchi: 
            - nome: Resistenze condivise
              descrizione: Quando il personaggio evoca lo spirito, sceglie una delle sue resistenze. Così facendo, ottiene resistenza al tipo di danno scelto fino al termine dell'incantesimo.
---
L'incantatore invoca uno spirito di drago, che si manifesta in uno spazio libero entro gittata che egli sia in grado di vedere e utilizza la scheda delle statistiche dello spirito draconico. La creatura scompare quando scende a 0 punti ferita o quando l'incantesimo termina ed è un alleato per il personaggio e i suoi alleati. In combattimento, la creatura ha lo stesso punteggio di iniziativa dell'incantatore, ma inizia il turno immediatamente dopo il suo, obbedendo ai suoi comandi verbali (nessuna azione richiesta da parte dell'incantatore). Se l'incantatore non pronuncia comandi verbali, la creatura compie l'azione di Schivata e usa il suo movimento per sottrarsi al pericolo.

### Scaling

**Utilizzo di uno slot incantesimo di livello superiore**
Usa il livello dello slot incantesimo relativo al livello dell'incantesimo nella scheda delle statistiche.
