# TTTC3213 Data Engineering & Analytics Project: Shopify ETL & Exploratory Data Analysis
# TTTC3213 数据工程与分析项目：Shopify ETL 流程与探索性数据分析

---

## 📄 English Version

### 📖 Project Overview
This repository contains the complete codebase, datasets, presentation materials, and analysis reports for the **TTTC3213** course project. It comprises two main components: **Group 8 Team Project** and **Individual Assignments (YU YIFAN - A191702)**.

The project focuses on **Shopify E-commerce platform data**, covering the end-to-end data processing workflow: web scraping (Extract), data cleaning and transformation (Transform), data loading/storage (Load), as well as Exploratory Data Analysis (EDA) and data visualization.

---

### 📁 Directory Structure

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
    ├── TTTC3213 Project Link.docx             # Summary of External Links (Colab / GitHub / Medium)
    ├── shopify_sales_products.csv            # Raw Web-scraped Shopify Product Dataset
    ├── shopify_sales_products_cleaned.csv    # Cleaned & Structured Dataset
    └── shopify_products_vendor_star.csv      # Derived Dataset with Vendor Ratings/Stars

🚀 Key Modules & Workflow
1. Group 8 Team Project: Shopify E-commerce ETL Pipeline & Analysis
Extract: Built Python web scraper scripts to harvest product attributes (Titles, Prices, Vendors, Tags, Inventory Levels, etc.) from Shopify e-commerce sites.

Transform:

Handled missing values, duplicated entries, and price format anomalies.

Extracted and standardized pricing numerical fields and inventory quantities.

Derived vendor rating metrics (shopify_products_vendor_star.csv).

Load & Data Visualization:

Analyzed vendor performance, price distribution, and product categorical popularity using Pandas, Matplotlib, and Seaborn.

2. Individual Assignments (A191702 - YU YIFAN)
Assignment 1: Focused on fundamental data cleaning, missing value imputations, and feature transformation.

Assignment 2: Comprehensive Exploratory Data Analysis (EDA):

Univariate Analysis: Evaluated clean price distributions (Price_Clean) and outliers using Histograms and Boxplots.

Bivariate & Correlation Analysis: Examined relationships between clean prices (Price_Clean) and inventory levels (Inventory_Clean) using Scatterplots and correlation metrics with written analytical insights.

🔗 Project Links & Resources
Google Colab Notebook: Open in Colab

GitHub Repository: View Code on GitHub

Medium Article: ETL Process for Shopify Online Shopping Website

🛠️ Prerequisites & Installation
To run the Jupyter Notebooks locally, install the required packages:

Bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 openpyxl jupyter
📄 中文版
📖 项目概述
本项目为 TTTC3213 课程的全套成果库，包含 Group 8 团队项目 与 个人作业（YU YIFAN - A191702） 的完整代码、数据集、演示文稿以及分析报告。

项目核心围绕 Shopify 电商平台数据 展开，实现了完整的端到端数据工程与分析流程：网络数据爬取（Extract）、数据清洗与转换（Transform）、数据加载与保存（Load），以及探索性数据分析（EDA）和数据可视化。

📁 目录结构说明
Plaintext
.
├── A191702 Individual Assignment/             # 个人作业目录 (Yu Yifan - A191702)
│   ├── INDIVIDUAL_ASSIGMENT_1_YU_YIFAN_A191702.ipynb  # 作业 1：数据预处理与清洗
│   ├── INDIVIDUAL_ASSIGMENT_2_YU_YIFAN_A191702.ipynb  # 作业 2：EDA、可视化与相关性分析
│   └── shopify_sales_products.csv            # 个人作业原始数据集
│
└── TTTC3213_Group8_Project/                  # Group 8 团队项目目录
    ├── TTTC3213_Group_Project.ipynb          # 团队项目主代码（网络爬虫、ETL与可视化）
    ├── ETL Process for Shopify Online Shopping Website.pdf   # 项目报告 PDF
    ├── ETL Process for Shopify Online Shopping Website.pptx  # 汇报演示文稿 PPTX
    ├── TTTC3213 Project Link.docx             # 项目外部资源链接汇总 (Colab / GitHub / Medium)
    ├── shopify_sales_products.csv            # 抓取的原始 Shopify 商品数据
    ├── shopify_sales_products_cleaned.csv    # 转换清洗后的结构化数据集
    └── shopify_products_vendor_star.csv      # 包含 Vendor 评分/星级信息的衍生数据集
🚀 项目核心模块与工作流
1. Group 8 团队项目：Shopify 电商 ETL 流程与数据分析
数据提取 (Extract): 使用 Python 编写 Web 爬虫，自动采集 Shopify 平台的商品数据（商品名称、价格、供应商 Vendor、标签 Tag、库存等）。

数据转换 (Transform):

清理缺失值、重复数据与异常价格格式。

标准化数值型字段，提取结构化特征。

计算并衍生 Vendor 供应商星级评价指标（shopify_products_vendor_star.csv）。

数据加载与可视化 (Load & Visualization):

使用 Pandas、Matplotlib 和 Seaborn 进行数据可视化，分析热门商品分类、供应商定价策略及库存分布。

2. 个人作业 (A191702 - YU YIFAN)
Individual Assignment 1: 重点进行基础数据清洗、缺失值处理及数据类型转换。

Individual Assignment 2: 深入探索性数据分析（EDA）：

单变量分析: 使用直方图（Histogram）与箱线图（Boxplot）分析商品清洗价格（Price_Clean）的分布形态与异常值。

双变量/相关性分析: 构建散点图（Scatterplot）及相关性矩阵，深入探究价格与库存（Inventory_Clean）之间的线性与非线性关系，并撰写详细报告。

🔗 在线资源与参考链接
Google Colab 代码运行环境: 在线打开 Colab Notebook

GitHub 代码仓库: 查看 GitHub 项目

Medium 项目详细报告: 阅读 ETL Process 文章

🛠️ 环境依赖与安装说明
运行项目 Notebook 代码前，请确保 Python 环境中已安装以下依赖库：

Bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 openpyxl jupyter
👥 Author / 作者信息
Course / 课程: TTTC3213 Data Engineering & Analytics

Group / 团队: Group 8

Student / 学生: YU YIFAN (Matric No: A191702)
