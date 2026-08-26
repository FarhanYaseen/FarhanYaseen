<div align="center">

# Farhan Yaseen

### Senior Backend / Full-Stack Engineer

**Building scalable backend systems, cloud platforms, and data-intensive applications.**

`Node.js` · `TypeScript` · `Python` · `PostgreSQL` · `AWS` · `GCP` · `Kubernetes`

**10+ years in production engineering · 50K+ concurrent users · 1M+ events/day · $24K/year infrastructure savings**

[Portfolio](https://farhanyaseen.netlify.app) •
[LinkedIn](https://www.linkedin.com/in/farhanyaseen) •
[Email](mailto:farhan.yaseen.se@gmail.com)

</div>

---

## Engineering Profile

I'm a **Senior Backend / Full-Stack Engineer with 10+ years of production experience**, building and operating systems across SaaS, publishing, gaming, developer tooling, and data-intensive platforms.

My strongest area is backend and platform engineering: designing APIs, data models, distributed workflows, cloud infrastructure, observability, and systems that remain reliable as traffic and complexity increase.

I've also spent much of my career working across the full product stack, particularly with **React and Next.js**, which allows me to own problems from infrastructure and database design through API architecture and user-facing delivery.

I care about engineering systems that are:

* **Reliable** under real production conditions
* **Observable** when something goes wrong
* **Simple enough** for other engineers to understand
* **Scalable without premature complexity**
* **Well-tested** at the boundaries that matter
* **Designed around business outcomes**, not technology for its own sake

---

## Selected Engineering Impact

<table>
<tr>
<td width="50%" valign="top">

### 💰 $24K / year saved

Audited and redesigned a production **Algolia search architecture**, removed redundant indexes, and introduced incremental/delta indexing.

**Result:** approximately **$24,000 annual infrastructure cost reduction** while improving the search architecture.

</td>
<td width="50%" valign="top">

### ⚡ 50K+ concurrent users

Worked on production gaming infrastructure supporting **50,000+ concurrent players** with a focus on availability, scaling, deployment automation, and production monitoring.

**Availability:** up to **99.9% uptime**.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📊 1M+ events / day

Built and operated analytics and event-processing infrastructure handling **more than 1 million events per day**.

Worked across ingestion, processing, cloud infrastructure, and production monitoring.

</td>
<td width="50%" valign="top">

### 🧩 100K+ user platforms

Delivered features and platform improvements used across products serving **100,000+ users**.

Worked across backend services, frontend applications, integrations, data, and infrastructure.

</td>
</tr>
</table>

---

## What I Work On

| Area                    | Experience                                                                          |
| ----------------------- | ----------------------------------------------------------------------------------- |
| **Backend Engineering** | Node.js, TypeScript, Python, REST, GraphQL, API architecture                        |
| **System Design**       | Distributed systems, event-driven architecture, queues, caching, service boundaries |
| **Data**                | PostgreSQL, MongoDB, Redis, Elasticsearch, Algolia                                  |
| **Cloud & Platform**    | AWS, GCP, Kubernetes, Docker, Terraform                                             |
| **Reliability**         | Observability, monitoring, production debugging, performance optimization           |
| **Frontend**            | React, Next.js, Vue                                                                 |
| **Delivery**            | CI/CD, automated testing, deployment pipelines, engineering tooling                 |

---

# Featured Engineering Work

## AI CFO Dashboard

**Agentic financial intelligence system built around deterministic tools and structured financial data.**

[View Repository →](https://github.com/FarhanYaseen/ai-cfo-dashboard)

Instead of allowing an LLM to freely generate financial answers, the system separates reasoning from deterministic financial operations.

### Architecture highlights

* Agentic tool-calling workflow
* Typed database tools
* PostgreSQL / Supabase data layer
* Financial forecasting
* Statistical anomaly detection
* Duplicate expense detection
* Structured AI outputs
* Server and client component boundaries
* Documented architecture and execution flow

**Stack**

`Next.js` `TypeScript` `PostgreSQL` `Supabase` `AI/LLM`

---

## Motor Asset Monitor

**Full-stack industrial asset-monitoring application focused on scalable APIs, time-series data, and explicit architectural trade-offs.**

[View Repository →](https://github.com/FarhanYaseen/motor-asset-monitor)

### Architecture highlights

* REST API design
* Server-side pagination
* Repository-style data abstraction
* URL-driven frontend state
* Time-series sensor visualization
* Backend automated tests
* Frontend automated tests
* Docker-based local environment
* Production scaling considerations
* Documented architectural trade-offs

**Stack**

`Python` `Flask` `Angular` `TypeScript` `Docker`

---

# Architecture & Engineering

Most of the problems I enjoy solving live somewhere between application development and platform engineering.

```text
                         ┌─────────────────┐
                         │      Client     │
                         │ React / Next.js │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │   API / BFF     │
                         │ Node / Python   │
                         └────────┬────────┘
                                  │
                  ┌───────────────┼───────────────┐
                  │               │               │
                  ▼               ▼               ▼
          ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
          │ PostgreSQL   │ │    Redis     │ │ Search       │
          │ / MongoDB    │ │ Cache/Queue  │ │ ES / Algolia │
          └──────────────┘ └──────────────┘ └──────────────┘
                  │               │
                  └───────┬───────┘
                          ▼
                 ┌──────────────────┐
                 │ Events / Workers │
                 │ Queues / Streams │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │ Observability    │
                 │ Logs/Metrics/APM │
                 └──────────────────┘
```

The exact technology changes from project to project. The principles generally don't:

**clear boundaries → observable behavior → safe failure → measurable performance**

---

# Production Engineering Experience

### Backend & APIs

I have designed and maintained production APIs and services using:

`Node.js` · `TypeScript` · `JavaScript` · `Python` · `C#`

with:

`REST` · `GraphQL` · `WebSockets` · `event-driven workflows`

---

### Data & Search

Production experience with:

`PostgreSQL` · `MongoDB` · `Redis` · `Elasticsearch` · `Algolia`

including:

* Data modeling
* Query optimization
* Search architecture
* Caching
* Incremental indexing
* High-volume event data
* Database-backed APIs

---

### Cloud & Infrastructure

Worked across:

`AWS` · `GCP` · `Docker` · `Kubernetes` · `Terraform`

including production use of services and infrastructure around:

* EC2
* Lambda
* RDS
* S3
* SES
* Route53
* Elastic Beanstalk
* EKS
* Kinesis
* Redshift
* GCP Pub/Sub
* Cloud Functions
* BigQuery
* Cloud Storage

---

### CI/CD & Reliability

Experience building and operating delivery pipelines using:

`GitHub Actions` · `GitLab CI/CD` · `Jenkins` · `Docker`

with production observability through tools including:

`Honeycomb` · `New Relic` · `Segment` · `HotJar`

---

# Career Snapshot

### Morressier

**Senior Full-Stack Engineer**

Worked on a large-scale virtual conference, research, and publishing platform.

Key work included:

* Production backend and frontend features
* Search architecture and Algolia optimization
* SSO and external integrations
* Observability and analytics
* Technical mentoring
* Translating product requirements into scalable implementation
* Performance and reliability improvements

Notable integrations included **Google, ORCID, and ASCE**.

---

### MailMunch

**Senior Software Engineer**

Worked across product engineering, APIs, frontend systems, automated testing, and cloud infrastructure.

Key areas:

* Node.js
* React
* GraphQL
* AWS
* Cypress
* Docker
* CI/CD

---

### Revolving Games

**Software Engineer**

Worked on gaming platforms, backend infrastructure, real-time systems, analytics pipelines, internal tooling, and DevOps.

Projects included:

* Shop Heroes Legends
* Game operations tooling
* Fizz real-time messaging platform
* Internal dashboards

Infrastructure supported workloads including **50K+ concurrent players** and **1M+ analytics events/day**.

---

# Engineering Principles

### Design for failure

Networks fail. Services timeout. Events arrive twice. Dependencies become unavailable.

Reliable systems assume those things will eventually happen.

---

### Observability is part of the product

A system that cannot explain why it failed is significantly harder to operate.

Logs, traces, metrics, alerts, and useful operational context should be considered during design rather than after production incidents.

---

### Optimize from evidence

Measure before optimizing.

Production telemetry, profiling, query analysis, and actual usage patterns are more useful than assumptions.

---

### Keep boundaries explicit

Clear boundaries between infrastructure, persistence, application logic, and interfaces make systems easier to test and evolve.

---

### Prefer pragmatic architecture

The best architecture is rarely the one containing the most technologies.

I prefer the simplest design that provides the required reliability, scalability, and maintainability.

---

# Current Engineering Interests

I’m particularly interested in:

* Distributed backend architecture
* Event-driven systems
* High-throughput Node.js services
* AI-native application architecture
* PostgreSQL and data-intensive applications
* Kubernetes and cloud platforms
* Observability and reliability engineering
* Developer productivity and engineering tooling

---

# GitHub Activity

<p align="center">
  <img src="./github-metrics.svg" alt="Farhan Yaseen GitHub Metrics" width="100%">
</p>

---

# Let's Connect

I'm open to **Senior Backend, Senior Full-Stack, and Platform Engineering** opportunities where I can take meaningful technical ownership.

**Remote · Europe · Middle East**

<p align="center">

[**Portfolio**](https://farhanyaseen.netlify.app)
  •  
[**LinkedIn**](https://www.linkedin.com/in/farhanyaseen)
  •  
[**GitHub**](https://github.com/FarhanYaseen)
  •  
[**Email**](mailto:farhan.yaseen.se@gmail.com)

</p>

---

<div align="center">

**Build for production. Measure what matters. Keep the architecture understandable.**

</div>
