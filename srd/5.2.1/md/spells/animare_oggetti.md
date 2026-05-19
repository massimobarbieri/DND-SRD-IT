---
id: animare_oggetti
nome: Animare oggetti
tipo: incantesimo
livello: 5
scuola: Trasmutazione
classi: 
  - bardo
  - mago
  - stregone
tempo_lancio: azione
gittata: 36 metri
componenti: V, S
durata: concentrazione, fino a 1 minuto
pagine_sorgente: 124-125
creatura_evocata: 
  id: oggetto_animato
  fonte: mostri
  risoluzione: lookup_by_id

creature_evocate_inline: 
  - id: null
    nome: Oggetto animato
    tipo_blocco: creatura_evocata
    statblock: 
      tipo: Costrutto Enorme o inferiore
      dimensione: null
      allineamento: senza allineamento
      classe_armatura: 15
      punti_ferita: 10 (taglia Media o inferiore), 20 (taglia Grande), 40 (taglia Enorme)
      velocita: 9 m
      caratteristiche: 
        forza: 
          valore: 16
          modificatore: +3

        destrezza: 
          valore: 10
          modificatore: +0

        costituzione: 
          valore: 10
          modificatore: +0

        intelligenza: 
          valore: 3
          modificatore: "-4"

        saggezza: 
          valore: 3
          modificatore: "-4"

        carisma: 
          valore: 1
          modificatore: "-5"


      tiri_salvezza_base: 
        forza: +3
        destrezza: +0
        costituzione: +0
        intelligenza: "-4"
        saggezza: "-4"
        carisma: "-5"

      immunita_danni: psichico, veleno
      immunita_condizioni: affascinato, avvelenato, indebolimento, paralizzato, spaventato
      sensi: "Percezione passiva 6; vista cieca: 9 m"
      lingue: comprende le lingue del personaggio
      grado_sfida: null
      bonus_competenza: variabile
      azioni: 
        - nome: Schianto
          descrizione: "---"
      sezioni: []
---
Gli oggetti si animano su ordine dell'incantatore. L'incantatore sceglie un numero di oggetti non magici entro gittata che non siano indossati o trasportati, fissati su una superficie o di dimensioni Mastodontiche. Il numero massimo di oggetti è uguale al suo modificatore di caratteristica da incantatore; per questo numero, un bersaglio di taglia Media o inferiore conta come un oggetto, un bersaglio di taglia Grande conta come due e un bersaglio Enorme conta come tre.

Ogni bersaglio si anima e diventa un costrutto provvisto di gambe che utilizza la scheda delle statistiche dell'oggetto animato; questa creatura è sotto il controllo dell'incantatore fino al termine dell'incantesimo o finché non viene ridotta a 0 punti ferita. Ogni creatura creata con questo incantesimo diventa un alleato per l'incantatore e i suoi alleati. In combattimento, la creatura ha lo stesso punteggio di iniziativa dell'incantatore, ma inizia il turno immediatamente dopo il suo.

Fino al termine dell'incantesimo, come azione bonus, l'incantatore può comandare mentalmente qualsiasi creatura creata con questo incantesimo, a patto che si trovi entro 150 metri da sé (se controlla varie creature, l'incantatore può comandarne più di una allo stesso momento, impartendo lo stesso comando a ciascuna di loro). Se invece non impartisce alcun comando, la creatura effettua l'azione Schivata e si sposta solo per evitare di subire danni. Quando la creatura scende a 0 punti ferita, riassume la sua forma di oggetto, a cui vengono trasferiti eventuali danni rimanenti.

### Scaling

Utilizzo di uno slot incantesimo di livello superiore. I danni da Schianto della creatura aumentano di 1d4 (taglia Media o inferiore), 1d6 (taglia Grande) o 1d12 (taglia Enorme) per ogni slot di livello superiore al 5º.
