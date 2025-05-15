# E-Commerce Sales Analysis 🛒📊

> End-to-end data analysis of e-commerce sales using Python, Pandas, Matplotlib, and Seaborn — covering EDA, product ranking, regional breakdowns, trend analysis, and business recommendations.
>
> ![Python](https://img.shields.io/badge/Python-3.10+-blue)
> ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
> ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
> ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-purple)
> ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
>
> ---
>
> ## 📌 Project Overview
>
> This project performs a complete sales analytics pipeline on a multi-category e-commerce dataset. Starting from raw CSV data, it delivers actionable business insights through data cleaning, aggregation, visualization, and a structured recommendations report.
>
> **Business Questions Answered:**
> - Which products drive the most revenue?
> - - Which regions generate the highest sales?
>   - - How have sales trended over time?
>     - - Which categories are underperforming?
>       - - Where should the business focus its growth efforts?
>        
>         - ---
>
> ## 📁 Repository Structure
>
> ```
> Ecommerce-sales-analysis/
> ├── ecommerce_ analysis. ipynb      # Main Jupyter notebook (10 analysis steps)
> ├── ecommerce_sample_dataset.csv    # Dataset: OrderID, Product, Category, Sales, Quantity, OrderDate, Region
> └── README.md                       # Project documentation
> ```
>
> ---
>
> ## 📊 Dataset
>
> | Column | Type | Description |
> |--------|------|-------------|
> | `OrderID` | Integer | Unique order identifier |
> | `Product` | String | Product name (Shirt, Phone, Shoes, Laptop, Headphones) |
> | `Category` | String | Product category (Apparel, Electronics, Footwear) |
> | `Sales` | Float | Revenue from the order ($) |
> | `Quantity` | Integer | Units ordered |
> | `OrderDate` | Date | Date the order was placed |
> | `Region` | String | U.S. region (New York, Texas, California, Florida) |
>
> ---
>
> ## 🔍 Analysis Steps
>
> | Step | Description |
> |------|-------------|
> | 1 | Import libraries and configure plotting |
> | 2 | Load dataset and inspect shape/columns |
> | 3 | Data quality checks (missing values, duplicates, negative sales) |
> | 4 | Descriptive statistics and key business metrics |
> | 5 | Top products by total revenue (ranked bar chart) |
> | 6 | Regional sales breakdown (pie + bar charts) |
> | 7 | Daily sales trend with 7-day rolling average |
> | 8 | Category-level performance (revenue + units sold) |
> | 9 | Revenue vs Quantity scatter plot by product |
> | 10 | Auto-generated insights and business recommendations |
>
> ---
>
> ## 📈 Key Visualizations
>
> - **Horizontal bar chart** — Products ranked by total revenue
> - - **Pie + bar chart** — Revenue share and absolute value by region
>   - - **Line chart** — Daily sales trend with 7-day rolling average overlay
>     - - **Grouped bar charts** — Category revenue and units sold
>       - - **Scatter plot** — Revenue vs Quantity by product, colored by category
>        
>         - ---
>
> ## 🛠️ Tech Stack
>
> | Tool | Purpose |
> |------|---------|
> | Python 3.10+ | Core language |
> | Pandas | Data loading, cleaning, aggregation |
> | NumPy | Numerical operations |
> | Matplotlib | Base charts and formatting |
> | Seaborn | Color palettes and styling |
>
> ---
>
> ## 🚀 Getting Started
>
> ```bash
> # Clone the repo
> git clone https://github.com/kamjula/Ecommerce-sales-analysis.git
> cd Ecommerce-sales-analysis
>
> # Install dependencies
> pip install pandas numpy matplotlib seaborn
>
> # Open the notebook
> jupyter notebook "ecommerce_ analysis. ipynb"
> ```
>
> ---
>
> ## 💡 Sample Insights
>
> The analysis auto-generates a recommendations report at the end of the notebook, including:
>
> - **Best-performing product** by revenue share
> - - **Top region** for sales concentration
>   - - **Underperforming category** flagged for promotion review
>     - - **Actionable next steps** for inventory planning and cross-sell strategy
>      
>       - ---
>
> ## 👤 Author
>
> **Sravani Kamjula** — Data Analyst
> [LinkedIn](https://www.linkedin.com/in/sravani-kamjula-763285176/) | [GitHub](https://github.com/kamjula) | [Portfolio](https://sravanikamjula.netlify.app)
