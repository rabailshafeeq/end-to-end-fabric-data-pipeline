# 🌍 End-to-End Microsoft Fabric Data Engineering Project

<img src="Images/End to End Process Diagram.png" alt="Microsoft Fabric Data Engineering Architecture" width="100%">

## Overview

This project demonstrates a complete **end-to-end data engineering solution** built with **Microsoft Fabric**. The pipeline ingests real-time earthquake data from the USGS API, processes it through a **Medallion Architecture (Bronze → Silver → Gold)**, and delivers business-ready insights using an interactive **Power BI Dashboard**.

The solution showcases enterprise-grade data engineering practices, including automated ingestion, scalable ETL pipelines, Lakehouse architecture, and business intelligence reporting.

---

# 🚀 Solution Architecture

<img src="images/End to End Process Diagram.png" alt="Solution Architecture">

The architecture consists of:

* API Data Ingestion
* Bronze Layer (Raw Data)
* Silver Layer (Cleaned Data)
* Gold Layer (Business Data)
* Power BI Reporting

---

# ⚙️ Technology Stack

| Technology       | Purpose                |
| ---------------- | ---------------------- |
| Microsoft Fabric | Data Platform          |
| Data Factory     | Pipeline Orchestration |
| Lakehouse        | Data Storage           |
| OneLake          | Centralized Storage    |
| PySpark          | Data Processing        |
| Python           | API Integration        |
| Power BI         | Visualization          |
| REST API         | Data Source            |

---

# 📂 Project Workflow

### 1️⃣ Bronze Layer

Raw earthquake data is extracted directly from the USGS API and stored in the Lakehouse without modification.

<img src="Images/Bronze Layer.png" width="100%">

---

### 2️⃣ Silver Layer

Data is cleaned, validated, transformed, and converted into structured tables using PySpark.

<img src="images/Silver Layer.png" width="100%">

---

### 3️⃣ Gold Layer

Business-ready datasets are created for analytics and reporting.

<img src="Images/Gold Layer.png" width="100%">

---

# 🔄 Data Pipeline

The complete ETL process is orchestrated using Microsoft Fabric Data Factory.

<img src="images/Pipeline.jpg" width="100%">

Pipeline Highlights:

* Automated execution
* Notebook orchestration
* Layer-to-layer transformation
* End-to-end workflow automation

---

# 📊 Power BI Dashboard

The Gold Layer powers an interactive dashboard that enables business users to analyze earthquake events efficiently.

<img src="Images/Report Screenshot.jpg" width="100%">

Dashboard Features:

* Earthquake Magnitude Analysis
* Geographic Distribution
* Event Timeline
* Regional Insights
* Interactive Filtering
* KPI Monitoring

---

# ⭐ Key Features

* End-to-End Microsoft Fabric Solution
* REST API Data Integration
* Medallion Architecture
* Automated ETL Pipelines
* PySpark Data Transformation
* Lakehouse Implementation
* Power BI Reporting
* Scalable Enterprise Architecture

---

# 📦 Deliverables

✔ Microsoft Fabric Workspace

✔ Data Factory Pipeline

✔ Bronze / Silver / Gold Lakehouse

✔ PySpark Notebooks

✔ Power BI Dashboard

✔ Project Documentation

---

# 💼 Business Value

This solution demonstrates how Microsoft Fabric can be used to build modern, scalable data platforms capable of ingesting, processing, and analyzing large datasets efficiently. It follows industry best practices and provides a strong foundation for enterprise reporting and data-driven decision-making.

---

# 📬 Let's Connect

If you're looking for a Microsoft Fabric Data Engineer to build scalable ETL pipelines, Lakehouse solutions, or Power BI dashboards, feel free to connect.

⭐ If you found this project helpful, consider giving it a star!
