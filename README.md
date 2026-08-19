# 🎓 Data Engineering & Analytics Project: Shopify ETL & Exploratory Data Analysis

## 📖 TTTC3213 Project Overview

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

### 1. Team Project: Shopify E-commerce ETL Pipeline & Analysis

- **Extract**: Built Python web scraper scripts to harvest product attributes (Titles, Prices, Vendors, Tags, Inventory Levels, etc.) from Shopify e-commerce sites.

- **Transform**:
  - Handled missing values, duplicated entries, and price format anomalies.
  - Extracted and standardized pricing numerical fields and inventory quantities.
  - Derived vendor rating metrics (`shopify_products_vendor_star.csv`).

- **Load & Data Visualization**:
  - Analyzed vendor performance, price distribution, and product categorical popularity using Pandas, Matplotlib, and Seaborn.

### 2. Individual Assignments 

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

## 🚀 项目核心内容 (Project Highlights)

### 1. 团队项目: Shopify 电商数据 ETL 流程与分析

* **数据提取 (Extract):** 编写 Python Web 爬虫脚本，自动采集 Shopify 平台上商品的相关数据（标题、价格、供应商 Vendor、标签 Tag、库存状态等）。
* **数据转换与清洗 (Transform):**
* 处理缺失值、重复项与异常数据。
* 清洗并标准化商品价格、库存量，提炼 Vendor/Tag 维度数据。
* 生成 Vendor 星级指标（`shopify_products_vendor_star.csv`）。


* **数据加载与可视化 (Load & Data Visualization):**
* 使用 `Pandas`、`Matplotlib` 和 `Seaborn` 构建可视化图表。
* 分析热门商品分类、不同供应商的定价策略、库存分布与销售潜力。



### 2. 个人作业 (Individual Assignments)

* **Assignment 1:** 重点关注数据集的基础清理、字段类型转换与缺失值填补策略。
* **Assignment 2:** 深入的探索性数据分析（EDA）：
* **单变量分析:** 利用直方图（Histogram）和箱线图（Boxplot）分析商品价格（`Price_Clean`）的分布特征及离群值。
* **双变量/相关性分析:** 构建散点图（Scatterplot）与相关性矩阵，深入探究商品价格与库存量（`Inventory_Clean`）之间的线性与非线性关系，并撰写详细分析报告（Report Explanation）。



---

## 🔗 在线资源与参考链接 (Project Links)

* **Google Colab 交互式运行环境:** [Colab Notebook](https://www.google.com/search?q=https://colab.research.google.com/drive/1xJ1Nc_mclZIMo-6BTUsupnPjgMsMTY6m%3Fusp%3Dsharing)
* **GitHub 代码仓库:** [GitHub Repository](https://www.google.com/search?q=https://github.com/Christophery0614/School-Project/tree/ccadc293c8a25f3e1d81f8c9e6d32431e0ba0e82/TTTC3213_Group_Project)
* **Medium 项目详细报告:** [ETL Process for Shopify Online Shopping Website](https://www.google.com/search?q=https://medium.com/%40a191702/etl-process-for-shopify-online-shopping-website-072a1c326cf0)

---

## 🛠️ 环境准备与运行说明 (Getting Started)

### 依赖库安装

在运行 `.ipynb` Notebook 之前，请确保 Python 环境中已安装以下主要依赖包：

```bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 openpyxl jupyter

```

### 运行方式

1. **运行团队项目:**
启动 Jupyter Notebook 或打开 Google Colab，运行 `TTTC3213_Group8_Project/TTTC3213_Group_Project.ipynb`，即可按顺序体验数据爬取、ETL 清洗及图表生成。
2. **运行个人作业:**
进入 `A191702 Individual Assignment/` 目录，按顺序运行 `INDIVIDUAL_ASSIGMENT_1...ipynb` 与 `INDIVIDUAL_ASSIGMENT_2...ipynb`。

---

## 👤 作者信息 (Author & Team)

* **课程名称:** TTTC3213 Data Engineering / Data Analytics
* **团队名称:** Group 8
* **个人贡献者:** YU YIFAN (Matric No: A191702)



