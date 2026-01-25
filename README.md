# Azure Data Engineering & Analytics Skills

This repository documents hands-on experience with Azure Data Services, SQL Server Management Studio (SSMS), Azure Data Factory (ADF), Azure Synapse, Azure Data Lake, and Power BI. It includes practical implementations of data ingestion, transformation, and analytics using modern cloud architectures such as the Medallion Architecture.
## Skills Demonstrated
### 1. Azure Resource Setup

Created a Resource Group to manage all Azure resources.

Provisioned:

Azure Data Lake Storage (ADLS Gen2)

Azure Databricks

Azure Synapse Analytics

Azure Key Vault

Registered Azure Synapse and other resource providers to ensure quotas for compute resources.

Managed compute availability for Databricks by registering resource providers and leveraging Azure student subscriptions when needed.

### 2. Azure Data Factory (ADF) – ETL / ELT

Designed pipelines for moving and transforming data from on-premises systems to Azure Data Lake.

Configured Self-Hosted Integration Runtime (SHIR) for secure access to on-prem data.

Implemented iterative ingestion pipelines using Lookup & ForEach activities to process multiple tables efficiently.

Stored data in Parquet format for columnar storage and optimized querying in Azure Synapse.

### 3. Azure Synapse & Databricks

Leveraged Synapse Analytics for data modeling and analytics on ingested datasets.

Used Databricks for data transformation, cleansing, and preparation for analytics.

Ensured seamless integration between ADLS, Databricks, and Synapse for end-to-end data processing.

### 4. Azure Key Vault

Configured Key Vault to securely manage credentials and secrets.

Integrated Key Vault with ADF and Databricks to ensure secure and automated pipeline execution.

### 5. Power BI

Connected Power BI to Azure Synapse and Databricks for interactive dashboards.

Built visualizations from transformed data for business reporting and analytics.

### 6. Data Architecture – Medallion (Bronze/Silver/Gold)

Implemented Medallion Architecture for structured data processing:

Layer	        Purpose
Bronze	      Raw data ingestion from source systems into ADLS (minimal transformation).
Silver	      Cleansed and enriched data ready for analytics (joins, filters, transformations).
Gold	        Aggregated, business-ready datasets for reporting and Power BI dashboards.

Ensured scalable and modular pipelines for iterative data ingestion and transformation.

### 7. Key Learnings & Challenges

Managed compute quota issues in Azure subscriptions by registering resource providers and using student accounts for experimentation.

Resolved SHIR connectivity issues by reinstalling and reconfiguring for secure pipelines.

Azure Services: Data Factory, Synapse Analytics, Databricks, Key Vault, Data Lake Storage Gen2

Languages & Frameworks: Python (Databricks notebooks), SQL (conceptual knowledge)

Data Formats: Parquet, CSV

Analytics: Power BI

Architecture: Medallion Architecture (Bronze/Silver/Gold)

This README demonstrates strong Azure cloud skills, pipeline design, and data transformation expertise while emphasizing best practices in cloud architecture, security, and analytics.

Gained hands-on experience with end-to-end cloud ETL, secure secret management, and analytics workflow orchestration.

### 8. Tools & Technologies
Azure Services: Data Factory, Synapse Analytics, Databricks, Key Vault, Data Lake Storage Gen2

Languages & Frameworks: Python (Databricks notebooks), SQL (conceptual knowledge)

Data Formats: Parquet, CSV

Analytics: Power BI

Architecture: Medallion Architecture (Bronze/Silver/Gold)

# This README demonstrates strong Azure cloud skills, pipeline design, and data transformation expertise while emphasizing best practices in cloud architecture, security, and analytics.
