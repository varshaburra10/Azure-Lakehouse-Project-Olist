Kaggle Olist CSVs (6 files)
        │
        ▼
  ADLS Gen2 (raw/)
        │
        ▼
Azure Data Factory ──── ForEach loop 
        │
        ▼
  Bronze Layer (Delta) ── raw, schema-on-read, no transformations
        │
        ▼
Azure Databricks (PySpark notebooks)
        │
        ├── type casting · null handling · deduplication
        ▼
  Silver Layer (Delta) ── cleaned, typed, MERGE upsert
        │
        ▼
Azure Databricks (PySpark aggregations)
        │
        ├── revenue per seller · delivery SLA · monthly trends
        ▼
  Gold Layer (Delta) ── business-ready, BI-consumable
        │
        ▼
Azure Synapse Analytics ── external tables → SQL queries → dashboards
