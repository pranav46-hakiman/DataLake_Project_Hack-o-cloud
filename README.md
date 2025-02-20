# DataLake_Project_Hack-o-cloud
Intelligent Data Lake with Real-Time Analytics


Phase 1: Cloud Infrastructure & Data Storage (Sprints 1-3)

----> Cloud Provider:

1.Azure (50%): Azure Data Lake Storage (ADLS) Gen2
2.Hybrid Option: AWS S3 (for additional storage redundancy)

----> Infrastructure as Code (IaC):

Azure Bicep + Terraform (for flexible provisioning)

----> Security & IAM:

1.Azure Active Directory (Azure AD) (for authentication)
2.HashiCorp Vault (for secrets management)

_________________________________________________________________________________

Phase 2: Data Ingestion & Processing (Sprints 4-5)

----> Batch & Real-Time Data Ingestion:

1.Azure Event Hubs (for real-time data ingestion)
2.Apache Kafka (Self-hosted or Confluent Cloud) (for streaming & pub-sub architecture)

----> Data Processing & ETL:

1.Azure Synapse Analytics (for SQL-based data warehousing)
2.Azure Databricks (Apache Spark) (for large-scale ETL processing)

----> Querying & Analytics:

1.Azure Synapse Analytics + PrestoDB (for fast querying)

_________________________________________________________________________________


Phase 3: DevOps & Automation (Sprints 6-7)

----> CI/CD Pipeline Tools:

1.Azure DevOps Pipelines (for native Azure deployments)
2.GitHub Actions (for Git-based automation)
3.Jenkins (for managing hybrid CI/CD workflows)

----> Workflow Orchestration:

1.Apache Airflow (for scheduling ETL jobs)
2.Azure Logic Apps (for automated workflows)

----> Containerization & Orchestration:

1.Docker (for packaging ML models & apps)
2.Kubernetes (AKS + OpenShift for multi-cloud orchestration)

----> Database Migration & Versioning:

1.Liquibase / Flyway (for schema versioning)

_________________________________________________________________________________


