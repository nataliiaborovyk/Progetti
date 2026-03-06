# Sistema Spazio Coworking

## Overview

Questo progetto rappresenta la progettazione di un sistema informativo per la gestione di uno spazio di coworking.

Il sistema permette di gestire:

- clienti e utenti dello spazio
- abbonamenti e tipologie di tariffa
- servizi disponibili (sale riunioni, attrezzature, ecc.)
- accessi allo spazio di lavoro
- utilizzo dei servizi e relativi costi

L'obiettivo del progetto è modellare il dominio del problema e progettare una base di dati relazionale coerente per la gestione delle attività di uno spazio di coworking.

---

# System Architecture

Il progetto segue le principali fasi di progettazione di un sistema informativo:

## Analisi dei requisiti
Definizione delle funzionalità richieste dal sistema e delle informazioni da gestire.

## Modellazione concettuale
Creazione di un **diagramma UML delle classi** per rappresentare entità, relazioni e vincoli del dominio.

## Progettazione per basi di dati
Ristrutturazione del modello concettuale e traduzione in **schema relazionale**.

---

# Data Model

Il modello dati include le principali entità del sistema:

- **Utente** – persona che utilizza lo spazio di coworking  
- **Cliente** – soggetto che sottoscrive un abbonamento (persona fisica o impresa)  
- **Abbonamento** – contratto che consente l’accesso allo spazio  
- **TipoAbbonamento** – definisce durata, prezzo e numero massimo di utenti  
- **Postazione** – postazione di lavoro assegnata a un utente  
- **Servizio** – servizi disponibili nello spazio (es. sala riunioni, stampante)  
- **UsoServizio** – utilizzo di un servizio da parte di un utente  
- **AccessoSpazio** – registrazione degli ingressi e delle uscite dallo spazio.

---

# Key Features

Il sistema consente di:

- registrare clienti e utenti dello spazio
- gestire abbonamenti e tipologie di tariffa
- registrare accessi e uscite degli utenti
- monitorare l’utilizzo dei servizi
- calcolare statistiche sull’utilizzo dello spazio e dei servizi.

---

# Tecnologie utilizzate

- UML
- progettazione di basi di dati
- SQL
- modellazione di sistemi informativi

---

# Contesto del progetto

Progetto sviluppato come esercizio accademico nell’ambito dello studio di **progettazione di sistemi informativi e basi di dati**.