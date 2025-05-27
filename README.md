# UTM Conversion Analysis from Web and CRM Data

This project explores the relationship between user web activity and conversion outcomes using synthetic CRM and web tracking datasets.

The analysis focuses on identifying top-performing UTM sources based on:
- Number of unique users
- Total time spent on the website
- Conversion rate (from CRM `lead_status = "Converted"`)

## 🧪 Key Objectives

1. Clean and merge multi-source data (CRM + web tracking)
2. Calculate key metrics grouped by `utm_source`
3. Visualize relationships between engagement and conversion performance
4. Present findings via clean dashboards and charts

## 📊 Tools & Libraries

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## 📁 Structure

- `notebook.ipynb`: full workflow with analysis and visualizations
- `/data`: raw input files (CRM + web tracking)
- `/images`: charts used in presentation or dashboard
