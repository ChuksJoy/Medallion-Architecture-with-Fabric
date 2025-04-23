# Medallion Architecture with Microsoft Fabric Lakehouse

This project demonstrates the implementation of a **Medallion Architecture** (Bronze, Silver, and Gold layers) using **Microsoft Fabric Lakehouse** and notebooks. The architecture follows a modern data engineering pattern that incrementally refines raw data for advanced analytics and reporting.

## Overview

In this exercise, I built out a complete medallion architecture using Delta Lake tables in a Fabric Lakehouse. The goal was to ingest raw data, process it through structured transformations, and make it analysis-ready by layering it into Bronze, Silver, and Gold Delta tables.

## Steps and Workflow

1. **Create a Workspace**
   - Set up a dedicated workspace for housing all assets.

2. **Create a Lakehouse and Upload Data to Bronze Layer**
   - Established the lakehouse structure.
   - Ingested raw data into the **Bronze Layer**, preserving the original state for traceability.

3. **Transform Data and Load to Silver Delta Table**
   - Cleaned and structured data using notebooks.
   - Loaded the curated data into the **Silver Layer** Delta table.

4. **Explore Data Using the SQL Endpoint**
   - Connected to the SQL endpoint to perform ad-hoc queries and validate the Silver data.

5. **Transform Data for Gold Layer**
   - Applied business logic and aggregations.
   - Loaded the results into **Gold Layer** Delta tables for final consumption.

6. **Create a Semantic Model**
   - Built relationships and defined measures.
   - Enabled self-service analytics and reporting through Power BI integration.

## Technologies Used

- Microsoft Fabric
- Lakehouse (Delta Lake format)
- Notebooks
- SQL Endpoint
- Power BI (Semantic modeling)

## Outcome

This exercise showcases a scalable and modular approach to modern data transformation pipelines using Fabric. Each layer adds value to the raw data and makes it ready for consumption in business intelligence tools.

---

🔍 **Note:** This project is an educational exercise to reinforce key concepts in data modeling, transformation, and lakehouse architecture using Microsoft's unified analytics platform.

