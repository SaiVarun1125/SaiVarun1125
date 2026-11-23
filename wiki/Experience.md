# Experience

## CFA Institute: Data Engineer & Enterprise Analytics
*Charlottesville, VA · Mar 2025 – Present*

**Scope:** marketing data subject matter expert owning ingestion, modeling and delivery.

- Own end-to-end ingestion of **10+ marketing and web-analytics SaaS sources** into Snowflake via Airflow DAGs with custom Python operators.
- Engineered an **event-driven pipeline for Adobe Analytics clickstream** (1,085 columns: hits, visits, sessions).
- Designed the trigger chain: Blob Storage upload → Event Grid → Azure Functions → Azure Data Factory + Airflow → Snowflake external stages → raw tables → dbt worker DAGs for Silver and Gold.
- Authored ingestion and extraction **catalogs in Confluence**: sources, upstream platforms, ingestion types, target schemas, SLAs, cadence, consumers and Snowflake role-based access.
- Implemented quality checks and cleaning rules in Airflow and dbt.
- Lead **LLM evaluation** across reasoning, development and routine tasks; standardized model-routing practices that reduce AI spend within regulatory constraints.
- Monitor pipeline health and the QA backlog; triage failures across Airflow, Azure Functions and dbt to protect SLAs.
- Deliver curated datasets to **Salesforce Data Cloud** and **Tableau**; maintain the reporting layer (Tableau and Power BI on Snowflake and Redshift models).

**Stack:** Snowflake, Airflow, dbt, Azure (Blob, Event Grid, Functions, Data Factory), Python, Tableau, Power BI, Confluence, Jira

## Molina Healthcare: Data Engineer
*Long Beach, CA · Jan 2023 – Mar 2025*

- Built and maintained ingestion on **S3, Glue, Kinesis, Lambda, EMR, Redshift** for high-volume healthcare and life-insurance data.
- Built **AI-assisted automation** for pipeline generation, data quality checks and documentation.
- Engineered distributed processing in **Databricks / PySpark** integrating PostgreSQL and MySQL.
- Implemented data accuracy and quality-control frameworks that reduced downstream defects.
- Ran Airflow workflows; troubleshot DAG failures and enforced quality checks.
- Loaded high-volume data to **Snowflake** powering Power BI dashboards; automated CI/CD with Jenkins and Git.
- Developed APIs over **RDS (SQL) and DynamoDB (NoSQL)** for real-time access.
- Partnered with data scientists on PySpark + Redshift datasets for predictive modeling.
- Wrote data dictionaries, runbooks and system diagrams; maintained monitoring and alerting.

**Stack:** AWS, Databricks, PySpark, Snowflake, Airflow, Jenkins, Power BI, PostgreSQL, MySQL, DynamoDB

## Syscon Solutions: Data Engineer
*Hyderabad, India · May 2021 – Jun 2022*

- Built real-time streaming pipelines on **AWS Kinesis** for event and financial data.
- Optimized **Glue + PySpark + EMR** pipelines, **reducing ingestion time by 30%**.
- Developed Spark big-data pipelines for scalable downstream analytics.
- Implemented validation rules and monitoring to improve accuracy, consistency and completeness.
- Defined **GDPR- and PII-aware** practices: masking, access controls, auditability.
- Orchestrated workflows with Databricks Jobs/Workflows and Airflow.
- Worked with Product Engineering and business stakeholders to define the data needed to launch products and measure adoption.

**Stack:** AWS Kinesis, Glue, EMR, PySpark, Databricks, Airflow
