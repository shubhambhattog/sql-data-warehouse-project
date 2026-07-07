# 📊 Data Warehouse and Analytics Project

![Data Warehouse Banner]

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project showcases a comprehensive solution for building a data warehouse and generating business insights through SQL-based analytics. Designed as a portfolio project, it incorporates industry best practices in **data architecture, ETL, and analytics**.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** — structured in **Bronze, Silver, and Gold layers**:

| Layer  | Description |
|--------|-------------|
| 🟫 **Bronze** | Raw data from source systems ingested from CSV files into SQL Server. |
| ⚪ **Silver** | Cleaned, standardized, and transformed data for querying. |
| 🟨 **Gold**   | Business-ready data in a **Star Schema** for reporting and analytics. |

---

## 📖 Project Overview

This project covers:

- 🧱 **Data Architecture** — Medallion layered design
- ⚙️ **ETL Pipelines** — Extract, Transform, Load workflows
- 🗃️ **Data Modeling** — Fact and dimension tables (star schema)
- 📈 **Analytics & Reporting** — Actionable SQL-based insights

---

## 🎯 Who Is This For?

This project is perfect for anyone looking to build or showcase skills in:

- 🔍 **SQL Development**
- 🧠 **Data Analytics**
- 🏗️ **Data Engineering**
- 🔁 **ETL Pipelines**
- 📊 **BI & Reporting**
- 🧰 **Data Modeling**

---

## 🛠️ Tools & Resources

Everything you need is **free** to use:

| Tool | Purpose |
|------|---------|
| 📂 CSV Datasets | Sales data from ERP & CRM systems |
| 🧮 SQL Server Express | Lightweight database engine |
| 🧠 SSMS | GUI for managing SQL Server |
| 🧾 Notion | Project planning and templates |
| 🧱 DrawIO | Architecture, data flows, and models |
| 💻 GitHub | Version control and collaboration |

---

## 🚀 Project Requirements

### 📦 Building the Data Warehouse

**Objective:**  
Design a modern data warehouse using SQL Server to unify ERP and CRM data.

- **Sources:** Two CSV files (ERP & CRM)
- **Quality:** Clean and resolve data issues
- **Integration:** Unified data model for analytics
- **Focus:** Latest dataset only (no historization)
- **Docs:** Clear model documentation for business & tech users

---

### 📊 BI: Analytics & Reporting

**Objective:**  
Use SQL to extract meaningful insights, including:

- 👥 Customer Behavior
- 📦 Product Performance
- 💰 Sales Trends

This enables stakeholders to make data-driven decisions with confidence.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hey there! 👋 I’m Tanishka Vijetra — part analyst, part data detective, and full-time fan of turning chaos into clarity. I built this project to show how raw, messy CSV files can be transformed into sleek, business-ready dashboards… kind of like giving data a spa day 🧖‍♀️📊.

💬 A little about me:
- 🛠 I love designing data pipelines that actually *work* — no duct tape involved.
- 📦 I believe in the power of good data models (Star Schema = ⭐️ of my heart).
- 📈 My happy place is writing SQL queries that answer the unspoken business question.
- 🎯 I enjoy finding hidden patterns, weird anomalies, and “aha!” insights in datasets.

Let's stay in touch! Feel free to connect with me on the following platforms:


[![LinkedIn](https://www.linkedin.com/in/tanishka-vijetra/)


