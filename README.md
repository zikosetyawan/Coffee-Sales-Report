# Coffee Sales Performance Analysis

This project analyzes coffee shop sales data to support **data-driven operational
and marketing decisions**, with a focus on staffing optimization, product performance,
and time-based revenue patterns.

The analysis aims to help management increase transaction frequency during off-peak
hours and maximize revenue from top-performing products during peak periods.

---

## Business Problem

How can a coffee shop allocate resources and promotional strategies optimally to:
- Increase transaction frequency by **15% during off-peak hours**
- Increase total revenue from the **top 3 products by 10% during peak hours**
within the next **30 days**, based on historical sales data?

---

## Dataset

- **Source**: [Coffee Sales Dataset](https://www.kaggle.com/datasets/anassarfraz13/coffee-sales-dataset)
- **Description**: Transaction-level coffee sales data containing information on
  time of purchase, product type, payment method, and revenue.
- The dataset was cleaned and preprocessed prior to analysis.

---

## Objectives

The objectives of this analysis are to:
1. Identify peak and off-peak sales hours to support staffing decisions.
2. Analyze sales patterns across days and time periods.
3. Determine top coffee products contributing the most to total revenue.
4. Evaluate whether revenue differences across time of day are statistically significant.
5. Provide actionable recommendations for staffing and promotion strategies.

---

## Key Insights

- Peak revenue consistently occurs between **18:00–20:00**, while morning hours
  tend to be off-peak.
- Day–hour heatmap analysis reveals stable and repeatable demand patterns.
- **Latte, Americano with Milk, and Cappuccino** are the top contributors to total revenue.
- Payment method analysis shows no variation, indicating limited impact on decision-making.
- Inferential statistical testing (one-way ANOVA) confirms that revenue differences
  across time of day are **statistically significant (p < 0.001)**.

---

## Dashboard

The Tableau dashboard focuses on **business and operational insights**, intentionally
prioritizing clarity and actionability over statistical complexity.

[Dashboard Preview](https://public.tableau.com/app/profile/muhammad.ziko.ananda.setyawan/viz/Coffee_Sales_17668420189440/CoffeeSalesDashboard)

Key dashboard components include:
- Average revenue by hour
- Day–hour revenue heatmap
- Top products by total revenue
- Key insights and recommendations panel

---

## Statistical Validation

Time-based revenue differences were validated using **one-way ANOVA**, confirming that
observed peak and off-peak patterns are not due to random variation and can be used as
a reliable basis for operational decisions.

---

## Tools & Technologies

- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Visualization**: Tableau Public
- **Environment**: Jupyter Notebook

---

## Project Structure
The project is organized as follows:

- `dataset/`  
  Contains the original, unmodified dataset and Contains the cleaned dataset used for analysis.

- `coffee_sales_analysis.ipynb`  
  Contains the main analysis notebook.

This structure ensures clear separation between raw data, processed data,
analysis, and visualization outputs.

## Conclusion

This project demonstrates how historical sales data can be transformed into actionable
insights for staffing and promotional planning. By combining exploratory analysis,
visualization, and statistical validation, the analysis provides a strong foundation
for achieving targeted improvements in transaction frequency and revenue performance.