---
id: trova_cavalcatura
nome: Trova cavalcatura
tipo: incantesimo
livello: 2
scuola: Evocazione
classi: 
  - paladino
tempo_lancio: azione
gittata: 9 metri
componenti: V, S
durata: istantanea
pagine_sorgente: 198-198
creatura_evocata: 
  id: cavalcatura_ultraterrena
  fonte: mostri
  risoluzione: lookup_by_id

creature_evocate_inline: 
  - id: null
    nome: Cavalcatura ultraterrena
    tipo_blocco: creatura_evocata
    statblock: 
      tipo: Celestiale, folletto o immondo (a scelta)
      dimensione: null
      allineamento: allineamento del tipo scelto
      classe_armatura: 10 + 1 per livello dell'incantesimo
      punti_ferita: "v5 + 10 per livello dell'incantesimo (la cavalcatura ha un numero di Dadi Vita [d10] pari al livello dell'incantesimo)"
      velocita: 18 m, volo 18 m (richiede incantesimo di 4º livello o superiore)
      caratteristiche: 
        forza: 
          valore: 18
          modificatore: +4

        destrezza: 
          valore: 12
          modificatore: +1

        costituzione: 
          valore: 14
          modificatore: +2

        intelligenza: 
          valore: 6
          modificatore: "-2"

        saggezza: 
          valore: 12
          modificatore: +1

        carisma: 
          valore: 8
          modificatore: "-1"


      tiri_salvezza_base: 
        forza: +4
        destrezza: +1
        costituzione: +2
        intelligenza: +2
        saggezza: +1
        carisma: "-1"

      immunita_danni: null
      immunita_condizioni: null
      sensi: ""
      lingue: telepatia 1,5 km (funziona solo con l'incantatore) GS nessuno (PE 0; BC pari al bonus di competenza del personaggio)
      grado_sfida: null
      bonus_competenza: null
      azioni: 
        - nome: Schianto ultraterreno
          descrizione: ""
      sezioni: 
        - titolo: Tratti
          blocchi: 
            - nome: Legame vitale
              descrizione: Quando l'incantatore recupera punti ferita grazie a un incantesimo di 1º livello o superiore, la cavalcatura recupera la stessa quantità di punti ferita se l'incantatore si trova entro 1,5 metri da essa.
        - titolo: Azioni bonus
          blocchi: 
            - nome: Passo fatato (solo folletto; ricarica dopo un riposo lungo)
              descrizione: La cavalcatura si teletrasporta, insieme al suo cavaliere, in un uno spazio libero a scelta del personaggio situato a 18 metri da sé.
            - nome: Sguardo letale (solo immondo; ricarica dopo un riposo lungo)
              descrizione: ""
            - nome: Tocco guaritore (solo celestiale; ricarica dopo un riposo lungo)
              descrizione: "Una creatura entro 1,5 metri dalla cavalcatura recupera un numero di punti ferita pari a 2d8 più il livello dell'incantesimo.\n\n---"
---
L'incantatore evoca un essere ultraterreno che appare come una cavalcatura forte e fedele in uno spazio libero a scelta dell'incantatore entro gittata. Questa creatura usa la scheda delle statistiche della cavalcatura ultraterrena. Se l'incantatore possiede già una cavalcatura evocata con questo incantesimo, essa viene sostituita da quella nuova.

La cavalcatura ha l'aspetto di un animale di taglia Grande a scelta dell'incantatore, per esempio un cavallo, un cammello, un lupo feroce o un alce. Ogni volta che l'incantatore lancia l'incantesimo, sceglie il tipo di creatura della cavalcatura (celestiale, folletto o immondo) e questa scelta determina i tratti e la scheda delle statistiche della creatura.

Combattimento. La cavalcatura diventa un alleato per l'incantatore e i suoi alleati. In combattimento, ha lo stesso punteggio di iniziativa dell'incantatore, il quale può salirci in sella e guidarla come se fosse una cavalcatura controllata (come descritto nelle regole riguardanti il combattimento in sella). Se l'incantatore è incapacitato, la cavalcatura inizia il suo turno subito dopo quello dell'incantatore: la creatura è indipendente e si concentra sul proteggere l'incantatore.

Scomparsa della cavalcatura. La cavalcatura scompare quando scende a 0 punti ferita o se l'incantatore muore. Quando scompare, nello spazio che occupava in precedenza lascia qualsiasi oggetto stesse indossando o trasportando. Lanciando nuovamente l'incantesimo, l'incantatore può scegliere se evocare la cavalcatura scomparsa o una diversa.

### Scaling

**Utilizzo di uno slot incantesimo di livello superiore**
Usa il livello dello slot incantesimo relativo al livello dell'incantesimo nella scheda delle statistiche.
