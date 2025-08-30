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
<type>/<short-description>/<your-name>/<YYYYMMDD>
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

## 🔍 Analysis Phases

The project follows a **phased approach**:

1. **Data Cleaning & Preprocessing** 🧹

   * Handle missing values, duplicates, cancellations
   * Correct data types, generate `TotalPrice`, extract temporal features

2. **Exploratory Data Analysis (EDA)** 📊

   * Temporal analysis: monthly/yearly trends, peak hours/days
   * Product performance: top 10 by quantity vs. revenue
   * Geographic analysis: top countries, domestic vs. international revenue

3. **Advanced Analytics – RFM Segmentation** 💳

   * Calculate Recency, Frequency, Monetary metrics per customer
   * Assign quintile-based RFM scores
   * Map segments to business-friendly categories (Champions, Loyal, At-Risk, etc.)

4. **Strategic Recommendations** 📝

   * Investigate retail vs. wholesaler purchasing patterns
   * Recommend targeted strategies for marketing, retention, and inventory

5. **Data Enrichment via API Integration** 💱

   * Fetch daily USD and EUR exchange rates via API
   * Convert top transactions’ revenue for multi-currency insights

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
