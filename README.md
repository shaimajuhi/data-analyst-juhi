# Data-Analyst-Juhi Ali
# 📊 Project 1: Descriptive Analysis
<img width="680" alt="project1-ss" src="https://github.com/user-attachments/assets/d663e91d-4a0b-4db2-a2bf-cf8a221154e7" />

# 💧 Operating Permit for Water Quality  
## 📊 Descriptive Analysis Using AWS Data Analytic Platform (DAP) – City of Vancouver

---

## 📘 Project Description

This project focuses on the **design and implementation** of a **Data Analytic Platform (DAP)** using **Amazon Web Services (AWS)** to perform **descriptive analysis** on the **Operating Permit dataset related to water quality** from the City of Vancouver. The platform supports structured data ingestion, transformation, and querying to generate actionable insights for city officials, water quality teams, and compliance departments.

---

## 🎯 Project Objective

- Design a **cloud-based data analytics platform** using AWS services  
- Ingest and profile the **Operating Permit water quality dataset**  
- Apply descriptive analytics to summarize key metrics  
- Enable serverless, scalable analysis and reporting

# AWS-Based Data Analytic Platform

## 📌 Project Description
This project designs and implements a **cloud-based Data Analytic Platform (DAP)** using AWS services. The platform performs **descriptive data analysis** on Vancouver’s operating permit dataset, implementing the five-step process from ingestion to summarization.

---

## 📊 Dataset Information

- **Source:** [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/)
- **Format:** CSV
- **Content Includes:**
  - Business Operator Unique ID
  - Property Address (Street Number & Name)
  - Outstanding Fees
  - Number of Rental Units
  - Geographic Location (Local Area & Coordinates)
  - Detail URLs & Geometric Representation

---

## ✅ Project Requirements

### 1. Functional Requirements (FRs)

- **FR1:** The platform must ingest CSV data from the Vancouver open data portal via manual upload to AWS S3.
- **FR2:** The system shall use AWS Glue DataBrew for data profiling and cleaning.
- **FR3:** A Glue Crawler must catalog the cleaned data and update the AWS Glue Data Catalog.
- **FR4:** The platform must summarize data to extract average outstanding fees and total units by operator.
- **FR5:** All components must be integrated and visualized through a data pipeline.
- **FR6:** Generate a cost report using AWS Pricing Calculator.

### 2. Non-Functional Requirements (NFRs)

- **NFR1:** The system must ensure data consistency after cleaning.
- **NFR2:** The solution should be scalable and modular.
- **NFR3:** The overall monthly cost must remain below $10 for the prototype phase.
- **NFR4:** Processing time for dataset ingestion to summarization should be under 5 minutes.

### 3. Technical Requirements (TRs)

- **TR1:** Use Amazon S3 for raw and processed data storage.
- **TR2:** Use AWS Glue for ETL (Extract, Transform, Load).
- **TR3:** Use AWS Glue DataBrew for profiling and data cleaning.
- **TR4:** Visualize architecture using draw.io diagrams.
- **TR5:** Cost calculation should be documented using the AWS Pricing Calculator.

---

## 🧪 5-Step Descriptive Analysis Process

1. **Data Ingestion:** Upload the dataset to S3.
2. **Data Profiling:** Use AWS Glue DataBrew to evaluate data quality and structure.
3. **Data Cleaning:** Fix inconsistencies, unnest and rename columns.
4. **Data Cataloging:** Use AWS Glue Crawlers to scan and catalog cleaned data.
5. **Data Summarization:** Summarize data using Glue Jobs or queries to extract key insights.

---

## 📦 Deliverables

- ✅ AWS Data Analytic Platform Implementation
- ✅ Architecture Diagram (draw.io)
- ✅ Descriptive Analysis Report
- ✅ Screenshots of Implementation Steps
- ✅ AWS Cost Estimation Report
- ✅ Insight Summary Report

---

## 💻 Tools and Technologies

| Tool | Purpose |
|------|---------|
| AWS S3 | Data storage |
| AWS Glue | ETL and data pipeline |
| AWS Glue DataBrew | Profiling & cleaning |
| AWS Pricing Calculator | Cost estimation |
| draw.io | Architecture diagrams |

---

## 💰 AWS Cost Estimation

The AWS Pricing Calculator was used to estimate:
- **Monthly Storage Cost**
- **Monthly ETL Job Cost**
- **Total Platform Operation Cost**

Estimated Monthly Total: ~$5.78  
Estimated Annual Total: ~$69.36

---

## 🔍 Insights and Findings

- Identified operators with highest outstanding fees.
- Found correlation between the number of rental units and unpaid fees.
- Enabled real-time summarization for policy analysis and decision-making.

---

## 📂 Repository Structure

# 🚀 Project Part 2: AWS-Based Data Analytics Platform (DAP) Implementation
<img width="506" alt="project2-ss" src="https://github.com/user-attachments/assets/9df30a8c-dffc-41ad-b8e7-d9a703a61416" />
# 📊 AWS Data Analytics Platform for the City of Vancouver
## 🎯 Objectives

- Deploy and integrate AWS services for real-time data processing
- Automate ETL pipelines using AWS Glue and S3
- Enable serverless querying using Amazon Athena
- Ensure secure access control and compliance with best practices
- Generate reports and dashboards from cleaned and structured datasets

## 📘 Project Description

This project focuses on leveraging **Amazon Web Services (AWS)** to develop a **scalable, automated Data Analytics Platform (DAP)** for analyzing datasets from the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/). The platform implements a structured **ETL pipeline** for data ingestion, transformation, validation, and visualization—ensuring accurate and actionable insights for stakeholders.

---

## 📚 Background

Urban governance and workforce planning depend on high-quality data. However, raw datasets from the City of Vancouver often contain:
- Inconsistencies
- Missing values
- Redundant records

To address these issues, this project:
- Automates ingestion using AWS Glue and Amazon S3
- Enhances validation via AWS Glue DataBrew
- Enables querying using Amazon Athena
- Ensures security and compliance using AWS IAM, CloudTrail, and S3 encryption

This project extends Part 1 by:
- Refining deployment procedures
- Establishing operational best practices
- Adding real-time monitoring and rollback capabilities

---

## 🚀 Methodology

### 🔁 ETL Pipeline Overview

1. **Data Ingestion**
   - Source: *Rental Standards Current Issues* dataset
   - Upload raw CSV data to Amazon S3 with versioning

2. **Data Transformation & Cleaning**
   - Clean and preprocess data using AWS Glue Jobs
   - Fix missing/inconsistent values with AWS Glue DataBrew

3. **Data Cataloging & Querying**
   - Register cleaned datasets in AWS Glue Data Catalog
   - Enable serverless SQL querying via Amazon Athena

4. **Monitoring & Error Handling**
   - Setup AWS CloudWatch alarms for ETL failures
   - Enable AWS CloudTrail for auditing and anomaly detection

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **AWS S3** | Store raw and processed datasets |
| **AWS Glue** | ETL and transformation |
| **AWS Glue DataBrew** | Data cleaning & profiling |
| **AWS Glue Data Catalog** | Metadata management |
| **Amazon Athena** | Serverless querying |
| **AWS CloudWatch** | Monitoring & job alerts |
| **AWS CloudTrail** | Security auditing |
| **AWS IAM & KMS** | Role-based access and encryption |

---

## 📦 Deliverables

- ✅ ETL Scripts (AWS Glue)
- ✅ Data Cleaning Pipelines (Glue DataBrew)
- ✅ Data Catalog Schema (Glue Data Catalog)
- ✅ Athena Query Templates
- ✅ Monitoring via CloudWatch & CloudTrail

---

## 📈 Insights & Findings

### 🧠 Business Questions Answered:
- What is the **average total outstanding** and **average number of rental units**?
- How many **distinct business URLs** are in the dataset?
- What is the **minimum street number** value?

### 🔒 Data Governance & Quality Control:
- Data validation rules enforced across reporting periods
- IAM access policies established to restrict unauthorized changes

### 📊
# 🧽 Project 3: Data Cleaning
<img width="715" alt="data cleaning -3" src="https://github.com/user-attachments/assets/8fd7f66f-279e-4218-a011-2f0a89060849" />
# 🧹 AWS-Based Data Cleaning and Analysis for Workforce and Policy Management

## 📘 Project Description

This project focuses on cleaning, analyzing, and structuring workforce and policy-related datasets using **AWS cloud services**. The goal is to ensure high-quality, structured data for effective **workforce management** and **policy compliance** by applying data preprocessing techniques and leveraging AWS tools for storage, transformation, and querying.

---

## 🏛️ Background

Organizations depend on structured, accurate data for reliable insights and compliance tracking. However, raw datasets often contain:
- Missing values
- Duplicates
- Inconsistent formats
- Incorrect data types

This project uses **AWS Glue DataBrew**, **AWS S3**, and **AWS Athena** to clean and process three datasets. The refined datasets support:
- Improved HR processes
- Enhanced policy enforcement
- Accurate reporting
- Better compliance monitoring

---

## 📂 Datasets Used

### 1. **Supervisor List Dataset (`supervisor-list.csv`)**
- Contains 10 **categorical features** (`Feature_1` to `Feature_10`)
- Useful for analyzing leadership roles and categorization patterns

### 2. **Workers List Dataset (`workers-list.csv`)**
- Includes demographic and employment data:  
  `Name`, `Age`, `Email`, `Phone`, `Address`, `City`, `State`, `Zip Code`, `Position`, `Application Date`
- Supports analysis of workforce structure and distribution

### 3. **Policy List Dataset (`policy-list.csv`)**
- Contains 10 **numerical features** (`Feature_1` to `Feature_10`)
- Helps assess policy effectiveness and compliance trends

---

## 🧪 Methodology

### 1. **Data Ingestion**
- Upload raw `.csv` files to **Amazon S3** for centralized storage

### 2. **Data Profiling**
- Use **AWS Glue DataBrew** to identify:
  - Missing values
  - Duplicate records
  - Incorrect data types

### 3. **Data Cleaning**
- Handle missing values (imputation/removal)
- Remove duplicates
- Standardize date, text, and numerical formats
- Validate and correct data types

### 4. **Data Cataloging**
- Use **AWS Glue Crawler** to catalog cleaned data

### 5. **Data Summarization**
- Run queries on cleaned data using **Amazon Athena**
- Use **Python (Pandas, Matplotlib)** for visual analytics

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Amazon S3** | Storage for raw and cleaned datasets |
| **AWS Glue DataBrew** | Profiling and data cleaning |
| **AWS Glue Crawler** | Metadata cataloging |
| **Amazon Athena** | SQL-based analysis |
| **SQL / Pandas / Matplotlib** | Custom querying and visual analytics |

---

## 📦 Deliverables

- ✅ Cleaned datasets stored in Amazon S3
- ✅ Data profiling & cleaning reports (Glue DataBrew)
- ✅ AWS Glue DataBrew transformation recipes
- ✅ SQL queries for analytics (Amazon Athena)
- ✅ Insight and recommendation document (based on analysis)

---

## 📈 Example Business Questions Answered

- What are the most common supervisor classifications?
- What is the geographical distribution of the workforce?
- Are there any patterns in application dates or job roles?
- Which policy metrics are underperforming or exceeding thresholds?

---


# 🧼 AWS-Based Data Quality Control for Workforce and Policy Datasets
<img width="688" alt="github" src="https://github.com/user-attachments/assets/c1b1d77a-2604-47eb-9bb0-e18b3418ec95" />

## 📘 Project Description

This project implements a **Data Quality Control (DQC)** framework using AWS cloud services to clean, validate, and monitor **workforce and policy datasets**. By automating data quality checks and applying best practices in data management, this solution ensures data **accuracy**, **completeness**, and **consistency** to support **reliable decision-making** and **regulatory compliance**.

---

## 🏛️ Background

Poor data quality negatively impacts workforce planning and policy enforcement. Inconsistencies, missing fields, duplicates, and anomalies can result in:

- Misclassification of workers and supervisors
- Gaps in policy tracking and enforcement
- Compliance risks and reporting errors

This project solves these issues through a **scalable, AWS-based DQC framework** leveraging services like **AWS Glue**, **AWS Glue DataBrew**, **Amazon S3**, and **Amazon Athena**.

---

## 📂 Datasets

### 🧑‍💼 Supervisor List (`employee-list.csv`)
- **Fields**: Feature_1 to Feature_10
- **Common Issues**:
  - Inconsistent categorical values
  - Duplicate entries
  - Missing classifications

### 👷 Workers List (`remote workers-list.csv`)
- **Fields**: Name, Age, Email, Phone, Address, City, State, Zip Code, Position, Application Date
- **Common Issues**:
  - Invalid email/phone formats
  - Missing application dates
  - Duplicate records

### 📋 Policy List (`policy-list.csv`)
- **Fields**: Feature_1 to Feature_10
- **Common Issues**:
  - Inaccurate classifications
  - Outdated or missing records
  - Anomalies in numerical values

---

## 🔁 Methodology: Data Quality Control Lifecycle

### 1. 📥 Data Ingestion & Storage
- Upload raw datasets to **Amazon S3**
- Generate metadata using **AWS Glue Crawler**

### 2. 🔍 Data Profiling & Assessment
- Use **AWS Glue DataBrew** to:
  - Identify missing values
  - Detect anomalies
  - Check for duplicate records

### 3. ✅ Data Validation & Quality Checks
- Define validation rules for:
  - Range checks
  - Format enforcement (email, phone)
  - Unique constraints

### 4. 🚨 Error Handling & Anomaly Detection
- Use **DataBrew transformations** to flag errors
- Log invalid records for manual review or remediation

### 5. 🧽 Data Cleaning & Standardization
- Fix data type mismatches
- Remove duplicates
- Normalize categories and dates

### 6. 📊 Data Monitoring & Reporting
- Generate quality reports via **Amazon Athena**
- Create visual dashboards using **Amazon QuickSight**
- Implement automated alerts for recurring issues

---

## 🛠️ Tools and Technologies

| AWS Service | Purpose |
|-------------|---------|
| **Amazon S3** | Store raw and processed datasets |
| **AWS Glue** | Metadata cataloging & ETL |
| **AWS Glue DataBrew** | Profiling, cleaning, and validation |
| **Amazon Athena** | SQL-based analysis and reporting |
| **Amazon QuickSight** | (Optional


# 🏅 My AWS Completion Badge
<img width="443" alt="aws badge" src="https://github.com/user-attachments/assets/5f56d161-19b4-48f2-bd32-36684ff685c1" />


## 🧠 What I Learned

Throughout the training, I developed skills in:

- ✅ Cloud computing fundamentals (IaaS, PaaS, SaaS)
- ✅ Core AWS services: S3, EC2, IAM, VPC, RDS, Lambda, and more
- ✅ Data analytics tools: AWS Glue, Athena, QuickSight, and S3
- ✅ Serverless computing and automation
- ✅ Security, compliance, and cost optimization
- ✅ Designing scalable and highly available architectures

## 🙌 Acknowledgments

Thanks to [AWS Academy](https://aws.amazon.com/training/) for providing hands-on cloud learning and real-world project experience.

