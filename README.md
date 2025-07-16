# Retail-Demand-Forecasting-Pipeline
A machine learning pipeline built on Databricks to predict daily item-level retail sales using AutoML, Feature Store, and Delta Lake on AWS.

## Tech Stack
- Databricks on AWS (Workspaces, Jobs, DLT, Unity Catalog, MLflow)
- Delta Lake (Bronze → Silver → Gold architecture)
- AWS S3 (raw data)
- AutoML, Hyperopt, MLflow Tracking & Registry
- Feature Store, DBX Workflows

## Team Members
- Era Ismaili (Data Scientist, ML Engineer)
- Leart Rama (Data Scientist, ML Engineer)

##  Business Goal
Forecast item-level demand to improve inventory decisions and avoid overstock/understock situations.

##  Project Structure
- `/notebooks/` → Feature engineering, modeling, evaluation
- `/pipelines/` → DLT pipeline code (Bronze → Silver)
- `/jobs/` → DBX job configs and automation
- `/docs/` → Architecture diagrams, Agile plan, presentations

## Output
- Registered ML model (MLflow)
- Gold Delta Tables in Unity Catalog
- Scheduled batch scoring & retraining workflows
- Final slide deck + architecture

##  Agile Workflow
Project is delivered in 3 weekly sprints, following Agile methodology (see `/docs/agile.md` for full breakdown).
