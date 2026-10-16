# Modellazione e Analisi dei Processi Aziendali della Scuola di Pittura

Progetto sviluppato per il corso di Modelli e Processi Aziendali (MPB) presso l'Universita di Pisa (A.A. 2025/2026).

## Panoramica del Progetto
Questo repository contiene i modelli di processi aziendali, le reti di workflow, i file di analisi e la documentazione relativi allo scenario della scuola di pittura. Il sistema modella le interazioni end-to-end tra allievi, maestri di pittura e segreteria della scuola, coprendo l'iscrizione ai corsi, la pianificazione iterativa delle lezioni, lo svolgimento delle attività didattiche, l'invio dei compiti, i pagamenti elettronici e la conclusione del corso.

Il progetto si concentra sulla progettazione di processi aziendali astratti (BPMN/EPC), sulla loro successiva trasformazione in reti di workflow (reti di Petri) e sulla verifica formale delle proprietà strutturali e comportamentali.

## Flusso di Analisi e Modellazione

### 1. Modellazione dello Scenario

* Progettazione della collaborazione e della coreografia che catturano le interazioni tra Allievo, Maestro e Scuola.
* Diagrammi di orchestrazione per ciascun singolo partecipante.
* Specifiche astratte iniziali modellate in formati BPMN/EPC.

###2. Trasformazione dei Modelli

* Mappatura sistematica dai modelli di collaborazione e orchestrazione BPMN a Reti di Workflow (WfN / Reti di Petri).
* Documentazione e giustificazione delle regole di trasformazione applicate.

### 3. Analisi Strutturale e Comportamentale

* Verifica delle proprietà strutturali sulle reti di workflow: invarianti, S-componenti, proprietà di free-choice, well-handledness e sicurezza/safeness.
* Analisi del grafo di raggiungibilità, inclusa la stima dello spazio degli stati (numero di vertici e di archi).

### 4. Verifica di Soundness

* Valutazione formale della soundness sulle singole orchestrazioni dei partecipanti (pool) e sulla rete di collaborazione complessiva.
* Analisi di potenziali deadlock, livelock o terminazioni anomale, con discussione della relaxed soundness e della weak soundness nei casi in cui la soundness completa non sia ottenibile.

## Strumenti Utilizzati

* Modellazione: Camunda Modeler, BPMN.io
* Trasformazione e Analisi: bpmn2petrinet, WoPeD, Woflan
* Documentazione: LaTeX


# Painting School Business Process Modeling and Analysis 

Project developed for the Business Process Modeling (MPB) course at the University of Pisa (A.Y. 2025/2026).

## Project Overview
This repository contains the business process models, workflow nets, analysis files, and documentation for the "Scuola di pittura" (Painting School) scenario. The system models the end-to-end interactions between students, painting instructors, and the school administration, covering course enrollment, iterative scheduling of painting lessons, lesson execution, homework delivery, electronic payments, and course completion.

The project focuses on designing abstract business processes (BPMN/EPC), translating them into workflow nets (Petri nets), and formally verifying structural and behavioral properties.

## Analysis and Modeling Workflow

### 1. Scenario Modeling

* Collaboration and choreography design capturing interactions between Student, Instructor, and School.
* Orchestration diagrams for each individual participant.
* Initial abstract specifications modeled in BPMN/EPC formats.
  
### 2. Model Transformation

* Systematic mapping from BPMN collaboration and orchestration models into Workflow Nets (WfN / Petri nets).
* Documentation and justification of the transformation rules applied.

### 3. Structural and Behavioral Analysis

* Structural property verification on the workflow nets: invariants, S-components, free-choice, well-handledness, and boundedness/safeness.
* Reachability graph analysis, including state-space estimation (number of vertices and edges).

### 4. Soundness Verification

* Formal soundness evaluation on individual participant orchestrations (pools) and on the global collaboration net.
* Analysis of potential deadlocks, livelocks, or improper termination, with discussion of relaxed soundness and weak soundness where full soundness is not achievable.

## Tools Used

* Modeling: Camunda Modeler, BPMN.io
* Transformation & Analysis: bpmn2petrinet, WoPeD, Woflan
* Documentation: LaTeX
