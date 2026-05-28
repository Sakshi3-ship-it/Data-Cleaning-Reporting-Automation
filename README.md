# Data Cleaning & Reporting Automation Tool

A rule-based automated analytics workflow that ingests uncleaned transaction database records, resolves common structural data quality anomalies, and programmatically exports multi-sheet Excel reports and executive KPI visual matrices.

## 📊 Project Overview
Manual data preprocessing and corporate report generation can be incredibly time-consuming. This pipeline automates the entire processing lifecycle, taking a messy row-and-column data source and instantly converting it into clean, presentation-ready business intelligence.

### Key Features
* **Automated Data Quality Audits:** Automatically drops duplicate transactions based on strict unique constraints.
* **String Standardization:** Trims structural trailing white spaces and formats mismatched string casing schemas.
* **Intelligent Imputation:** Imputes missing numerical cells using statistical median strategies to preserve data distributions.
* **Programmatic Reporting:** Uses an advanced data engine layer to route clean metrics out to organized multi-sheet Excel workbooks (`.xlsx`).
* **Visual Summary Integration:** Compiles regional performance variations directly into an exported, presentation-grade bar chart visualization.

---

## 🗂️ Project Workspace Mapping
Data-Cleaning-Reporting-Automation/
│
├── reporting_automation.py       # Primary pipeline execution script
├── README.md                     # Technical implementation documentation (This file)
├── automated_business_report.xlsx# Automatically compiled multi-sheet KPI Excel file
└── automated_report_chart.png    # Automatically exported revenue distribution chart

---

## ⚙️ Installation & Workspace Setup

1. **Clone or download this repository** into your local development workspace.
2. **Install core pipeline dependencies** using your terminal tool:
   ```bash
   pip install numpy pandas openpyxl matplotlib seaborn
