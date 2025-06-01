# 🛍️ Customer and Product Insights on Chip Purchasing Behavior

## 🗂 Project Overview

This repository presents a data-driven analysis conducted as part of the Quantium Virtual Internship – Retail Strategy and Analytics (Task 1). The project explores transactional data to uncover customer and product-level insights, driving strategic recommendations to enhance retail decision-making.

Through segmentation, purchase behavior, and time-series trend analysis, the objective was to support category managers with actionable intelligence that can optimize pricing strategies, promotions, inventory decisions, and customer targeting initiatives.

---

## 👥 1. Customer Segmentation Insights

The dataset was segmented by **Lifestage** and **Customer Type** (Budget, Mainstream, Premium) to identify core consumer groups and their purchasing dynamics.

- **Older Families – Budget** ranked as the top-spending segment, generating over **$168,000** in revenue.
- **Young Singles/Couples – Mainstream** and **Retirees – Mainstream** were also significant contributors.
- Premium customers exhibited fewer transactions but higher **spend per transaction**, reflecting strong brand loyalty and preference for high-value SKUs.
- Budget segments like **Young Families** and **Older Singles** demonstrated steady purchase frequencies, suggesting consistent demand patterns.

---

## 📦 2. Product-Level Insights

Analysis across products and customer segments revealed patterns in consumer preferences:

- Top-selling products included **"Natural Chip Compny SeaSalt175g"** and **"Smiths Crinkle Cut Chips Chicken 170g"**.
- These products performed well across **Mainstream Retirees** and **Budget Older Families**.
- A heatmap visualized clear correlations between segment type and product preference, offering opportunities for hyper-targeted marketing.
- Premium products retained high per-transaction value across all customer types, validating the pricing strategy for select SKUs.

---

## 🛒 3. Basket Size & Frequency

Insights into customer shopping behavior per visit and over time highlighted:

- **Young Singles/Couples – Premium** recorded the highest average basket size (**>$7.90** per transaction).
- **Budget customers** exhibited more frequent purchases but spent less per visit, likely reflecting value-seeking behavior.
- High-value customers averaged **12+ transactions**, spending consistently between **$6.00 and $7.50**, indicating loyalty and habitual purchase cycles.

---

## 📆 4. Time-Series Trend Analysis

Temporal sales analysis uncovered peak performance periods:

- **Sunday** emerged as the highest grossing day (**$283,276.45**), with **Friday** and **Wednesday** following.
- On a monthly scale, **December 2018** led with **$167,741.00** in sales—highlighting festive season demand.
- **Weekdays** drove **$1.37M** in sales versus **$558K** on weekends, indicating routine-based shopping behavior linked to workweek patterns.

---

## ✅ Strategic Recommendations

- Focus marketing campaigns on **Older Families** and **Retirees** in **Budget/Mainstream** segments using value-driven bundles.
- Design retention strategies for **Premium customers**, such as loyalty tiers or first-look access to new flavors.
- Launch major promotions mid-week to Friday to align with observed peak shopping periods.
- Stock up and plan promotions in **December and March**, where seasonal spikes in sales are evident.

---

## 📌 Conclusion

This end-to-end analytics project demonstrates how transactional data can unlock deep customer and product insights. Leveraging segmentation, behavioral metrics, and temporal analysis, the study provides a clear foundation for strategic planning in the retail snack category.

---

## 💻 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Data wrangling, visualization, and segmentation techniques

---

## 📁 Repository Structure



## 🗂 Repository Structure

```bash
PyDataLab/
│
├── data/                 # Contains raw and processed datasets
│   ├── QVI_transaction_data.xlsx
│   ├── QVI_purchase_behaviour.csv
│
├── notebooks/            # Jupyter notebooks for step-by-step analysis
│   └── Task_1.ipynb
│
├── visualizations/       # Saved graphs and exported visuals
│   └── sales_by_segment.png
│   └── trend_analysis.png
│
├── README.md             # Project summary and documentation
