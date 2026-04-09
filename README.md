
# UCI Online Retail Analysis

## Project Description
This project analyzes the **UCI Online Retail Dataset**, a real-world dataset of UK-based online store transactions. The goal is to clean the data, compute revenue metrics, and visualize insights such as the top 10 countries by revenue. This simulates a real-world business analytics workflow.

---

## Project Requirements
- Sample 10% of rows for manageability
- Clean the data:
  - Remove nulls
  - Fix data types
  - Filter out returns and free items
- Convert `InvoiceDate` to datetime
- Create a `Revenue` column (Quantity × UnitPrice)
- Find and visualize the top 10 countries by total revenue

---

## Technologies Used
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## How to Run

Go to Google Colab
1. Click File → Open notebook → GitHub.
2. Enter your repository URL:
https://github.com/sandhyabastola/uci_online_retail_analysis
3. Open retail_analysis.ipynb and run all cells.