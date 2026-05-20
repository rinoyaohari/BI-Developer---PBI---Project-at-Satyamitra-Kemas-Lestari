# 📦 PT Satyamitra Kemas Lestari – BI Reporting Project

## Project Overview
This project was developed for **PT Satyamitra Kemas Lestari** to support business reporting and analytics using **Power BI** with data sourced directly from **Google Cloud Platform (GCP)**.

The reporting solution utilized direct connectivity between Power BI and GCP using credential authentication in **JSON format**. The project focused on building tabular reporting solutions for operational and business analysis.

I worked as a **BI Developer**, responsible for data connectivity, report development, and automated report generation.

---

# Responsibilities

## Data Source Integration
- Connected Power BI directly to Google Cloud Platform (GCP)
- Configured authentication using JSON credential files
- Managed secure data access and connectivity setup

## Power BI Reporting Development
- Developed 3 tabular reporting solutions
- Built reports optimized for operational and business reporting needs
- Structured datasets for reporting consumption

## Power BI Report Builder
- Created 2 paginated/tabular reports using:
  - Power BI Report Builder
- Designed report layouts for printable and exportable reporting

## Python Automation
- Developed custom Python program to generate Excel-based reports
- Automated report generation process
- Improved reporting distribution and export flexibility

## Reporting Delivery
- Ensured report accuracy and usability
- Supported business users with reporting outputs and validation

---

# Technology Stack

| Technology | Purpose |
|---|---|
| Google Cloud Platform (GCP) | Data Source |
| Power BI | Dashboard & Reporting |
| Power BI Report Builder | Paginated Reports |
| Python | Excel Report Automation |
| JSON Credential | Secure Authentication |

---

# Project Workflow

```mermaid
flowchart TD

A[GCP Data Source]
B[JSON Credential Authentication]
C[Power BI Connection]
D[Dataset Preparation]
E[Power BI Tabular Reports]
F[Power BI Report Builder]
G[Paginated Reports]
H[Python Automation]
I[Excel Report Generation]
J[Business Users]

A --> B
B --> C
C --> D
D --> E
D --> F
F --> G
D --> H
H --> I
E --> J
G --> J
I --> J
