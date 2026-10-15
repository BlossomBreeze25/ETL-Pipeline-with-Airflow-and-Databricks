# Airflow + Databricks ETL Infrastructure Stack

This repository provides an production execution template for orchestration workloads.

## Setup Instructions

1. **Start Environment**:
   Run `docker-compose up -d` in the project root directory to launch Airflow locally.
2. **Access Web Console**:
   Open `http://localhost:8080` (Username: `admin`, Password: `admin`).
3. **Configure Databricks Connection**:
   Navigate to **Admin -> Connections** inside the Airflow panel dashboard UI and configure `databricks_default` pointing to your Workspace Token credentials.
