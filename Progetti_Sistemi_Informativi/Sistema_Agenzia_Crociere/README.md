# Sistema Agenzia Crociere

## Descrizione

Questo progetto rappresenta la progettazione di un sistema informativo per la gestione di una agenzia turistica che organizza crociere.

Il sistema permette di gestire:

- crociere offerte dall’agenzia  
- itinerari e destinazioni  
- navi utilizzate per le crociere  
- clienti e prenotazioni  
- attività e luoghi visitabili durante le escursioni  

Il progetto è stato sviluppato partendo dalla specifica dei requisiti e dalla modellazione UML, fino alla traduzione in schema relazionale per basi di dati.

---

# Fasi principali del progetto

## 1. Analisi dei requisiti

Studio del problema e identificazione delle principali entità del sistema, tra cui:

- Crociera  
- Nave  
- Cliente  
- Prenotazione  
- Itinerario  
- Scalo  
- Destinazione  
- PostoEscursione  

Sono state inoltre definite le principali funzionalità richieste dal sistema, come la gestione delle prenotazioni e il calcolo di statistiche.

---

## 2. Modellazione concettuale

Realizzazione del diagramma UML delle classi per rappresentare:

- entità del dominio  
- attributi  
- associazioni tra le classi  
- vincoli del sistema  

È stato inoltre definito il diagramma UML degli use case per descrivere le principali operazioni del sistema.

---

## 3. Ristrutturazione per basi di dati

Il modello concettuale è stato adattato per la progettazione del database tramite:

- ristrutturazione del diagramma UML  
- definizione dei vincoli di integrità  
- preparazione dello schema per la traduzione relazionale.

---

## 4. Traduzione in schema relazionale

Il modello è stato trasformato in schema relazionale SQL, definendo:

- tabelle
- chiavi primarie
- chiavi esterne
- domini e tipi personalizzati
- vincoli di integrità.

---

# Funzionalità principali

Il sistema supporta diverse operazioni, tra cui:

- prenotazione di posti su una crociera
- gestione delle destinazioni e delle escursioni
- calcolo dell’età media dei clienti che prenotano crociere con destinazioni esotiche
- calcolo della percentuale di destinazioni più richieste in un certo periodo

---

# Tecnologie utilizzate

- UML (modellazione concettuale)
- SQL
- progettazione di basi di dati relazionali

---

# Contesto del progetto

Progetto sviluppato come esercizio accademico nell’ambito dello studio di progettazione di sistemi informativi e basi di dati.