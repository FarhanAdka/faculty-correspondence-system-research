# Faculty Correspondence & Administration System 🎓

![Project Status](https://img.shields.io/badge/Status-Prototype%20Completed-success)
![Tech Stack](https://img.shields.io/badge/Stack-Bun_Runtime_%7C_ElysiaJS_%7C_PostgreSQL-black)
![Role](https://img.shields.io/badge/Role-Backend_Engineer_(Research_Team)-blue)

## 📌 Project Overview
This project is a **funded research initiative** aimed at modernizing the faculty's administrative processes. As a key member of a 4-person research team, I was responsible for engineering the **Graduation Administration Module**.

The system replaces legacy manual workflows with a high-performance digital platform, handling complex document verification logic.

**Note:** *Source code is intellectual property of the research grant/university and is not publicly available. This repository serves as technical documentation.*

---

## 🏗️ High-Level Architecture
The backend is built on the **Bun runtime** using **ElysiaJS** framework to ensure maximum throughput and low latency. It communicates with a React (UmiJS) frontend.

![System Architecture](system-architecture.png) 

---

## 🧠 Key Logic: Graduation Clearance Workflow
One of the most complex challenges was orchestrating the "Clearance Letter" validation. The system must verify approval from 3 distinct departments (Library, Finance, Faculty Tool) before unlocking the graduation application.

**Sequence Diagram:**
![Sequence Diagram](graduation-flow-sequence.png)

---

## 🗄️ Database Design (ERD)
I designed a normalized PostgreSQL schema to maintain data integrity across student records and approval logs.

![ERD](database-erd.png)

---

## 🚀 Key Technical Contributions
- **Performance:** Leveraged **Bun**'s speed for API response times < 50ms.
- **Component Reusability:** Built the Graduation Module by extending shared backend components established by the core team.
- **Complex Validation:** Implemented a multi-step approval gatekeeper pattern.
