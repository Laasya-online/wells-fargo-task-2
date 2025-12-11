---

<p align="center">

  <!-- Tech Stack -->
  <img src="https://img.shields.io/badge/Java-21-red?style=for-the-badge&logo=openjdk" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3.0-green?style=for-the-badge&logo=springboot" />
  <img src="https://img.shields.io/badge/JPA-Jakarta-orange?style=for-the-badge&logo=hibernate" />
  <img src="https://img.shields.io/badge/IntelliJ-IDEA-blue?style=for-the-badge&logo=intellijidea" />
  
  <!-- Tools -->
  <img src="https://img.shields.io/badge/GitHub-Version%20Control-black?style=for-the-badge&logo=github" />

  <!-- Forage Badge -->
  <img src="https://img.shields.io/badge/Forage-Job%20Simulation-purple?style=for-the-badge&logo=briefcase" />

</p>

---

# Wells Fargo Software Engineering Job Simulation

This repository contains my completed work for the **Wells Fargo Software Engineering Virtual Job Simulation** hosted on **Forage**.  

---

## Overview

During this simulation, I worked through the process of designing and implementing a data model for a system used by financial advisors to manage client portfolios.  
This included understanding requirements, modeling relationships, designing database entities, and implementing them using Java with Spring Boot and JPA.

---

## Key Accomplishments

### Requirements & System Understanding
- Analyzed business requirements for a system that manages financial advisor–client relationships.
- Identified functional and data needs for managing portfolios and securities.

### Data Modeling
- Determined what data structures the system needed to track.
- Designed an **Entity Relationship Diagram (ERD)** representing advisors, clients, portfolios, and securities.
- Ensured correct representation of 1:N and 1:1 relationships.

### Implementation
- Used **IntelliJ IDEA** to develop and implement Java entities following the ERD.
- Applied JPA annotations (`@Entity`, `@Id`, `@GeneratedValue`, relationships, constraints) to model the system accurately.
- Ensured each entity included constructors and appropriate getters/setters.

### Version Control & Deployment
- Pushed completed work to GitHub using standard version control workflows.

---

## Project Contents

- `Advisor.java` — Represents a financial advisor  
- `Client.java` — Represents a client linked to an advisor  
- `Portfolio.java` — Represents a client portfolio (1:1 with Client)  
- `Security.java` — Represents securities held in a portfolio (Many-to-One)

---

---

