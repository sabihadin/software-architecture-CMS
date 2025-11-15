# Architectural Style

## Context and Problem Statement
Before the CMS is developed, the architectural style needs to be decided to dictate the design of the software and how its components interact.

## Considered Options

-	Client/Server Architecture
-	Layered Architecture
-	Monolithic Architecture
-	Distributed Architecture


## Decision Outcome

Chosen option: “Layered Architecture” because it keeps each layer of the system separate. For example, keeping the presentation (UI) layer, database layer, and the business layer separate makes the system easier to maintain because any changes made to one layer does not affect the others (Cherif, 2024). 

### Consequences

-	Good, because the separation keeps the system simple and modular, meaning each layer can be maintained and updated without affecting other layers, and layers can be added after. This also makes the development of the new layers simpler as the structure of the layers have been standardised. 
-	Bad, because the complex structure means each request from the system must pass through multiple layers and this sequential flow can increase response times. Tight coupling can occur if not regularly maintained (Cherif, 2024).
