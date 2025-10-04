# UML Project – Smart Fitness System

## Project Context
This project was developed as part of the *UML (Unified Modeling Language)* module at the École des Mines de Saint-Étienne.  
The objective was not to produce an executable program, but to **design and document a complete UML architecture** for a connected fitness coaching application.  

The provided C++ header files represent a **conceptual translation of the UML class diagram**, serving as a structural prototype of the system.  
Each class models a real-world entity — user, session, sensor, payment, subscription, etc. — and demonstrates the object-oriented relationships defined in the UML design.


## Overview
This project involves the design and documentation of a UML-based system. The key components of the project include a class diagram, a detailed project report, multiple header files defining the system's structure and functionality, and a main header file orchestrating the system's operation.

## Contents
1. **Class Diagram** (`Class Diagram.png`)
   - A graphical representation of the system's structure, showing classes, attributes, methods, and their relationships.
   - Key entities include `Utilisateur`, `BaseDeDonnees`, `Seance`, `Capteur`, `Abonnement`, and others.

2. **Project Report** (`UML Project Report - Walid MOUH MOUH.pdf`)
   - A detailed explanation of the UML model, design choices, and functionality.
   - Describes the responsibilities of different classes, use case scenarios, and potential system behaviors.

3. **Header Files**
   - Define the system's main components and their interactions.
   - Key files:
     - `Abonnement.h` - Defines subscription types and renewal functionalities.
     - `BaseDeDonnees.h` - Manages storage and retrieval of user and session data.
     - `Capteur.h` - Handles different types of sensors (Bluetooth, WiFi).
     - `CoachVirtuel.h` - Provides performance analysis and advice.
     - `Exercice.h` - Defines exercise types and their instructions.
     - `Notification.h` - Manages notifications for sessions and subscriptions.
     - `Paiement.h` - Handles payment processing and validation.
     - `RapportPerformance.h` - Generates performance reports.
     - `Seance.h` - Manages exercise sessions and their storage.
     - `Utilisateur.h` - Defines user functionalities, including session management and sensor interaction.
     - `main.h` - The central header file that includes all other headers and manages the core system functionalities.

4. **Main Header File (`main.h`)**
   - Orchestrates system operations by including all key headers.
   - Provides essential utility functions for:
     - Displaying menus (`afficherMenu`).
     - Managing users (`gestionUtilisateur`).
     - Handling exercise sessions (`gestionSeance`).
     - Processing payments (`gestionPaiement`).
     - Managing notifications (`gestionNotifications`).

## How to Navigate
- Start by reviewing the **Class Diagram** to get an overall understanding of the system architecture.
- Read the **Project Report** for an in-depth explanation of the design choices and system functionality.
- Explore the **Header Files** to understand the implementation details and system components.
- Refer to **main.h** to see how the different system components interact within the core program structure.
