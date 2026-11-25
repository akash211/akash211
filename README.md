# Akash Kumar

### Technical Lead · Data Engineering & AI Platforms

I build and operate production data platforms: time-series infrastructure, market-data ingestion, analytics applications and AI automation, with a focus on reliability, scale and operational ownership.

## About me

- 14+ years across investment management, e-commerce, analytics and automation
- Technical Lead at Nuware Systems, supporting AllianceBernstein Multi-Asset Solutions
- Owner of a 300+ TB OneTick time-series fleet: 5 servers, 26 processes, 100–140 GB/day of global market data
- Re-architected the TCA dashboard onto DuckDB for zero-downtime refresh and sub-second queries
- Delivered 60+ FTE equivalents in savings through Python automation at Amazon
- Microsoft-certified: Fabric Data Engineer (DP-700), Power BI (PL-300), Azure Data Scientist (DP-100), Azure DBA (DP-300), Cosmos DB AI Developer (DP-420)

## What I build

| Area | Focus |
|---|---|
| Data platforms | Batch ingestion, ETL/ELT, data quality, time-series, analytical storage |
| Engineering | Python, SQL, FastAPI, Dash, Streamlit, Pandas, pytest, REST APIs |
| Orchestration | Apache Airflow, monitoring, alerting, failure recovery |
| Cloud & data | Azure (ADF, Fabric), Snowflake, AWS S3, Redshift, DuckDB, SQL Server, Parquet |
| Infrastructure | Linux, Docker, CI/CD, GitHub Actions, Ansible, Terraform (homelab) |
| AI systems | Tool-using agents, MCP servers, LLM automation, RAG concepts, evaluation |

## Selected production impact

### 300+ TB market-data platform

- Five OneTick servers (4 production, 1 QA), 26 processes on 64-core nodes up to 1 TB RAM.
- 300+ TB tick history, including 130+ TB of 30-year US TAQ.
- 100–140 GB/day ingestion across US, LSE, Shanghai and Shenzhen exchanges: trades, quotes, order book, NBBO, FX, futures.
- Bloomberg BPIPE real-time feeds generating 1-, 5-minute and volume bars.

### Platform modernization

- Re-architected mas-tca-dashboard from a memory-bound in-process model to DuckDB-backed serving with decoupled refresh.
- Eliminated daily restarts and held sub-second queries for trading-desk analysts.
- Led three production Python modernisations (3.7 to 3.11, 3.8 to 3.12).
- Built CI/CD sync across a five-server fleet; migrated DQ baselines from 70+ JSON files to SQLite.

### AI automation

- Tick-data DQ monitoring agent: LLM tool calling + FastMCP + AWS S3, triages missing tick data against exchange holidays and source availability.
- OneTick MCP server: exposes tick coverage, DQ results and symbol metadata as tools for coding assistants and internal agents.

### Earlier impact

- Amazon: Python/VBA automation delivering 60+ FTE savings; 20+ Tableau dashboards; NLP engine correcting 84%+ of non-compliant product titles.
- Tolexo: Six Sigma DMAIC programme moved dispatch from 90% within 72 hours to 95% within 28 hours.
- Snapdeal: routing and network redesign for 9,000+ daily orders, cutting allocation-to-dispatch from 4 days to 1.5 days.
- Jabong: vendor payment turnaround from 15 days to 7 days.

## Certifications

- Microsoft Certified: Fabric Data Engineer Associate (DP-700), 2025
- Microsoft Certified: Power BI Data Analyst Associate (PL-300), 2024
- Microsoft Certified: Azure Data Scientist Associate (DP-100), 2024
- Microsoft Certified: Azure Database Administrator Associate (DP-300), 2023
- Microsoft Certified: Azure Cosmos DB AI Developer Associate (DP-420), 2023
- Astronomer Certified: Apache Airflow 2 Fundamentals, 2024
- Six Sigma Green Belt — Indian Statistical Institute, 2016

## Education

- Post Graduate Program in Business Analysis (PGP-BA), Purdue University (online), 2022
- B.Tech, Electronics & Communication Engineering, Uttarakhand Technical University; Kumaon Engineering College, Almora, 2007–2011

## Current learning focus

Kafka and event-driven architecture · advanced PySpark · Delta Lake and Apache Iceberg · Kubernetes and Helm · production RAG and agent evaluation.

These are active learning and portfolio areas, not claims of production ownership.

## Connect

- LinkedIn: https://www.linkedin.com/in/akash211/
- Email: akash211@gmail.com

If you are building data platforms, market-data systems or production AI automation, I would be happy to connect.
