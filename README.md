# Superstore Sales Analysis

Exploratory Data Analysis (EDA) and visualization of the classic Superstore sales dataset using Python (Pandas, Matplotlib).

## Project Structure

```
superstore-sales-analysis/
├── data/                  # Place SuperStore_Sales_Dataset.csv here
├── notebooks/
│   ├── Analysis.ipynb     # Full exploratory analysis (customers, products, regions, time)
│   ├── Analysis3.ipynb    # Date conversion and shipping trends
│   ├── Plots.ipynb        # Visualization of sales & profit trends
│   └── Pandasin10minutes.ipynb  # Quick pandas practice
├── reports/
│   └── sales_report.xlsx  # Sample sales/profit summary
└── README.md
```

## Dataset

Download the Superstore Sales Dataset (CSV) and place it in the `data/` folder as `SuperStore_Sales_Dataset.csv`.

The notebooks expect columns such as: Order ID, Order Date, Ship Date, Customer_Name, Segment, Region, Category, Sub-Category, Sales, Quantity, Profit, Payment_Mode, etc.

## How to run

1. Clone the repo
2. Place the CSV in `data/`
3. Open the notebooks in Jupyter / VS Code / Colab

## Analysis Highlights

- Customer analysis (top spenders, most frequent buyers)
- Product & Category performance (Furniture, Office Supplies, Technology)
- Regional sales & profit comparison
- Shipping mode and payment method insights
- Monthly / yearly sales and profit trends
- Visualizations of key business metrics

## Learning Goals (GitHub workflow practice)

- Small, meaningful commits
- Feature branches
- Pull Requests with clear descriptions
- Clean project organization
