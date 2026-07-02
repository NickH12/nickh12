<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f6e56,100:185fa5&height=200&section=header&text=Nick%20Haimov&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Fullstack%20Developer%20%7C%20B.Sc.%20Computer%20Science&descAlignY=55&descSize=18" width="100%"/>

# Hey there, I'm Nick! 👋

**Fullstack developer** passionate about scalable systems, clean architecture, and solving hard problems under pressure.
B.Sc. in Computer Science · Holon Institute of Technology (HIT) · GPA: 89

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nickhaimov)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nickhaimov@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NickH12)

</div>

---

## About Me

- 🎓 **B.Sc. Computer Science** - Holon Institute of Technology (HIT), GPA: 89
- 🏆 **Dean's Excellence Award** - 3rd year
- Focused on Backend APIs, Microservices, Cloud Infrastructure & DevOps
- Former combat soldier (MAGAV Border Police) - discipline, pressure & teamwork are in my DNA
- Hebrew (Native) · English (Fluent) · Russian (Intermediate)

---

## Featured Projects

### Bulk Data Importer - Async Microservice
`Python` `FastAPI` `PostgreSQL` `Redis` `Celery` `Docker` &nbsp; [![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NickH12/bulk-data-importer)

Designed and built a production-grade asynchronous ingestion service capable of handling large-scale data uploads without degrading API responsiveness. The core challenge was decoupling the upload lifecycle from the processing pipeline - achieved by introducing a task queue layer between the API and the workers.

- Engineered a non-blocking upload flow using **FastAPI** with background task dispatch via **Celery**, allowing the API to return immediately while heavy jobs run independently
- Designed a **Redis**-backed queue to manage job state, retry logic, and worker coordination across concurrent uploads
- Modeled the **PostgreSQL** schema to support partial imports, failure tracking, and resumable jobs - with strict input validation enforced through Pydantic at every boundary
- Containerized the full stack with **Docker Compose**, enabling consistent local development and straightforward deployment

---

### Job Search Management Dashboard
`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `JWT` `Docker` &nbsp; [![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NickH12/JobTracker)

A production-grade backend system for managing the full job application lifecycle. Built with a focus on clean architecture, security, and scalability - not just a CRUD app, but a structured platform that tracks companies, applications, and statuses with strict per-user data isolation.

- Architected JWT-based authentication with register, login, and protected routes - per-user data isolation enforced at the query level so users never access each other's data
- Designed a normalized **PostgreSQL** schema with **SQLAlchemy** ORM; managed schema evolution through **Alembic** migrations and enforced input contracts with Pydantic
- Applied **Repository Pattern** to decouple data access from business logic, enabling clean separation of concerns and straightforward unit testing
- Exposed a self-documenting REST API via FastAPI's auto-generated OpenAPI/Swagger interface

---

### End-to-End Cloud Infrastructure & GitOps Pipeline
`Terraform` `GCP` `Kubernetes` `ArgoCD` `NGINX` &nbsp; [![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NickH12/CloudGCP)

Provisioned and operated a complete cloud-native infrastructure from scratch, covering everything from raw compute to automated deployment pipelines. The goal was to build something that a real engineering team could hand off and run - not just a demo.

- Wrote **Terraform** modules to provision GCP infrastructure including VPC networking, firewall rules, compute instances, and IAM bindings - all versioned and reproducible
- Deployed containerized workloads on **Kubernetes**, configuring namespaces, deployments, services, and health checks for reliable operation
- Set up **ArgoCD** to watch the Git repository and automatically sync cluster state with every merge - eliminating manual deployment steps entirely
- Configured **NGINX Ingress Controller** for routing traffic across services, with separate ingress rules for the application and ArgoCD

---

### Enterprise Cybersecurity Management System
`Python` `FastAPI` `MySQL` `Docker`

Built a backend management platform for enterprise security operations, with a strong focus on data integrity, access control, and resilience against common attack vectors. Designed from the ground up with security as a first-class concern rather than an afterthought.

- Implemented layered input validation and **parameterized SQL queries** throughout the codebase, closing off SQL injection and XSS attack surfaces at the API boundary
- Architected a normalized **MySQL** relational schema optimized for the read-heavy query patterns typical of security dashboards and audit trails
- Structured the API around role-based access logic, ensuring sensitive operations are gated and auditable
- Containerized with **Docker** for reproducible deployments across environments

---

## Technical Skills

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend Frameworks**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Express](https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Concepts**
`REST APIs` · `Microservices` · `CI/CD` · `Async Processing` · `JWT Auth` · `GitOps`

---

## Certifications

**AWS Certified Solutions Architect – Associate** *(Stephane Maarek, Udemy - near completion)*

---

## Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nick%20Haimov-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nickhaimov)

<br/>

[![Email](https://img.shields.io/badge/Email-nickhaimov%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nickhaimov@gmail.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:185fa5,100:0f6e56&height=120&section=footer" width="100%"/>
</div>
