
# Enterprise Data Platform

### Azure & Microsoft Fabric


This repository contains multiple end-to-end Data Engineering case studies that demonstrate how the same business problem can be solved using different Microsoft data platforms.

The objective is to apply real-world Data Engineering concepts such as:

- Data Ingestion
- Data Lake Architecture
- ETL / ELT Pipelines
- Data Warehousing
- Data Quality
- Pipeline Monitoring
- Incremental Loading
- Business Intelligence
- Platform Comparison

---

## Technologies

### Microsoft Azure

- Azure Data Lake Storage Gen2
- Azure Data Factory
- Azure SQL Database
- Power BI

### Microsoft Fabric

- OneLake
- Data Factory
- Lakehouse
- Warehouse
- Notebook
- Power BI

---

## Repository Structure

```text
enterprise-data-platform/
│
├── README.md
│
├── case-studies/
│   └── walmart-sales/
│       ├── azure/
│       ├── fabric/
│       └── comparison/
│
├── docs/
│
├── architecture/
│
└── assets/
```

---

# Case Studies

## 01 - Walmart Sales Platform

**Business Problem**

Build an end-to-end data platform for Walmart sales data using Microsoft Azure and Microsoft Fabric.

### Current Status

- [x] Project Planning
- [x] Data Analysis
- [ ] Azure Implementation
- [ ] Microsoft Fabric Implementation
- [ ] Platform Comparison

## Design Decisions

### Data Model

A single fact table was selected instead of implementing a full Star Schema.

**Reason:**

The Walmart Sales dataset contains a single business entity (weekly sales) with a limited number of descriptive attributes. Implementing multiple dimension tables would introduce unnecessary complexity without providing significant analytical benefits.

This approach keeps the solution simple while still following Data Engineering best practices. If additional datasets (such as Customers, Products, or Stores) become available, the model can be extended into a Star Schema.

---

## Learning Objectives

- Design scalable data platforms.
- Build production-like ETL pipelines.
- Apply Data Engineering best practices.
- Compare Azure and Microsoft Fabric.
- Create professional portfolio projects.

---

## Documentation

Documentation, architecture diagrams, implementation details, and design decisions will be added throughout the project.

---
