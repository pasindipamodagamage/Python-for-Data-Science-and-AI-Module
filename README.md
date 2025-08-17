# Geographic Analysis – Online Retail Dataset

This project analyzes the **geographic footprint** of customers based on the `online_retail_cleaned.csv` dataset.  
It answers key business questions such as:  

- **Where are our most valuable customers located?**  
- **What is the balance between the UK (domestic market) and international sales?**  
- **Which countries represent the best opportunities for international growth?**  

---

## 📊 Analysis Steps

1. **Data Preparation**
   - Load cleaned dataset (`online_retail_cleaned.csv`)
   - Calculate revenue as:  
     ```python
     Revenue = Quantity * Price
     ```
   - Aggregate revenue by country.

2. **Top 10 Countries by Revenue**
   - Sort countries by revenue and select the top 10.
   - Visualized using a **bar chart** with annotated revenue values.

3. **UK vs Non-UK Revenue Share**
   - Calculate UK revenue percentage vs all other countries.
   - Present results in a **pie chart**.

---

## 📈 Visualizations

### Top 10 Countries by Sales Revenue
- Horizontal bar chart showing revenue contribution.
- Highlights which international markets are most valuable.

### UK vs Non-UK Market Balance
- Pie chart visualizing revenue share.
- Provides clear insight into domestic vs international sales.

---
