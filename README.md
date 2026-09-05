# Azure Digital Marketing Data Engineering Project

## 📌 Project Overview

This project demonstrates an end-to-end **Data Engineering pipeline for Digital Marketing data** using Microsoft Azure services.

The pipeline ingests advertising campaign data from multiple e-commerce platforms, processes the data through a **Medallion Architecture**, and produces analytics-ready datasets and dashboards.

### Platforms Covered

- Amazon
- Flipkart
- Blinkit
- Zepto
- Swiggy
- BigBasket

---

## 🏗️ Architecture

```text
Marketing Platforms
        │
        ▼
   Landing Layer
        │
        ▼
 Azure Data Factory
        │
        ▼
   Bronze Layer
        │
        ▼
   Silver Layer
        │
        ▼
    Gold Layer
        │
        ▼
 Databricks AI/BI
    Dashboard
