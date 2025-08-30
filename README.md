# 📒 Python for Data Science & AI Module – Strategic Growth Analysis

**Team Project | Semester 3, 2025**  
**Project Title:** Strategic Growth Analysis for a UK-Based E-Commerce Retailer (Unique Gifts Ltd.)

---

## 🚀 Project Overview

This repository contains a **hands-on collaborative project** for the Python for Data Science & AI module (ITS 2122). The focus is on performing a **data-driven strategic analysis** for the UK-based online retailer, **Unique Gifts Ltd.**, using real transactional data.  

The project demonstrates **end-to-end data science workflows**, from data cleaning and EDA to advanced analytics and business-focused insights.

**Objectives:**

- 📈 Analyze sales trends, seasonality, and growth patterns  
- 🛍️ Optimize product portfolio (high-volume vs. high-revenue items)  
- 🌍 Map geographic footprint and international opportunities  
- 💳 Segment customers using RFM analysis  
- 🏢🛒 Distinguish retail vs. wholesaler behavior  
- 💱 Enrich data using external API (currency conversion)  
- 📝 Produce actionable recommendations for strategic decision-making  

---

## 📁 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `online_retail.csv` | Raw online retail transactional dataset |
| `online_retail_cleaned.csv` | Cleaned and preprocessed dataset |
| `unique_gifts_ltd.ipynb` | Jupyter Notebook covering EDA, cleaning, analysis, visualizations, and RFM segmentation |
| `README.md` | Project overview, setup instructions, and contribution guidelines |

---

## 🛠 Getting Started

Clone this repository and move into its directory:

```bash
git clone https://github.com/pasindipamodagamage/Python-for-Data-Science-and-AI-Module.git
cd Python-for-Data-Science-and-AI-Module


Ensure you have **Python 3.9+** and the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn requests
```

---

## 🌿 Branching & Workflow

Follow this branch naming pattern for consistency:

```
<type>/<short-description>/<group-member-name>/<YYYYMMDD>
```

* **type:** `feature`, `bugfix`, `hotfix`, `chore`
* **short-description:** brief hyphen-separated task summary
* **your-name:** GitHub handle or full name
* **YYYYMMDD:** current date

**Example:**

```bash
git checkout -b feature/data-cleaning/pasindi/20250830
git push -u origin feature/data-cleaning/pasindi/20250830
```

This ensures clear collaboration and maintainable project history.

---

## 🧩 Analysis Phases

This project follows a structured, **phase-wise data analysis workflow**:

### Phase 1: Data Cleaning & Preprocessing 🧹
- Remove missing Customer IDs and canceled orders.  
- Filter out non-product codes and zero-priced items.  
- Convert data types, create `TotalPrice`, and extract date features (`Year`, `Month`, `DayOfWeek`, `Hour`).  

### Phase 2: Exploratory Data Analysis (EDA) 📊
- Analyze **sales trends**: monthly, daily, and hourly revenue patterns.  
- Visualize **geographic footprint** and UK vs international sales.  
- Evaluate **top products** by quantity and revenue.

### Phase 3: RFM Customer Segmentation 💳
- Calculate **Recency, Frequency, and Monetary (RFM)** metrics per customer.  
- Visualize distributions and identify high-value customer segments.  

### Phase 4: Strategic Insights & Recommendations 📝
- Identify **retail vs. wholesaler customers**.  
- Provide actionable **business strategies** for different customer segments.  

### Phase 5: Data Enrichment via API 🌐
- Integrate **currency conversion API** to enrich transaction data.  
- Add USD and EUR equivalents for top transactions to support international analysis.

---

## 🤝 Contribution Guidelines

1. **Fork** the repository
2. **Create a branch** following the naming convention
3. **Implement changes** with clear code and comments
4. **Test** your modifications thoroughly
5. **Submit a Pull Request (PR)** with:

   * Description of changes
   * Justification for edits
   * Screenshots or sample outputs (if applicable)

**Code Style:**

* Follow **PEP 8 standards** for Python
* Include Markdown explanations for clarity in notebooks

---

## 📜 Acknowledgments

### Acknowledgments
- **Python Libraries:** pandas, numpy, matplotlib, seaborn, requests  
- **Team Members:** All contributors to data cleaning, analysis, and reporting

---


