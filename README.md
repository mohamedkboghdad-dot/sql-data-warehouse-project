# 🚀 SQL Server Data Warehouse & Analytics Project

An End-to-End Data Engineering Project | SQL Server | ETL | Medallion Architecture | Dimensional Modeling

## 📌 Project Overview

This project demonstrates the design and implementation of a modern **Data Warehouse using Microsoft SQL Server**, transforming raw sales data from multiple business systems into a structured, analytics-ready data model.

The solution integrates data from **CRM and ERP source systems**, applies data cleansing and transformation processes, and organizes the data into Bronze, Silver, and Gold layers following the Medallion Architecture.

The final Gold layer provides a dimensional model optimized for analytical queries and business reporting.

## 🎯 Business Objectives

The primary goal is to build a centralized data warehouse that enables reliable and consistent sales analysis.

Key objectives:

- Integrate data from multiple CRM and ERP systems.
- Improve data quality through cleansing and validation.
- Transform raw data into structured and consistent datasets.
- Build fact and dimension tables using dimensional modeling.
- Provide a reliable foundation for analytical reporting and business insights.

## 🏗️ Data Architecture

The project follows the **Medallion Architecture**, consisting of three layers:

### 1. Bronze Layer – Raw Data

- Load raw CSV files from CRM and ERP systems into SQL Server.
- Preserve the original source structure.
- Maintain raw data for downstream processing.

### 2. Silver Layer – Cleansed & Integrated Data

- Perform data cleansing and standardization.
- Handle missing values and inconsistent records.
- Resolve data quality issues.
- Integrate CRM and ERP datasets.
- Apply business transformation rules.

### 3. Gold Layer – Analytics & Reporting

- Build fact and dimension tables.
- Implement a Star Schema data model.
- Organize business entities for analytical queries.
- Provide analytics-ready datasets for reporting.

## 🔄 ETL Pipeline

The data engineering workflow consists of three main stages:

**Extract**
- Extract raw data from CRM and ERP CSV files.

**Transform**
- Clean and standardize source data.
- Apply transformation and integration rules.
- Validate data quality.
- Prepare datasets for dimensional modeling.

**Load**
- Load processed data into the appropriate warehouse layers.
- Build analytical fact and dimension tables.
- Make the final datasets available for reporting.

## 🧩 Data Modeling

The Gold layer is designed using **Dimensional Modeling** principles.

The project focuses on:

- Fact and dimension table design.
- Star Schema architecture.
- Primary and foreign key relationships.
- Analytical query optimization.

The dimensional model provides a simplified structure for querying business data and generating meaningful insights.

## 🛠️ Technologies & Tools

| Category | Technologies |
|---|---|
| Database | Microsoft SQL Server |
| Query Language | T-SQL |
| Data Processing | SQL |
| Data Architecture | Medallion Architecture |
| Data Modeling | Star Schema, Fact & Dimension Tables |
| Data Integration | ETL |
| Data Sources | CRM & ERP CSV Files |
| Documentation | Markdown, ER Diagrams |
| Version Control | Git & GitHub |

## 📂 Repository Structure

```text
sql-data-warehouse-project/
│
├── datasets/
│   ├── source_crm/
│   └── source_erp/
│
├── docs/
│   ├── data_catalog.md
│   ├── data_architecture.drawio
│   └── data_models.drawio
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│   ├── quality_checks_silver.sql
│   └── quality_checks_gold.sql
│
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Before running the project, make sure you have:

- Microsoft SQL Server.
- SQL Server Management Studio (SSMS).
- Git.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/mohamedkboghdad-dot/sql-data-warehouse-project.git
```

**2. Navigate to the project directory**

```bash
cd sql-data-warehouse-project
```

**3. Open the SQL scripts**

Open the project scripts using SQL Server Management Studio.

**4. Configure the database**

Create the required database and configure the source data paths according to your local environment.

**5. Execute the ETL workflow**

Run the SQL scripts in the appropriate order:

1. Bronze Layer – Raw Data Loading.
2. Silver Layer – Data Cleaning & Transformation.
3. Gold Layer – Dimensional Modeling.

**6. Run Data Quality Tests**

Execute the validation scripts in the `tests/` directory to check the quality and consistency of the processed data.

## 🧪 Data Quality & Validation

Data quality is an essential part of this project.

Validation focuses on:

- Identifying duplicate records.
- Checking missing and invalid values.
- Validating primary and foreign key relationships.
- Ensuring consistency across integrated datasets.
- Verifying the integrity of Gold layer tables.

## 📊 Analytics & Reporting

The Gold layer provides a foundation for analytical queries and business reporting.

It enables analysis of:

- Sales performance.
- Customer behavior.
- Product performance.
- Business trends and patterns.

## 📚 Key Concepts Demonstrated

Through this project, the following Data Engineering concepts are demonstrated:

- Data Warehouse Architecture.
- ETL Pipeline Development.
- Medallion Architecture (Bronze, Silver, Gold).
- Data Cleaning & Transformation.
- Data Integration.
- Dimensional Modeling.
- Star Schema Design.
- Data Quality Testing.
- SQL Server Development.

## ⚠️ Project Scope

This implementation focuses on the latest available dataset.

Historical data tracking and Slowly Changing Dimensions (SCD) are outside the current project scope.

## 👨‍💻 Author

**Mohamed Kamer Boghdad**

Junior Data Engineer | SQL | Python | PySpark | Databricks | Data Warehousing | ETL

- GitHub: [mohamedkboghdad-dot](https://github.com/mohamedkboghdad-dot)
- LinkedIn: [Mohamed Kamer Boghdad](https://www.linkedin.com/in/mohamed-boghdad-46a169403/)

---

⭐ If you find this project useful, feel free to explore the repository and give it a star!
