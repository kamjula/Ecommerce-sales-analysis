# E-Commerce Sales Analysis

I built this project to practice end-to-end data analysis on a realistic e-commerce dataset. The goal was to go from raw sales data all the way to actual business insights — not just clean data, but answers to real questions a business would care about.

## What I worked on

The dataset has orders with product, category, sales amount, quantity, date, and region. I ran 10 steps of analysis in a Jupyter notebook covering:

- Data cleaning (missing values, duplicates, negative sales)
- - Top products by revenue
  - - Regional sales breakdown
    - - Daily sales trends with rolling averages
      - - Category performance
        - - Revenue vs quantity scatter analysis
          - - Auto-generated business recommendations at the end
           
            - ## Tools used
           
            - Python, Pandas, NumPy, Matplotlib, Seaborn
           
            - ## How to run it
           
            - ```bash
              git clone https://github.com/kamjula/Ecommerce-sales-analysis.git
              cd Ecommerce-sales-analysis
              pip install pandas numpy matplotlib seaborn
              jupyter notebook "ecommerce_ analysis. ipynb"
              ```

              ## Files

              | File | What it is |
              |------|-----------|
              | `ecommerce_ analysis.ipynb` | Main notebook with all 10 analysis steps |
              | `ecommerce_sample_dataset.csv` | The dataset (OrderID, Product, Category, Sales, Quantity, Date, Region) |
              | `requirements.txt` | Dependencies |

              ---

              Made by Sravani Kamjula
