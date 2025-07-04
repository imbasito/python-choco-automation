# Python Automation: Chocolate Sales Data

This project focuses on using Python to automate reporting, analyze trends, and visualize chocolate sales data from a CSV extract of the Awesome Chocolates database.

## Tools & Libraries
- Python
- Pandas
- matplotlib

## What I Built
- Custom functions to summarize product discounts and pricing
- Data cleaning pipeline using Pandas
- Grouped sales by product, region, and month
- Visualizations (bar charts, line graphs) for trend insights

## Folders
- `/scripts` → Python `.py` scripts (functions, loops, cleaning)
- `/charts` → Output PNG charts from matplotlib
- `/data` → Sample or mock dataset in CSV

## Sample Function
```python
def discounted_summary(product_name, amount=0, discount=0):
    final = amount - discount
    return f"{product_name} | Rs.{amount} → Rs.{final}"
