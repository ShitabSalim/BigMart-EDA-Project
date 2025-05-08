# 📊 BigMart Sales Data Analysis

This project performs Exploratory Data Analysis (EDA) on the BigMart dataset to understand sales patterns and product/store-level behavior. The goal is to extract useful insights that could help BigMart improve its sales and operations.

---

## 🗂️ Project Structure

- `EDA_on_Bigmart_dataset.ipynb`: Jupyter Notebook containing data analysis, visualizations, and insights.
- `bigmart.csv`: Dataset file used for the analysis.

---

## 📌 Dataset Description

The dataset contains sales data for different items across various outlets.

### Key Features:
- `Item_Identifier`: Unique ID of the product
- `Item_Weight`: Weight of the product
- `Item_Fat_Content`: Low Fat/Regular
- `Item_Visibility`: % of total display area of all products in a store allocated to this product
- `Item_Type`: Category of the product
- `Item_MRP`: Maximum Retail Price
- `Outlet_Identifier`: Unique ID of the store
- `Outlet_Establishment_Year`: Year when the store was established
- `Outlet_Size`: Size of the store (Small/Medium/High)
- `Outlet_Location_Type`: Tier of the location
- `Outlet_Type`: Grocery Store/Supermarket type
- `Item_Outlet_Sales`: Sales of the product in the store (target variable)

---

## 🔍 Exploratory Data Analysis

The EDA includes:
- Data cleaning and handling missing values
- Univariate and multivariate analysis
- Distribution plots and boxplots
- Correlation heatmaps
- Insights and recommendations

---

## 📈 Key Insights

- Sales are strongly influenced by `Item_MRP`.
- Stores established earlier have different sales trends.
- Fat content labeling has inconsistencies that require standardization.
- Smaller stores have higher sales per item visibility.

---

## 🧰 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BigMart-EDA-Project.git
   cd BigMart-EDA-Project
   ```
2. Open the notebook:
  ```bash
jupyter notebook EDA_on_Bigmart_dataset.ipynb
```
