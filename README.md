# Hi, I'm Karthik 👋

**Data Engineer | Streaming Systems | Kafka & Flink | Streaming & Event-Driven Systems | Applied Data Science**

I'm a Master's graduate in Information Technology with a focus on Data Analytics, currently building toward Data Engineering and Analytics Engineering roles.

I enjoy working on problems where data has to be more than technically correct — it has to be reliable, explainable, observable, and useful.

My recent work spans real-time streaming systems, event-driven data pipelines, schema governance, tracking-data analytics, feature engineering, and applied machine learning. I prefer building projects around realistic engineering and analytical problems rather than isolated tutorials, and I document the decisions, failures, debugging, and validation behind the final result.

---

### 🔭 Featured Project

**[Streaming Data Platform](https://github.com/Karthik070398/streaming-data-platform)**

An end-to-end streaming platform inspired by production engineering patterns used across large-scale technology companies.

Built around:

- Config-driven Kafka ingestion with source/sink connector patterns
- Schema governance using Confluent Schema Registry and Avro
- Idempotent, offset-tracked consumers
- Apache Flink windowed aggregation with event-time processing and watermarks
- Prometheus + Grafana observability
- Docker Compose-based local infrastructure

The project also documents real debugging work, including a distributed watermark-stalling issue caused by Kafka partitioning and Flink parallelism.

See PROGRESS.md in the repository for the engineering decisions, failures, fixes, and lessons learned throughout the build.

---
**🏈 NFL Big Data Bowl 2027 — Open Track Submission**

Finding the Players the Stopwatch Misses

Built an end-to-end sports tracking analytics pipeline to investigate whether NFL Combine wide-receiver route mechanics predict future NFL separation beyond traditional athletic testing.

The project includes:

- Processing 10 Hz NFL Combine tracking data
- Engineering speed, acceleration, braking, path-efficiency, turn-angle, and post-break movement features
- Analyzing 107 WR prospects across 1,079 Combine route attempts
- Normalizing movement by Combine year and drill
- Building an out-of-fold NFL Separation Over Expected target across 38,030 qualifying route observations
- Comparing traditional Combine, movement-only, and combined models with nested repeated cross-validation
- Testing route-specific Combine-to-NFL translation as a robustness analysis

The final result was a useful null finding: the current movement representation did not provide reliable incremental prediction beyond traditional Combine measurements.

Rather than tuning the analysis until the original hypothesis appeared favorable, I kept the held-out result and documented its limitations and future research directions.

**Status: Submitted to the NFL Big Data Bowl 2027 — Open Track.**
---

### 🧰 Tech I work with

**Streaming & Messaging:** Apache Kafka · Apache Flink · Confluent Schema Registry · Avro

**Languages & Analysis :** Python · SQL · pandas · NumPy · scikit-learn

**Data Engineering** ETL/ELT · Data Modeling · Event-Driven Architecture · REST APIs

**Infrastructure:** Docker · Docker Compose · Git

**Observability:** Prometheus · Grafana

**Data & Analytics:** PostgreSQL · MongoDB · Jupyter · Feature Engineering · Predictive Modeling · Time-Series / Tracking Data

---

### 🌱 Currently Building Toward

I'm continuing to deepen my experience with distributed data systems and production-oriented data engineering, including:

- orchestration and workflow management;
- data lakes and lakehouse architecture;
- change data capture;
- scalable batch and streaming pipelines;
- reliability, observability, and data-quality patterns.

My goal is to keep building systems that resemble real production problems rather than isolated demonstrations.

---

### 📫 Connect with me

[LinkedIn](https://www.linkedin.com/in/karthik-venugopal0703) 

📍 Columbus, Ohio · Open to relocation

