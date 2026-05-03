# Tipizzazione dei dati DND
Questo progetto ha l’obiettivo di **tipizzare e strutturare i dati** contenuti nello [Standard Reference Document](https://www.dndbeyond.com/srd) (SRD) di *Dungeons & Dragons*, utilizzando la **localizzazione italiana**.

Lo scopo è creare una base dati coerente e riutilizzabile, pensata per facilitare lo sviluppo di **applicazioni, strumenti e servizi** legati al mondo di D&D (ad esempio character builder, app di supporto al gioco, API, ecc.).

## Pipeline di tipizzazione
Il processo di trasformazione dei dati segue una pipeline strutturata che parte dal documento originale e produce diversi formati utilizzabili:

```
SRD (PDF) → Markdown → JSON
                     → YAML
```
- **PDF → Markdown**: conversione del contenuto in un formato testuale intermedio, più semplice da elaborare e versionare  
- **Markdown → JSON/YAML**: strutturazione dei dati in formati standard, ideali per l’integrazione in applicazioni software  

## Come contribuire al progetto
I contributi sono benvenuti!

Puoi partecipare in diversi modi:

- **Fork del repository**: crea una copia del progetto, apporta le modifiche e invia una *pull request*
- **Segnalazione di problemi**: usa la sezione *Issues* per riportare errori o proporre miglioramenti
- **Collaborazione diretta**: se desideri contribuire in modo continuativo, contattami per diventare *collaborator*
