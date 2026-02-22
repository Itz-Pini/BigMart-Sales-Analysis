# 📊 BigMart Sales Analysis & Revenue Insights

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the BigMart Sales dataset to identify key factors influencing product sales across different outlets. The analysis focuses on understanding how outlet characteristics, product attributes, and operational factors impact overall revenue performance.

The goal of this project is to derive actionable business insights that support data-driven decision-making in retail sales optimization.

---

## 🎯 Business Objective

The primary objectives of this analysis are:

- Identify high-performing outlet types and sizes  
- Analyze product categories contributing most to revenue  
- Evaluate the impact of product visibility and fat content on sales  
- Understand how outlet establishment year influences sales trends  

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset Information

- **Dataset Name:** BigMart_Sales  
- **Source:** Kaggle: https://www.kaggle.com/code/mairedaai/bigmart-sales/input?select=Train.csv
- **Total Records:** ~8,500+  
- **Key Features:**
  - Item Type  
  - Item Weight  
  - Item Visibility  
  - Item Fat Content  
  - Outlet Type  
  - Outlet Size  
  - Outlet Location Type  
  - Outlet Establishment Year  
  - Sales  

---

## 📊 Key Performance Indicators (KPIs)

- Total Sales  
- Average Sales per Item  
- Sales by Outlet Type  
- Sales by Outlet Size  
- Sales by Product Category  
- Sales by Establishment Year  

---

## 📈 Exploratory Data Analysis Performed

### 1️⃣ Data Understanding
- Dataset structure review  
- Data types validation  
- Missing value detection  
- Duplicate record check  

### 2️⃣ Data Cleaning
- Handling missing values  
- Standardizing categorical variables  
- Ensuring feature consistency  

### 3️⃣ Univariate Analysis
- Sales distribution  
- Product category distribution  
- Outlet size and type frequency  

### 4️⃣ Bivariate Analysis
- Item Type vs Sales  
- Outlet Type vs Sales  
- Outlet Size vs Sales  
- Fat Content vs Sales  
- Visibility vs Sales  

### 5️⃣ Correlation Analysis
- Identified relationships between numerical features  
- Evaluated strength of linear correlations  

---

## 📌 Key Business Insights

- Supermarket-type outlets generate higher average sales compared to smaller outlet formats.  
- Medium-sized outlets contribute strong and consistent revenue performance.  
- Certain product categories consistently outperform others in total sales.  
- Extremely low or high product visibility does not significantly increase sales.  
- Fat content segmentation has minimal influence on overall revenue trends.  

---

## ✅ Conclusion

The analysis demonstrates that outlet characteristics and product categories significantly influence overall sales performance. Strategic focus on high-performing outlet types and optimized inventory planning can enhance revenue generation and operational efficiency.

This project highlights the importance of data-driven decision-making in retail sales optimization.

---

## 📊 Sample Visualizations
### Sales Distribution
![Sales Distribution](images/sales_distribution.png)

### Sales by Outlet Type
![Outlate_identifier](https://github.com/user-attachments/assets/e876a1e8-5172-4141-bd24-a2894f55f4c5)
### Sales by Item Type
![Item_type](https://github.com/user-attachments/assets/f10e33fb-fb49-4096-a585-8257a66c33dd)
### Sales by Item MRP Category
![Item_MRP_category](https://github.com/user-attachments/assets/6751c418-1f57-44cc-81de-3c60dba7d6f0)


---

## 📁 Project Structure

BigMart-Sales-Analysis/
│
├── data/
│   └── BigMart_Sales.csv
│
├── notebooks/
│   └── BigMart_EDA.ipynb
│
├── images/
│   ├── sales_distribution.png
│   └── outlet_sales.png
│
├── README.md
└── requirements.txt

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install required libraries  

pip install -r requirements.txt  

3. Open Jupyter Notebook  
4. Run `BigMart_EDA.ipynb`  

---

## 👤 Author

**Ashwini Kumar Sahu**   

- LinkedIn: https://www.linkedin.com/in/ashwini-kumar-sahu-0520b52b8 
- GitHub: https://github.com/Itz-Pini 
