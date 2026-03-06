# Sistema Ospitalità tra Viaggiatori

## Overview

Questo progetto rappresenta la progettazione di un sistema informativo per una piattaforma web di ospitalità tra viaggiatori, simile a servizi come Couchsurfing.

Il sistema consente agli utenti registrati di offrire ospitalità nella propria abitazione e ai viaggiatori di cercare alloggi disponibili durante i loro viaggi.

La piattaforma permette di:

- registrare utenti e profili personali
- pubblicare alloggi disponibili
- cercare ospitanti in una città e in un determinato periodo
- gestire richieste di prenotazione
- valutare ospitanti e viaggiatori tramite un sistema di feedback

L'obiettivo del progetto è modellare il dominio del problema e progettare una base di dati relazionale coerente e ben strutturata.

---

# System Architecture

Il progetto segue le principali fasi di progettazione di un sistema informativo:

1. **Analisi dei requisiti**  
   Definizione delle funzionalità del sistema e delle informazioni da gestire.

2. **Modellazione concettuale (UML)**  
   Creazione del diagramma delle classi per rappresentare entità, relazioni e vincoli del dominio.

3. **Ristrutturazione per basi di dati**  
   Adattamento del modello concettuale per l'implementazione su database relazionale.

4. **Traduzione in schema relazionale**  
   Definizione delle tabelle SQL con chiavi primarie, chiavi esterne e vincoli di integrità.

---

# Data Model

Il modello concettuale è stato progettato utilizzando **diagrammi UML delle classi**.

Le entità principali del sistema sono:

- **Utente** – persona registrata al portale  
- **Alloggio** – abitazione offerta per ospitalità  
- **Camera** – stanza dell’alloggio  
- **Letto** – unità di ospitalità prenotabile  
- **Prenotazione** – richiesta di soggiorno effettuata da un viaggiatore  
- **SceltaPosto** – selezione dei letti per una prenotazione  

Il modello include inoltre elementi per gestire la disponibilità degli alloggi:

- **PeriodoChiusura** – periodi in cui l’alloggio non è disponibile  
- **ChiusuraStraordinaria** – chiusure temporanee dovute a imprevisti.

---

# Key Features

Il sistema supporta diverse funzionalità principali:

### Registrazione utenti
Gli utenti possono registrarsi al portale fornendo informazioni personali e indicando se desiderano offrire ospitalità.

### Gestione alloggi
Gli ospitanti possono:

- registrare il proprio alloggio
- definire camere e posti letto
- indicare il numero massimo di ospiti
- gestire periodi di chiusura o indisponibilità.

### Ricerca alloggi
I viaggiatori possono cercare ospitanti disponibili:

- in una specifica città
- in un determinato periodo
- con un numero sufficiente di posti disponibili.

### Gestione prenotazioni
I viaggiatori possono inviare richieste di prenotazione che l’ospitante può:

- **accettare**
- **rifiutare**, indicando una motivazione.

### Sistema di feedback
Dopo il soggiorno:

- il viaggiatore deve valutare l’ospitante
- l’ospitante può valutare il viaggiatore

Questo meccanismo aiuta a garantire affidabilità e sicurezza nella piattaforma.

---

# Database Schema

Il database relazionale include tabelle per rappresentare:

- utenti
- alloggi
- camere
- letti
- prenotazioni
- periodi di chiusura
- valutazioni

Lo schema include inoltre diversi **vincoli di integrità** per garantire la coerenza dei dati, ad esempio:

- prenotazioni non sovrapposte per lo stesso utente
- numero di ospiti non superiore ai posti disponibili
- prenotazioni valide solo per periodi disponibili
- assegnazione dei letti coerente con l’alloggio.

---

# Tecnologie utilizzate

- UML (modellazione concettuale)
- SQL
- progettazione di basi di dati relazionali

---

# Contesto del progetto

Progetto sviluppato come esercizio accademico nell’ambito dello studio di **progettazione di sistemi informativi e basi di dati**.