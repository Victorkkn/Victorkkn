<div align="center">

# Víctor Kennedy

**Backend Engineer · Python · Event-Driven Systems · Identity & Access**
**AI Training & Evaluation**

Based in Brazil (UTC−3) · Remote · Working with international teams

[LinkedIn](https://www.linkedin.com/in/victorkennedy) · [Certifications](#certifications)

</div>

---

## About

Backend engineer with 6+ years of Python, building event-driven microservices for financial services and secure identity platforms. I also do hands-on AI training and evaluation work: writing multi-step tasks for models, reviewing other contributors' work, and judging model outputs against defined criteria.

I care about code quality, testing, and clear technical communication, and I use AI coding tools daily (Claude, Cursor, Codex, GPT, Gemini, Antigravity).

```python
victor = {
    "focus":     ["event-driven microservices", "IAM / OAuth2 / OIDC", "AI task design & evaluation"],
    "languages": ["Python", "C#/.NET", "SQL", "JavaScript"],
    "clouds":    ["GCP", "Azure", "AWS"],
    "currently": "Core banking & fintech systems on GCP",
    "education": "MBA in Data Science & AI",
}
```

## What I do

**Backend & event-driven systems.** Async Python services (FastAPI, asyncio), Clean/Hexagonal Architecture, Pub/Sub messaging with retries and dead-letter queues, PostgreSQL, Kubernetes.

**Identity & access.** Keycloak, OAuth2/OIDC, SSO, RBAC, Entra ID, Okta, Auth0. I have built and operated SSO platforms and secured APIs with role-based access.

**AI training & evaluation.** Authoring model-training tasks, reference solutions, and code-response comparisons. Details below.

**Cloud & delivery.** CI/CD, containers, GitOps, observability across Azure, GCP and AWS.

## AI training & evaluation

- **Task authoring (Fleet AI):** wrote prompts and step-by-step tasks to train models, including multi-tool workflows spanning email, chat, ticketing, documentation and security systems. Recorded reference solutions in a virtual environment for models and reviewers to compare against.
- **Task review (Fleet AI):** reviewed tasks written by other contributors, comparing the author's result, a human attempter's result, and the model's.
- **Response evaluation (Alignerr):** compared pairs of model responses to code prompts and judged which was better against defined criteria, using a local git and CLI workflow with written judgments and submitted diffs.

## Selected work

**Core banking & fintech platform · GFT (Dec 2025 – present)**
Event-driven Python microservices on GCP for onboarding/KYC, fraud and transaction-risk decisions, biometric identity verification, and credit eligibility.
- Async services with FastAPI, uvloop and asyncpg, following Clean/Hexagonal Architecture
- Pub/Sub pipelines with exactly-once delivery, dead-letter queues and immutable event logs for auditability
- 80%+ test coverage with pytest-asyncio, integration tests and mutation testing
- Zero-downtime Kubernetes deployments with GitOps, feature flags and Datadog APM

*Client details are confidential; I can discuss the technology and design decisions.*

**Snap Reports · Techbiz (2022 – 2025)**
A forensic data-aggregation platform for law-enforcement investigators, which I initiated, designed and shipped.
- Consolidates public and private data from 10+ sources into one searchable interface with relationship mapping between people and companies
- Evolved through three versions (Firebase + React → Supabase → FastAPI + Docker) after customer feedback required on-premises deployment
- Client-side encryption so the server cannot see what investigators search for
- AI-assisted link suggestions: deterministic matching plus an LLM for ambiguous fields, with investigators reviewing every suggestion
- Sold as licensed software to police units across Brazil

**SSO & access control · Techbiz**
Keycloak SSO on Docker Swarm, with OAuth2 brokering for Google and Microsoft and RBAC across 100+ API endpoints. Also: SSL/Certbot setup, Unleash feature flags, Redis caching.

**Data ingestion & pipelines · Techbiz**
Ingestion services integrating 10+ third-party providers, with async processing through Kafka, MinIO and Celery. Parallelized provider lookups to cut critical-path latency by roughly 50%.

**Earlier · Localiza (2020 – 2022)**
Python automation, workforce-management applications, and Power BI dashboards used by directors and managers for business decisions.

## Stack

**Backend** `Python` `FastAPI` `Flask` `asyncio` `SQLAlchemy` `Pydantic` `C#/.NET` `PostgreSQL` `Redis`

**Messaging & data** `GCP Pub/Sub` `Kafka` `RabbitMQ` `Celery` `MinIO` `Pandas`

**Identity** `Keycloak` `OAuth2` `OIDC` `SSO` `RBAC` `JWT` `Entra ID` `Okta` `Auth0`

**Cloud & DevOps** `GCP` `Azure` `AWS` `Kubernetes` `Docker` `GitOps` `Azure Pipelines` `Datadog`

**Testing & quality** `pytest` `pytest-asyncio` `mutation testing` `integration testing`

**AI & data** `LLM APIs` `prompt engineering` `model evaluation` `embeddings` `Power BI`

## Certifications

Microsoft credentials link to Microsoft Learn; AWS credentials link to Credly. Every link is a public verification page.

**Highlights**
- [Microsoft Certified: Azure Solutions Architect Expert](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/DE835A9EDAD78A58?sharingId=5FF306831E8A0A0C)
- [Microsoft Certified: DevOps Engineer Expert](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/8DFAB5BA7E7C1F0E?sharingId=5FF306831E8A0A0C)
- [Microsoft Certified: Agentic AI Business Solutions Architect Expert](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/DA938AE12CB0A53D?sharingId=5FF306831E8A0A0C)
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/a5d78309-e418-4c39-b7c7-50426cdadf5d/public_url)
- [AWS Certified Developer – Associate](https://www.credly.com/badges/d7debc3a-b030-4ea9-a9a9-134429b3d4e7/public_url)
- [AWS Certified AI Practitioner](https://www.credly.com/badges/6c59082b-b53e-49a2-bf63-9c52a867068a/public_url)

**Microsoft: Associate and Specialty**
[Azure Administrator](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/E7B9B2B48C75F35C?sharingId=5FF306831E8A0A0C) · [Azure Network Engineer](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/44607B170BBCCF11?sharingId=5FF306831E8A0A0C) · [Azure Virtual Desktop (Specialty)](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/E14E5F2272DD829B?sharingId=5FF306831E8A0A0C) · [Power Platform Developer](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/64742598194AF74F?sharingId=5FF306831E8A0A0C) · [Power Platform Functional Consultant](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/9F8EF69CF430C832?sharingId=5FF306831E8A0A0C) · [Power BI Data Analyst](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/1B59F37D4629E2E7?sharingId=5FF306831E8A0A0C)

**Microsoft: Fundamentals**
[Azure](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/5415B3995EC8C9ED?sharingId=5FF306831E8A0A0C) · [Azure AI](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/25A31184E1096A17?sharingId=5FF306831E8A0A0C) · [Azure Data](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/913CAB90EC519ADC?sharingId=5FF306831E8A0A0C) · [Microsoft 365](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/5A8E131AF3C71979?sharingId=5FF306831E8A0A0C) · [Security, Compliance & Identity](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/5BBC53F4754BED49?sharingId=5FF306831E8A0A0C) · [Dynamics 365 ERP](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/425F2415805CA218?sharingId=5FF306831E8A0A0C) · [Dynamics 365 CRM](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/70ED164C0B0A8497?sharingId=5FF306831E8A0A0C) · [Power Platform](https://learn.microsoft.com/api/credentials/share/pt-br/VctorNunes-2692/B211A6571E36EBCE?sharingId=5FF306831E8A0A0C)

**AWS: Practitioner**
[Cloud](https://www.credly.com/badges/d42100f2-2ad8-4304-a61b-b53dd57a5d54/public_url)

## Education & languages

**Education**
- MBA, Data Science & Artificial Intelligence · FIAP
- Postgraduate, Business Consulting · FIA Business School
- B.Sc., Mechanical Engineering · CEFET-MG (exchange semester in Germany, 2019)

**Languages**
- Portuguese · C2 (native)
- English · C1
- German · B1
- Spanish · B1

## Public code

<!-- TODO: add new showcase repositories here (e.g. FastAPI + Keycloak token validation demo, event-driven Pub/Sub demo) -->

- **[CognitiveEnvironments](https://github.com/Victorkkn/CognitiveEnvironments)**: coursework for the Cognitive Environments subject (Jupyter Notebook)
- **[SudokuSolver](https://github.com/Victorkkn/SudokuSolver)**: Sudoku solver in JavaScript

Most of my professional work is in private or client repositories, so the case studies above are the best view of what I build.

## Get in touch

I'm open to remote backend, IAM, and AI-evaluation work with international teams.

[LinkedIn](https://www.linkedin.com/in/victorkennedy) · [Certifications](#certifications)
