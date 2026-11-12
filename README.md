### Hello!

I'm Marcia, data professional with 5 years of experience across data science, data engineering and AI. I build data pipelines and the AI applications on top of them, such as RAG and agents.

I recently completed an international Master's in Software Engineering. While working at a data consultancy in Finland, I built the data and AI layer for a sustainability reporting team: pipelines that replaced manual data collection and brought supplier data into one structure for reporting, and an AI assistant that finds metrics in unstructured documents. The work resulted in my master's thesis on sustainability data interoperability.

**What I work on:**

- **Data pipelines** — automated ingestion and transformation, with data quality checks built in.
- **AI applications** — RAG and agents, evaluated for accuracy and cost against the existing process, and traced in production.
- **Agents** — agents that combine several tools over MCP, such as search and document retrieval, to answer multi-step questions.
- **AI-assisted development** — building with Claude Code: subagents, custom commands, hooks and MCP connections, with review and tests in the workflow.

**Education:** Master's in Software Engineering for the Green Deal (Italy, Finland, Netherlands) · BSc Software Engineering · BSc Environmental Engineering · Specialization in Artificial Intelligence

Reach me at *marcia.rrdg@gmail.com* or on [LinkedIn](https://www.linkedin.com/in/rodriguesmarciar/).

---

### Tech Toolbox

- **Pipelines:** Python · SQL · PySpark · Airflow · dbt · Kafka · Flink
- **Storage:** PostgreSQL · MySQL · MongoDB · DuckDB · Delta Lake · Apache Iceberg · Parquet · S3 / MinIO
- **Cloud & DevOps:** AWS (S3, EC2, Lambda) · Azure · Databricks · Docker · Terraform · GitHub Actions (CI/CD)
- **Quality & Observability:** pytest · dbt tests · ruff · OpenTelemetry · Prometheus · Grafana · Langfuse
- **LLMs & Agents:** RAG · LangGraph · LlamaIndex · MCP · pgvector · FastAPI · Azure OpenAI · Claude Code
- **Machine Learning:** Scikit-learn · PyTorch · TensorFlow · Keras
- **BI & Visualization:** Metabase · Streamlit · Superset

---

### Selected Projects

- **Knowledge-base assistant (private)** — RAG over a Confluence documentation corpus, with source citations, HTML normalization and PII redaction. Agents combine search, change tracking and page retrieval over MCP to answer multi-step questions. Retrieval is scored against a labelled question set (TREC qrels, ir-measures).

- **[Agent observability](https://github.com/mrcrdg/claude-telemetry)** — a self-hosted OpenTelemetry → Prometheus → Grafana stack that tracks how Claude Code behaves: token consumption, cost and session activity, entirely on localhost.

- **[Medallion lakehouse](https://github.com/mrcrdg/standard-lakehouse)** — bronze → silver → gold over a Stack Exchange XML dump. PySpark handles ingestion and everything downstream is SQL, on Delta Lake/Iceberg, orchestrated with Airflow and dbt Core. Tested and linted, with ADRs for the design decisions.

- **[Streaming & event-driven pipeline](https://github.com/mrcrdg/real-time-data-pipeline)** — clickstream events through Kafka, filtered in Flink, landed as Iceberg tables on MinIO, queried with Trino and charted in Superset. Runs end to end on one machine.

- **[Semantic layer](https://github.com/mrcrdg/semantic-layer-duckdb-demo)** — metrics defined once in YAML and queried by name over 20M rows of NYC taxi data, with DuckDB, Ibis and dbt and no warehouse underneath.

- **[Orchestrated Databricks workloads](https://github.com/mrcrdg/dataflow-databricks-airflow-3.0)** — PySpark pipelines on Databricks, orchestrated with Airflow 3.0.

- **Databricks Certified Data Engineer Associate** (in progress)

---
<!-- <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mrcrdg/mrcrdg/output/snake-dark.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/mrcrdg/mrcrdg/output/snake.svg">
</picture> -->
