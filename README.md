# 🏗️ Data Warehouse Project

Welcome to the repository for our modern **Data Warehouse** architecture built using the **Medallion Model** (Bronze → Silver → Gold). This structure enables scalable, maintainable, and analytics-ready data pipelines.

---

## 📌 Overview

This project ingests raw data from multiple sources (CRM, ERP in CSV format), processes it in stages, and outputs **business-ready datasets** for analytics and reporting.

**Architecture Stages:**
- **Bronze Layer** – Raw Data (No transformations)
- **Silver Layer** – Cleaned & Standardized Data
- **Gold Layer** – Business-Ready Data

---

## 🧱 Architecture

```text
Sources (CRM, ERP CSV) 
     ↓
Bronze Layer (Raw Data Tables)
     ↓
Silver Layer (Cleaned & Standardized)
     ↓
Gold Layer (Business-Ready Data)
     ↓
Consumption (Dashboards, Reports, ML)
