### Hello!

Welcome to my GitHub profile. My name is Marcia and here you'll find my studies and projects.

**About me:**

**Data Scientist** moving into **Data engineering** — 5 years across the data lifecycle: ingestion, modeling, transformation, deployment, and monitoring. I started in data science and applied ML, and I now build the pipelines and platforms underneath them.

Recently completed the Erasmus Mundus **Master's in Software Engineering** (SE4GD), a joint degree across Italy, Finland, and the Netherlands, concluding with thesis research on data interoperability across systems and organisations, conducted with a data consultancy in Finland.

I hold a **Bachelor's degree in Software Engineering** and a specialization in Artificial Intelligence, both focused on industrial and applied technologies.

Day to day I work in **Python, SQL, Airflow, dbt, Docker, Git, Linux/bash and CI** — plus in-pipeline testing and data quality, and monitoring.

Documenting: **dbt docs** for lineage, **ADRs** for decisions, **Mermaid** for architecture, **AGENTS.md** for context.

Reach me at *marcia.rrdg@gmail.com* or connect on [LinkedIn](https://www.linkedin.com/in/rodriguesmarciar/).
— Always happy to connect, exchange ideas, or collaborate.

---

### Tech Toolbox

- **Pipelines:** Python · SQL · PySpark · Airflow · dbt · Kafka · Flink
- **Storage:** PostgreSQL · MySQL · MongoDB · DuckDB · Delta Lake · Apache Iceberg · Parquet · S3 / MinIO
- **Cloud & DevOps:** AWS (S3, EC2, Lambda)· Azure · Databricks · Docker · Terraform · GitHub Actions (CI/CD)
- **Quality & Observability:** pytest · dbt tests · ruff · OpenTelemetry · Prometheus · Grafana
- **AI & ML:** Scikit-learn · TensorFlow · PyTorch · Keras · RAG pipelines · Claude Code
- **BI & Visualization:** Metabase · Streamlit

---

### Selected Projects
 
- **[Agent observability](https://github.com/mrcrdg/claude-telemetry)** — a self-hosted OpenTelemetry → Prometheus → Grafana stack that tracks how Claude Code actually behaves: token consumption, cost, and session activity, entirely on localhost.
  
- **[Medallion lakehouse ](https://github.com/mrcrdg/standard-lakehouse)** — bronze → silver → gold over a Stack Exchange XML dump. PySpark handles ingestion, everything downstream is SQL. Delta Lake/Iceberg table formats, Spark (PySpark), orchestration with Airflow and dbt Core, tested and linted, with ADRs for the design calls.
 
- **[Streaming & event-driven pipeline](https://github.com/mrcrdg/real-time-data-pipeline)** — clickstream events through Kafka, filtered in Flink, landed as Iceberg tables on MinIO, queried with Trino and charted in Superset. Runs end to end on one machine.
  
- **[Semantic layer](https://github.com/mrcrdg/semantic-layer-duckdb-demo)** —  metrics defined once in YAML and queried by name, over 20M rows of NYC taxi data. DuckDB and Ibis, no warehouse underneath, modeling the layer analysts query, without a warehouse underneath · DuckDB · dbt

- **Retrieval over a documentation corpus (private)** — a RAG pipeline over Confluence with citations, HTML normalization, PII redaction, and a measured evaluation set scored with TREC qrels and ir-measures. The evaluation harness is the point: retrieval you can't measure is retrieval you can't improve.
    
- **[Orchestrated Databricks workloads](https://github.com/mrcrdg/dataflow-databricks-airflow-3.0)** — pipelines on Airflow 3.0 · Databricks · PySpark · Airflow
  
- **Databricks Certified Data Engineer Associate** (in progress)

---
<!-- <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mrcrdg/mrcrdg/output/snake-dark.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/mrcrdg/mrcrdg/output/snake.svg">
</picture> -->
