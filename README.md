# 🌍 Ngelmak Project — Concept & Architecture

**Project Description:**

Aiming to create a free enterprise-level framework tailored for public services, this initiative focuses on enhancing efficiency, accessibility, and quality in the delivery of public sector offerings. The project seeks to leverage innovative solutions and collaborative approaches to ensure that essential services are available to all citizens at no cost, promoting inclusivity and sustainability within communities.

---

## 🎯 Purpose

This repository serves as the **concept hub** for the Ngelmak ecosystem.  
It contains the **LaTeX sources** and the **compiled PDF document** that explain the overall vision, design decisions, and system architecture.

Unlike the code repositories (Gateway, Thruline Core, Angular Web), this repo is dedicated to the **conceptual documentation** and does not include instructions for running services.

---

## 🧩 Project Overview

The Ngelmak ecosystem consists of:

- **API Gateway** → Entry point, JWT validation, Vault integration, routing.  
- **Thruline Core** → Social media logic, Postgres persistence, Vault secrets, messaging (RabbitMQ/Kafka planned).  
- **Angular Web** → Frontend interface, user interactions, connected via Gateway.  
- **Vault** → Centralized secret management.  
- **Postgres** → Relational database for core service.  
- **Future messaging layer** → RabbitMQ & Kafka for event-driven communication.  

---

## 📄 Documentation

The full documentation is available in PDF format:

👉 [View the Ngelmak Project Document](./src/main.pdf)

*(Compiled from LaTeX sources in this repository)*

---

## 📂 Repository Structure

```
ngelmak-description/
 ├── src/                # LaTeX sources
 │    ├── chapters/      # Individual sections
 │    ├── images/        # Source images
 │    ├── NgelmakProjectDesc.pdf/      # Compiled document (read this!)
 │    └── NgelmakProjectDesc.tex       # NgelmakProjectDesc entrypoint
 └── README.md           # This file
```


---

This way, the **Project Description** acts like a manifesto at the top, setting the tone for the rest of the README.