
# DADABI_DEMO 📊  
### Data Engineering Practice & Project Implementation Repository

## 📌 Overview
This repository contains individual and course workshop projects implemented using Azure Data Factory (ADF), focusing on building and testing scalable data pipelines, dataflows, and end-to-end data engineering solutions.  
It includes real-world datasets such as:
- **Seattle Pet License Data**
- **NYPD Complaint Data**

The aim of this repo is to demonstrate practical skills in data ingestion, transformation, staging, and loading into Snowflake, along with cleaning and pipeline orchestration using ADF.

---

## 📂 Repository Structure
```
DADABI_DEMO/
│
├── dataflow/               # Data transformation logic using ADF Mapping Data Flows
├── dataset/                # Dataset references for source and sink data
├── factory/                # Azure Data Factory template
├── integrationRuntime/     # Runtime configurations for ADF execution
├── linkedService/          # Linked service definitions for Blob Storage and Snowflake
├── pipeline/               # Orchestration pipelines (e.g., ingestion, cleaning, loading)
├── publish_config.json     # ADF ARM deployment configuration
└── main                    # Entry trigger or utility file
```

---

## 🛠️ Projects Covered

### 📁 Seattle Pet License Dataset
- **Objective**: Clean and transform pet license data for analysis.
- **Tasks Performed**:
  - Removing nulls and invalid records
  - Standardizing breed and species categories
  - Enriching data with geolocation details (ZIP code level)
  - Loading into Snowflake for dashboard/report use

### 📁 NYPD Complaint Dataset
- **Objective**: Process and analyze crime complaint data from NYC Open Data.
- **Tasks Performed**:
  - Standardization of date and complaint type fields
  - Handling malformed characters and nulls
  - Creating a dimensional data model (Fact_Crime, Dim_Date, Dim_Location)
  - Loading transformed tables into Snowflake

---

## 🔄 Process Flow
1. **Raw Data Ingestion** → Azure Blob Storage  
2. **Cleaning & Transformation** → Mapping Dataflows in ADF  
3. **Staging/Loading** → Snowflake  
4. **Monitoring & Orchestration** → Pipelines and Integration Runtime  

---

## 🧰 Tools & Technologies
- Azure Data Factory (ADF)
- Azure Blob Storage
- Snowflake
- Power BI (optional dashboarding layer)
- JSON-based ADF templates

---

## 💡 Key Learnings
- Practiced building modular pipelines and reusable templates.
- Understood real-world data cleaning challenges and transformation logic.
- Gained expertise in linking cloud storage to Snowflake via ADF.
- Built foundational patterns for future enterprise-grade data solutions.

---

## 👨‍💻 Author
- **Ganesh Paparaju**

---

## 📬 Contact
Feel free to explore or fork the repository.  
For collaboration or feedback, connect via GitHub or LinkedIn.
