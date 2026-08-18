# TTTC3213 Data Engineering & Analytics Project: Shopify ETL & Exploratory Data Analysis

## 📖 Project Overview

This repository contains the complete codebase, datasets, presentation materials, and analysis reports for the **TTTC3213** course project. It comprises two main components: **Group 8 Team Project** and **Individual Assignments (YU YIFAN - A191702)**.

The project focuses on **Shopify E-commerce platform data**, covering the end-to-end data processing workflow: web scraping (Extract), data cleaning and transformation (Transform), data loading/storage (Load), as well as Exploratory Data Analysis (EDA) and data visualization.

---

## 📁 Directory Structure

```text
.
├── A191702 Individual Assignment/             # Individual Assignment Directory (Yu Yifan - A191702)
│   ├── INDIVIDUAL_ASSIGMENT_1_YU_YIFAN_A191702.ipynb  # Assignment 1: Data Preprocessing & Cleaning
│   ├── INDIVIDUAL_ASSIGMENT_2_YU_YIFAN_A191702.ipynb  # Assignment 2: EDA, Visualization & Correlation Analysis
│   └── shopify_sales_products.csv            # Raw Dataset for Individual Assignment
│
└── TTTC3213_Group8_Project/                  # Group 8 Team Project Directory
    ├── TTTC3213_Group_Project.ipynb          # Master Notebook (Scraping, ETL & Visualization)
    ├── ETL Process for Shopify Online Shopping Website.pdf   # Project Report (PDF)
    ├── ETL Process for Shopify Online Shopping Website.pptx  # Presentation Slides (PPTX)
    ├── TTTC3213 Project Link.docx            # Summary of External Links (Colab / GitHub / Medium)
    ├── shopify_sales_products.csv            # Raw Web-scraped Shopify Product Dataset
    ├── shopify_sales_products_cleaned.csv    # Cleaned & Structured Dataset
    └── shopify_products_vendor_star.csv      # Derived Dataset with Vendor Ratings/Stars
```

---

## 🚀 Key Modules & Workflow

### 1. Group 8 Team Project: Shopify E-commerce ETL Pipeline & Analysis

- **Extract**: Built Python web scraper scripts to harvest product attributes (Titles, Prices, Vendors, Tags, Inventory Levels, etc.) from Shopify e-commerce sites.

- **Transform**:
  - Handled missing values, duplicated entries, and price format anomalies.
  - Extracted and standardized pricing numerical fields and inventory quantities.
  - Derived vendor rating metrics (`shopify_products_vendor_star.csv`).

- **Load & Data Visualization**:
  - Analyzed vendor performance, price distribution, and product categorical popularity using Pandas, Matplotlib, and Seaborn.

### 2. Individual Assignments (A191702 - YU YIFAN)

- **Assignment 1**: Focused on fundamental data cleaning, missing value imputations, and feature transformation.

- **Assignment 2**: Comprehensive Exploratory Data Analysis (EDA):
  - **Univariate Analysis**: Evaluated clean price distributions (`Price_Clean`) and outliers using Histograms and Boxplots.
  - **Bivariate & Correlation Analysis**: Examined relationships between clean prices (`Price_Clean`) and inventory levels (`Inventory_Clean`) using Scatterplots and correlation metrics with written analytical insights.

---

## 🔗 Project Links & Resources

- **Google Colab Notebook**: [Open in Colab](https://colab.research.google.com/)
- **GitHub Repository**: [View Code on GitHub](https://github.com/)
- **Medium Article**: [ETL Process for Shopify Online Shopping Website](https://medium.com/)

---

## 🛠️ Prerequisites & Installation

To run the Jupyter Notebooks locally, install the required packages:

```bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 openpyxl jupyter
```

---

## 👥 Author Information

- **Course**: TTTC3213 Data Engineering & Analytics
- **Group**: Group 8
- **Student**: YU YIFAN (Matric No: A191702)
```

---

Just copy and paste the above into a file named `README.md` in your project root. Let me know if you need any modifications!
