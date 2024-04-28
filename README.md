# Software di Gestione Ordinazioni per Ristorante

# Specifica dei Requisiti
## ANALISI DEL PROBLEMA
### 1) CONTESTO
   Il problema analizzato si verifica nel contesto della ristorazione in generale.
### 2) DESCRIZIONE DEL PROBLEMA
   Il problema analizzato riguarda la procedura di ordinazione che viene effettuata a mano da parte dei camerieri e trasportata fisicamente in cucina.
### 3) OBIETTIVO
   L'obiettivo del software è quindi quello di sostiture in maniera telematica le varie procedure del caso.

## REQUISITI FUNZIONALI

Di seguito sono elencate le funzionalità richieste.
### 1) REGISTRAZIONE DEGLI UTENTI
   Il software dovrà permettere agli utenti di creare un proprio account sulla piattaforma, ciò permetterà di assegnare loro un ruolo che sarà fondamentale per l'esecuzione 
   delle proprie mansioni.
### 2) RICONOSCIMENTO ACCOUNT
   Il software dovrà capire quale utente ha eseguito l'accesso sulla piattaforma e rendere disponibile l'utilizzo delle funzioni a lui riservate.
### 3) INVIO DEI DATI TRA GLI UTENTI
   Il software dovrà permettere l'invio degli ordini attraverso gli utenti e la visualizzazione dello stato degli stessi.
### 4) IMPOSTAZIONE STATO ORDINI
   Il software dovrà permettere la modifica dello stato dell'ordine riguardo la preparazione o la consegna al tavolo.

   ## VALUE PROPOSITION
   ORDINAZIONI EFFICIENTI <br>
   La nostra web app offre un'efficace piattaforma per gestire le ordinazioni in modo intuitivo ed efficiente. Aiutiamo i camerieri a prendere ordinazioni in modo rapido e preciso, trasmettendo istantaneamente gli ordini direttamente alla cucina. Gli addetti in cucina possono visualizzare immediatamente gli ordini in arrivo, migliorando la comunicazione e riducendo i tempi di preparazione. Con la nostra soluzione, ottieni un flusso di lavoro fluido e coordinato, migliorando l'esperienza del cliente e ottimizzando l'efficienza operativa del tuo ristorante

# CASI D'USO

## 1) Creazione nuovo ordine:
* Attore: Cameriere
* Scenario: Il cameriere, previa auenticazione, crea un nuovo ordine indicando cosa desiderano i clienti, il loro tavolo e le eventuali annotazioni particolari come ad esempio le intolleranze alimentari o la modifica di alcuni ingredienti di un piatto.

## 2) Modifica ordine esistente:
* Attore: Cameriere
* Scenario: Il cameriere, previa autenticazione, ha la possibilità di modificare un ordine rimuovendo o aggiungeno elementi nello stesso.

## 3) Visualizzazione ordini:
* Attori: Cameriere, Cucina (Cuoco, Pizzaiolo, Barista)
* Scenario: Il cameriere o gli addetti alla cucina, all'occorrenza e previa autenticazione, possono visualizzare tutti gli ordini effettuati e consegnati.

## 4) Cancellazione ordine:
* Attori: Cameriere, Cucina (Cuoco, Pizzaiolo, Barista)
* Scenario: Il cameriere o gli addetti alla cucina, all'occorrenza e previa autenticazione, possono cancellare un ordine effettuato in precedenza.

## 5) Conferma e invio ordine:
* Attore: Cameriere
* Scenario: Il cameriere, finito di strutturare l'ordine e previa autenticazione, può confermare e inviare l'ordine agli addetti in cucina.

## 6) Impostazione stato ordine come servito:
* Attore: Cameriere
* Scenario: Il cameriere, consegnato il piatto al tavolo che lo ha richiesto e previa autenticazione, può contrassegnare l'ordine come in stato di servito.

## 7) Impostazione stato ordine come pronto:
* Attore: Cucina (Cuoco, Pizzaiolo, Barista)
* Scenario: Gli addetti alla cucina, finita la preparazione dell'ordine e previa autenticazione, possono contrassegnare l'ordine come pronto.

## 8) Generazione del conto:
* Attore: Cameriere
* Scenario: Il cameriere, previa richiesta da parte dei clienti e previa autenticazione, può generare il conto del pasto e applicare eventuali sconti o convezioni del ristorante.

# DIAGRAMMA UML
https://yuml.me/98710343.svg

