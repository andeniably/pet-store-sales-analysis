# 🐾 Pet Store Sales Analysis — Data Analytics Portfolio Project

This is a portfolio project created as part of my Python Data Analytics training. It explores transactional sales data from a fictional pet store using the OSEMN data science framework. The goal of this project is to demonstrate my end-to-end data analytics capabilities—data cleaning, exploration, interpretation, and visualization—using real Python code.

---

## 🔍 TL;DR

**Objective:**  
Identify which product categories and pet types drive sales and offer recommendations based on data insights.

**Tools Used:**  
- Python (pandas, seaborn, matplotlib)
- Jupyter Notebook
- CSV for data
- GitHub for version control and sharing

---

## 🧩 Dataset

- `transactions-pet_store-clean.csv`: Cleaned dataset used in this notebook
- Source: Provided via Coursera Lab (fictional but realistic transactional structure)

---

## 📊 Project Highlights

| Section                        | Details |
|-------------------------------|---------|
| **Framework Used**            | OSEMN (Obtain, Scrub, Explore, Model*, Interpret) |
| **Data Cleaning**             | Handled missing values, corrected invalid prices, dropped irrelevant columns |
| **Feature Engineering**       | Added `Subtotal` column (Price × Quantity) |
| **EDA**                       | Visualized category sales, top-selling products per pet type |
| **Interpretation**            | Derived business recommendations for pet product marketing |
| **Modeling**                  | Skipped (not applicable in this scope) |
| **Visualization**             | Comparative bar charts and highlighted insights using Seaborn |

---

## 🧠 Key Business Questions

- What are the most frequently purchased categories for each pet line?
- Which categories are the priciest by median price?
- Which categories are most important for inventory and marketing investment?

---

## 🧪 How to Run

1. Clone this repository
2. Open the notebook in Jupyter Lab/Notebook
3. Make sure `transactions-pet_store-clean.csv` is in the same folder
4. Run the notebook from top to bottom


---

## 📁 File Structure
pet-store-sales-analysis/
├── pet-store-sales-analysis.ipynb # Full annotated notebook
├── transactions-pet_store-clean.csv # Cleaned dataset used in analysis
└── README.md # Project summary (this file)
