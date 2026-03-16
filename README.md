<div align="center">

# 🚀 Denis Turkovic — Data Engineering Learning Roadmap
### Veljača 2026 → Ožujak 2027

[![Plan Status](https://img.shields.io/badge/Status-In%20Progress-brightgreen?style=for-the-badge)](https://github.com/denisturkovic1991/DenisDataPLAN)
[![Current Phase](https://img.shields.io/badge/Phase-Q1%20Foundations-blue?style=for-the-badge)](https://github.com/denisturkovic1991/DenisDataPLAN)
[![Target Role](https://img.shields.io/badge/Target-Analytics%20%2F%20Data%20Engineer-purple?style=for-the-badge)](https://github.com/denisturkovic1991/DenisDataPLAN)

<br/>

*A structured, project-driven journey from SQL fundamentals to cloud-native Data Engineering — anchored by a single evolving real-world project.*

</div>

---

## 🌱 The Core Project: EcoDrive AI

> Every skill in this roadmap is applied directly to one evolving project — not isolated exercises.

**EcoDrive AI** simulates an intelligent fleet management platform for electric vehicles (EVs). The system ingests telemetry data from a fleet of EVs, optimizes charging schedules, predicts energy consumption, and provides actionable dashboards for fleet managers.

**The project evolves with every quarter:**

```
Q1  →  SQL schema + Python ETL + Docker
Q2  →  dbt transformations + Power BI dashboard
Q3  →  Apache Airflow orchestration + Azure cloud migration
Q4  →  Azure Databricks + Spark + Delta Lake
Q5  →  Microsoft Fabric + DP-600 certification
```

📌 **[View EcoDrive AI Repository →] ([https://github.com/denisturkovic1991](https://github.com/denisturkovic1991/EcoDrive-AI))**

---

## 📅 Full Roadmap Overview

```
Feb,Mar 2026   Mar 2026    Apr 2026    May 2026    Jun 2026    Jul 2026
   │            │           │           │           │           │
[Git+SQL]  [Docker+SQL] [Python ETL] [Python DE] [dbt Bootcamp][Power BI]
   Q1 ─────────────────────── Q2 ──────────────────────────────────
   
Aug 2026    Sep 2026    Oct 2026    Nov 2026    Dec 2026    Jan-Mar 2027
   │            │           │           │           │           │
[Airflow]  [ADF+Azure]  [Databricks] [DP-900]  [Fabric]   [Portfolio]
   Q3 ─────────────────────── Q4 ─────────────────── Q5 ──────────
```

---

## 📦 Q1 — Foundations (Veljača – Travanj 2026)

> **Goal:** Build a solid, reproducible foundation. By end of April: a Dockerized Python ETL pipeline with a proper SQL schema, all on GitHub from day one.

| Month | Focus | Key Deliverable |
|-------|-------|-----------------|
| **Veljača** | Git & GitHub + SQL fundamentals (SELECT, JOINs, CTEs, Window Functions) | EcoDrive SQL schema v1 + 20+ analytics queries on GitHub |
| **Ožujak** | SQL data modelling (normalization, indexes) + Docker & Docker Compose | Dockerized PostgreSQL dev environment for EcoDrive |
| **Travanj** | Python for DE (Pandas, psycopg2, logging, error handling) | EcoDrive Python ETL pipeline (Extract → Transform → Load) |

### 🛠 Tech Stack — Q1
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

### 📚 Courses — Q1 & Q2
| Course | Platform | Instructor | Status |
|--------|----------|------------|--------|

| Microsoft Excel: Business Intelligence w/ Power Query & DAX | Maven Analytics | ✅ Done |
| SQL & PostgreSQL: The Complete Developer's Guide | Udemy | Stephen Grider | 🔄 In Progress |
| The Git & GitHub Bootcamp | Udemy | Colt Steele | 🔄 In Progress |
| Docker Mastery: with Kubernetes + Swarm | Udemy | Bret Fisher | ⏳ Planned |
| Python Data Analysis & Visualization Masterclass | Udemy | Colt Steele | ⏳ Planned |

### ✅ Q1 Milestone Checklist
- [x] Power Query & DAX |
- [ ] Git & GitHub Bootcamp — 100% complete
- [ ] SQL (Grider) — 100% complete
- [ ] Docker Mastery — 80%+ complete
- [ ] Python foundations solid
- [ ] EcoDrive: SQL schema + Docker Compose + Python ETL on GitHub
- [ ] 60+ GitHub commits

---

## 🔧 Q2 — Analytics Engineering (Svibanj – Srpanj 2026)

> **Goal:** Transform the raw ETL pipeline into a professional Analytics Engineering workflow. Every SQL transformation is versioned, tested, and documented.

| Month | Focus | Key Deliverable |
|-------|-------|-----------------|
| **Svibanj** | Python advanced (pytest, API ingestion, CI/CD) | EcoDrive: real OpenChargeMap EU data + GitHub Actions CI |
| **Lipanj** | dbt Bootcamp — complete month dedicated to dbt | EcoDrive: full dbt project (staging → intermediate → marts) |
| **Srpanj** | Power BI Desktop + DAX basics | EcoDrive: 3-page Fleet Manager Dashboard |

### 🏗 EcoDrive dbt Architecture
```
sources (PostgreSQL raw)
  └── staging/       stg_trips, stg_vehicles, stg_charging_events
        └── intermediate/   int_trip_metrics, int_charging_sessions
              └── marts/    fct_fleet_daily, dim_vehicles, dim_stations
                    └── Power BI reporting layer
```

### 🛠 Tech Stack — Q2
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

### 📚 Courses — Q2
| Course | Platform | Instructor | Status |
|--------|----------|------------|--------|
| The Complete dbt Bootcamp | Udemy | Zoltan Toth | ⏳ Planned |
| Microsoft Power BI Desktop (Maven Analytics) | Udemy | Maven Analytics | ⏳ Planned |
| Data Engineering Project: SQL, Python, Airflow, Docker | Udemy | Various | ⏳ Planned |

### ✅ Q2 Milestone Checklist
- [ ] Python Masterclass 100% + pytest test suite
- [ ] dbt Bootcamp 100% complete
- [ ] Power BI (Maven) 70%+
- [ ] EcoDrive: 10+ dbt models, 15+ tests, SCD2 snapshot
- [ ] dbt docs live on GitHub Pages
- [ ] GitHub Actions CI: pytest + dbt test on every push
- [ ] 130+ total GitHub commits
- [ ] EcoDrive Fleet Dashboard (Power BI) completed

---

## ✈️ Q3 — Orchestration & Cloud (Kolovoz – Listopad 2026)

> **Goal:** Move from manual local execution to fully automated cloud-hosted pipelines. EcoDrive runs itself.

| Month | Focus | Key Deliverable |
|-------|-------|-----------------|
| **Kolovoz** | Apache Airflow 3 — DAGs, Sensors, TaskFlow, dbt integration | EcoDrive: 3 production Airflow DAGs (hourly auto-run) |
| **Rujan** | DP-900 certification + Azure Data Factory + ADLS Gen2 | EcoDrive: Medallion architecture in Azure (Bronze/Silver/Gold) |
| **Listopad** | Azure Databricks + PySpark + Delta Lake | EcoDrive: complete cloud data lakehouse architecture |

### ☁️ EcoDrive Azure Architecture
```
[OpenChargeMap API]──┐
[EV Telemetry Gen]───┤
                     ▼
              Azure Data Factory
                  (Orchestration)
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       Bronze      Silver      Gold
      (Raw JSON)  (Parquet)  (Delta)
       ADLS Gen2   ADLS Gen2   ADLS Gen2
                               │
                    ┌──────────┘
                    ▼
            Azure Databricks
             (PySpark, Delta)
                    │
                    ▼
             Azure SQL Database
                    │
                    ▼
               Power BI
```

### 🛠 Tech Stack — Q3
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=flat)

### 📚 Courses — Q3
| Course | Platform | Instructor | Status |
|--------|----------|------------|--------|
| The Complete Hands-On Introduction to Apache Airflow 3 | Udemy | Marc Lamberti | ⏳ Planned |
| Azure Data Factory For Data Engineers — Covid19 Project | Udemy | Ramesh Retnasamy | ⏳ Planned |
| Azure Databricks & Spark | Udemy | Various | ⏳ Planned |

### 🏆 Certifications — Q3
| Cert | Provider | Target Date | Status |
|------|----------|-------------|--------|
| DP-900: Microsoft Azure Data Fundamentals | Microsoft | Rujan 2026 | ⏳ Planned |

### ✅ Q3 Milestone Checklist
- [ ] Airflow 3 (Lamberti) 100% complete
- [ ] DP-900 certification passed ✓
- [ ] Azure Data Factory (Retnasamy) 100% complete
- [ ] ADLS Gen2 Medallion architecture deployed
- [ ] EcoDrive runs in two modes: local (Docker+Airflow) and cloud (ADF+Azure)
- [ ] Databricks Gold Delta Layer live
- [ ] Loom 5-min video walkthrough in README
- [ ] 200+ total GitHub commits

---

## 🏔 Q4 — Scale & Certify (Studeni 2026 – Siječanj 2027)

> **Goal:** DP-203 prep, production-grade Spark patterns, enterprise data lakehouse finalization.

| Month | Focus | Key Deliverable |
|-------|-------|-----------------|
| **Studeni** | DP-203 Azure Data Engineer exam prep | Exam practice + EcoDrive Azure refinement |
| **Prosinac** | Databricks advanced + Spark optimization | EcoDrive: optimized Delta Lake with ZORDER, Z-statistics |
| **Siječanj** | Project integration sprint — dbt + Airflow + Azure | EcoDrive v4: fully integrated, documented, production-ready |

### 🏆 Certifications — Q4
| Cert | Provider | Target Date | Status |
|------|----------|-------------|--------|
| DP-203: Azure Data Engineer Associate | Microsoft | Prosinac 2026 | ⏳ Planned |

---

## 🎯 Q5 — Portfolio & Launch (Veljača – Ožujak 2027)

> **Goal:** DP-600 certification + master portfolio finalization + active job search.

| Month | Focus | Key Deliverable |
|-------|-------|-----------------|
| **Veljača** | DP-600: Microsoft Fabric | Fabric certification — #1 most demanded cert in modern DE teams |
| **Ožujak** | Portfolio polish + CV + LinkedIn + job applications | First interviews |

### 🏆 Certifications — Q5
| Cert | Provider | Target Date | Status |
|------|----------|-------------|--------|
| DP-600: Microsoft Fabric Analytics Engineer | Microsoft | Veljača 2027 | ⏳ Planned |

---

## 🧰 Complete Tech Stack by End of Roadmap

### Core DE Tools
![SQL](https://img.shields.io/badge/SQL-Advanced-4169E1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-Intermediate-3776AB?style=flat&logo=python&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-Analytics%20Engineering-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-Orchestration-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat&logo=git&logoColor=white)

### Cloud & Big Data
![Azure](https://img.shields.io/badge/Microsoft%20Azure-Cloud-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-ETL-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Azure%20Databricks-Spark-FF3621?style=flat&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-Big%20Data-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-Platform-0078D4?style=flat&logo=microsoft&logoColor=white)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat&logo=postgresql&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-Format-003366?style=flat)
![Azure Data Lake](https://img.shields.io/badge/ADLS%20Gen2-Storage-0078D4?style=flat&logo=microsoftazure&logoColor=white)

### Visualization & Analytics
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## 🏆 Certification Roadmap

```
Rujan 2026           Prosinac 2026          Veljača 2027
     │                     │                     │
  DP-900               DP-203                 DP-600
Azure Data           Azure Data            Microsoft Fabric
Fundamentals         Engineer            Analytics Engineer
(Fundamentals)      (Associate)             (Associate)
```

---

## 📊 Progress Tracker

| Quarter | Period | Status | Courses | Project Milestone |
|---------|--------|--------|---------|-------------------|
| Q1 | Feb–Apr 2026 | 🔄 In Progress | Git, SQL, Docker, Python | EcoDrive: SQL + Docker + Python ETL |
| Q2 | May–Jul 2026 | ⏳ Planned | dbt Bootcamp, Power BI | EcoDrive: dbt + Power BI Dashboard |
| Q3 | Aug–Oct 2026 | ⏳ Planned | Airflow, ADF, Databricks | EcoDrive: Cloud Lakehouse |
| Q4 | Nov 2026–Jan 2027 | ⏳ Planned | Spark advanced, DP-203 | EcoDrive: Production-ready |
| Q5 | Feb–Mar 2027 | ⏳ Planned | Microsoft Fabric, DP-600 | Master Portfolio + Job Search |

---

## 💡 Learning Philosophy

This roadmap is built around three principles observed in real-world DE teams at global companies:

**1. Project-first, not course-first.**
Every tool is learned in the context of a real project (EcoDrive AI). Theory without application is forgotten within weeks.

**2. Git from day one.**
The entire learning journey is version-controlled. Every week of study leaves a commit trail — the GitHub contribution graph is itself a portfolio piece.

**3. Depth before breadth.**
Rather than touching 20 tools superficially, this plan goes deep on the tools that matter: SQL, Python, dbt, Airflow, and the Azure ecosystem. These cover 90%+ of real DE job requirements in the EU market.

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Denis%20Turkovic-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/denisturkovic)
[![GitHub](https://img.shields.io/badge/GitHub-denisturkovic1991-181717?style=flat&logo=github&logoColor=white)](https://github.com/denisturkovic1991)

---

<div align="center">


**"The best time to start was yesterday. The second best time is today."**

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=denisturkovic1991.DenisDataPLAN)

</div>
