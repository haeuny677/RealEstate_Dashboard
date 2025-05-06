# 🏡 Structuring Real Estate: U.S. Property Database Design

This project builds a comprehensive, scalable real estate database combining demographic, economic, and housing data to support buyer decisions and broker strategies. Designed for ease of use by both analysts and executives, the platform enables cross-domain insights and market intelligence.

## 🎯 Objective
To create a centralized real estate data system that helps buyers find the right home, brokers improve targeting, and executives make strategic decisions.

## 💡 Key Features
- ZIP-level demographic and economic segmentation
- Realtor reliability insights by area
- Cross-linked property, broker, and sale data
- Tableau dashboards for non-technical users
- SQL & Python interfaces for analysts

## 🗂️ Database Design
- **18 tables across 3 domains**: Demographics, Economic Indicators, Property Listings
- 3NF-compliant schema ensures low redundancy and high relational integrity
- Primary/foreign key relationships include: `zipcode_id`, `year`, `broker_id`, `sale_status_id`

## 🔁 ETL Process
- **Extract**: U.S. Census, FRED, Kaggle datasets
- **Transform**: Data cleaning, referential integrity checks, normalization
- **Load**: PostgreSQL with SQLAlchemy integration

## 🧰 Tools Used
- **PostgreSQL**: Data warehousing
- **SQL & SQLAlchemy**: Schema and relationship management
- **Python (Jupyter Notebook)**: Script documentation and analytics
- **Tableau**: Interactive dashboards connected to SQL views

## 👥 User Experience
### Analysts
- Full SQL access and Python analytics
- Complex querying across linked datasets

### Executives
- Tableau dashboards for market trends, broker performance, and ZIP-level segmentation
- Decision support tools for expansion, pricing, and marketing

---

> 👩‍💻 Developed by Group 2 – Columbia University, APAN 5310 (Spring 2025)
