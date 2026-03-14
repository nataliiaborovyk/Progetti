# Information Systems UML Modeling

Collection of database design projects focused on **conceptual modeling, UML diagrams and relational database design**.

This repository contains several academic projects developed during the study of **Information Systems and Database Design**.

Each project follows the complete design process:

1. analysis of requirements  
2. conceptual modeling using UML  
3. restructuring for relational databases  
4. translation into SQL schema  

The goal of these projects is to model real-world domains and design coherent relational database structures.

---

# Projects

## 1. Cruise Agency Management System

Database design for a travel agency that organizes cruises.

The system manages:

- cruises and itineraries  
- ships used for the cruises  
- destinations and excursion locations  
- customers and reservations  

Main concepts modeled:

- cruise scheduling  
- itineraries composed of ordered destinations  
- excursion locations within destinations  
- booking management and statistics  

Project folder:
[Sistema_Agenzia_Crociere](Sistema_Agenzia_Crociere)


---

## 2. Hospitality Platform for Travelers

Database design for a web platform where travelers can request hospitality from other users, similar to Couchsurfing.

The system allows users to:

- register personal profiles  
- offer accommodation in their homes  
- search for hosts in a city and period  
- request and manage bookings  
- leave feedback after a stay  

Main concepts modeled:

- users and hosts  
- accommodations, rooms and beds  
- booking requests  
- availability periods and exceptional closures  
- feedback system between travelers and hosts  

Project folder:
[Sistema_Ospitalita_Tra_Viaggiatori](Sistema_Ospitalita_Tra_Viaggiatori)


---

## 3. Coworking Space Management System

Database design for a system that manages a coworking space.

The platform manages:

- customers and users of the workspace  
- subscription plans and tariffs  
- services offered (meeting rooms, equipment)  
- workspace access tracking  
- service usage and billing  

Main concepts modeled:

- subscription plans with included services  
- workspace access history  
- service usage tracking  
- billing and statistics  

Project folder:
[Sistema_Spazio_Coworking](Sistema_Spazio_Coworking)

---

# Design Process

Each project follows the same design methodology:

### 1. Requirement Analysis
Study of the textual problem description and identification of domain entities.

### 2. Conceptual Modeling
Creation of UML class diagrams to represent entities, attributes and relationships.

### 3. Database-Oriented Restructuring
Adaptation of the conceptual model for relational database implementation.

### 4. Relational Translation
Definition of the SQL schema including:

- tables
- primary keys
- foreign keys
- integrity constraints

---

# Repository Structure
```text
INFORMATION-SYSTEMS-UML-MODELING
│
├── Sistema_Agenzia_Crociere
│ ├── README.md
│ ├── problem_description.md
│ ├── functional_specifications.pdf
│ ├── database_schema.sql
│ ├── uml_class_diagram.png
│ └── uml_restructured_for_database.png
│
├── Sistema_Ospitalita_Tra_Viaggiatori
│ ├── README.md
│ ├── problem_description.md
│ ├── functional_specifications.pdf
│ ├── database_schema.sql
│ ├── uml_class_diagram.png
│ └── uml_restructured_for_database.png
│
├── Sistema_Spazio_Coworking
│ ├── README.md
│ ├── problem_description.md
│ ├── functional_specifications.pdf
│ ├── database_schema.sql
│ ├── uml_class_diagram.png
│ └── uml_restructured_for_database.png
│
└── README.md
```

---

# Technologies and Concepts

- UML modeling  
- conceptual database design  
- relational database design  
- SQL schema definition  
- integrity constraints  

---

# Academic Context

These projects were developed as part of coursework on **Information Systems Design and Database Modeling**.
