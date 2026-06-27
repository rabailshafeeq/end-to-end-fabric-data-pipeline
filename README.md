# End-to-End Microsoft Fabric Data Engineering Project

<img src="Images/End to End Process Diagram.png" alt="Microsoft Fabric Data Engineering Architecture" width="100%">

## Overview

This project demonstrates an end-to-end data engineering solution built with Microsoft Fabric. The solution ingests real-time earthquake data from the USGS API, processes it through a Medallion Architecture (Bronze, Silver, and Gold), and delivers business-ready insights through an interactive Power BI dashboard.

The project highlights the implementation of modern data engineering practices, including automated data ingestion, scalable ETL pipelines, Lakehouse architecture, and data visualization for reporting and analysis.

---

## Business Problem

Raw data collected from external APIs is often unstructured and unsuitable for direct reporting. Organizations require an efficient process to ingest, clean, transform, and organize this data before it can be used for analytics and business intelligence.

This project demonstrates how Microsoft Fabric can be used to automate that entire process, creating reliable and reporting-ready datasets.

---

## Solution Architecture

<img src="Images/End to End Process Diagram.png" alt="Solution Architecture" width="100%">

The solution follows the Medallion Architecture:

* **Bronze Layer** – Ingests raw earthquake data from the USGS API into the Lakehouse.
* **Silver Layer** – Cleans, validates, and transforms the raw data into structured datasets using PySpark.
* **Gold Layer** – Creates curated datasets optimized for analytics and reporting.
* **Power BI** – Connects to the Gold Layer to deliver interactive dashboards and business insights.

---

## Technology Stack

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| Microsoft Fabric | End-to-end data platform            |
| Data Factory     | Pipeline orchestration              |
| Lakehouse        | Data storage                        |
| OneLake          | Centralized data management         |
| Python           | API integration                     |
| PySpark          | Data transformation                 |
| Power BI         | Business intelligence and reporting |
| REST API         | Data source                         |

---

## Data Engineering Workflow

The project follows a three-layer Medallion Architecture:

### Bronze Layer

* Extracts earthquake event data from the USGS API.
* Stores raw JSON data in the Lakehouse.
* Preserves the original source data for future processing.

### Silver Layer

* Cleans and validates incoming records.
* Handles missing values and inconsistent data.
* Converts raw JSON into structured tables using PySpark.

### Gold Layer

* Creates business-ready datasets.
* Optimizes data for reporting and analytics.
* Serves as the source for Power BI dashboards.

---

## Data Pipeline

<img src="Images/Pipeline.jpg" alt="Microsoft Fabric Pipeline" width="100%">

The ETL workflow is orchestrated using Microsoft Fabric Data Factory. The pipeline automates data ingestion, executes transformation notebooks, and loads processed datasets into the Gold Layer, enabling a reliable and repeatable data processing workflow.

---

## Power BI Dashboard

<img src="Images/Report Screenshot.jpg" alt="Power BI Dashboard" width="100%">

The dashboard provides interactive insights into earthquake activity, allowing users to analyze:

* Earthquake magnitude trends
* Geographic distribution of events
* Event locations
* Time-based analysis
* Key performance indicators
* Interactive filtering and exploration

---

## Key Features

* End-to-end Microsoft Fabric implementation
* Automated ETL pipeline
* REST API integration
* Medallion Architecture (Bronze, Silver, Gold)
* Lakehouse-based data storage
* PySpark data transformation
* Interactive Power BI reporting
* Scalable and production-ready architecture

---

## Deliverables

* Microsoft Fabric Workspace
* Data Factory Pipeline
* Bronze, Silver, and Gold Lakehouse Layers
* PySpark Notebooks
* Interactive Power BI Dashboard
* Project Documentation

---

## Business Value

This project demonstrates how Microsoft Fabric can be used to build scalable, cloud-based data engineering solutions that transform raw API data into actionable business insights. The architecture is designed to support efficient data processing, reliable reporting, and informed decision-making.

---

## About This Project

This repository is part of my data engineering portfolio and demonstrates my experience with Microsoft Fabric, ETL pipeline development, Lakehouse architecture, PySpark data transformation, REST API integration, and Power BI dashboard development. It reflects the type of end-to-end data engineering solutions I can deliver for businesses seeking modern analytics platforms.
