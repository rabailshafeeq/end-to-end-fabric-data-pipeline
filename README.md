# Microsoft-Fabric-Data-Engineering-Project - World Wide Earthquakes

<img src="Images\End to End Process Diagram.png" >


## Project Overview
This project demonstrates a structured data pipeline implemented in Microsoft Fabric to process raw data ingested from the USGS API. The data is transformed across three layers—Bronze, Silver, and Gold—before being visualized in a Power BI report. The pipeline ensures that the data is cleaned, transformed, and optimized for reporting, offering a scalable and efficient way to work with large datasets.

Ingesting Earthquake events data from [usgs](https://earthquake.usgs.gov/fdsnws/event/1/#parameters).

Technologies Used: Python, PySpark, Fabric (Data Engineering, Data Factory, Power BI)


## Project Structure

[1. Bronze Layer (Raw Data)](https://github.com/Gbemiclassic/Microsoft-Fabric-Data-Engineering-Project/blob/main/1.%20Bronze%20Layer%20Processing.ipynb)
Purpose: Ingest raw JSON data from an API into the Lakehouse in Microsoft Fabric.
Method: A Notebook is used to pull the data and store it as a JSON file in the Lakehouse. This raw data acts as the foundation for further processing.

[2. Silver Layer (Processed Data)](https://github.com/Gbemiclassic/Microsoft-Fabric-Data-Engineering-Project/blob/main/2.%20Silver%20Layer%20Processing.ipynb)
Purpose: Clean, validate, and transform the raw JSON data into a structured table.
Method: Another Notebook processes the raw JSON file from the Bronze Layer, converting it into a more usable format, and stores it in a table. This layer ensures the data is ready for analysis by removing errors, handling missing values, and performing initial transformations.

[3. Gold Layer (Reporting-Ready Data)](https://github.com/Gbemiclassic/Microsoft-Fabric-Data-Engineering-Project/blob/main/3.%20Gold%20Layer%20Processing.ipynb)
Purpose: Further process the Silver Layer data into a format suitable for reporting and analysis.
Method: A third Notebook processes the data into the final Gold Layer, which contains aggregated and curated data, optimized for Power BI reports.

[4. Power BI Report](https://github.com/Gbemiclassic/Microsoft-Fabric-Data-Engineering-Project/blob/main/Earthquake%20Events%20Report.pbix)
Purpose: Visualize the final processed data for business analysis and decision-making.
Method: A Power BI report is created using the Gold Layer data, providing interactive dashboards and insights to the business stakeholders.


Data Attribute Definitions
`id`: A string identifier for each data record.

`latitude`: The latitude of the event, stored as a double.

`longitude`: The longitude of the event, also stored as a double.

`elevation`: The elevation at which the event occurred, expressed in meters, stored as a double.

`title`: A string representing the title or name of the event.

`place_description`: A string describing the location of the event.

`sig`: A bigint (large integer) representing the significance score of the event.

`mag`: A double indicating the magnitude of the earthquake.

`magType`: A string describing the type of magnitude scale used.

`time`: A timestamp marking the exact time of the event.

`updated`: A timestamp indicating the last update time for the event data.


## Pipeline

Here is the image of the pipeline

<img src="Images\Pipeline.jpg" >

## Power BI Report

Below is the Power BI created from the Gold layer data

<img src="Images\Report Screenshot.jpg" >


 # <p align="center" style="margin-top: 0px;">Thank you 😎
