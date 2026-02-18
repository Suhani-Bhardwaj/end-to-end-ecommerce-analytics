# 🛒 End-to-End Ecommerce Analytics & Customer Segmentation (RFM)

## 📌 Project Overview

This project performs a complete end-to-end analysis of an ecommerce retail dataset to uncover business insights, understand customer purchasing behavior, and segment customers using RFM (Recency, Frequency, Monetary) analysis.

The objective of this project is to simulate a real-world business analytics workflow — starting from raw data cleaning to advanced customer segmentation and interactive dashboard visualization.

This project demonstrates core data analyst skills including:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Segmentation (RFM)
- Business Dashboard Development
  
## 🎯 Business Problem

Ecommerce businesses generate large volumes of transactional data, but without analysis it is difficult to answer key questions such as:

- Who are the most valuable customers?
- Which products generate the highest revenue?
- How does revenue change over time?
- Which customers are at risk of churn?
- How can customers be segmented for targeted marketing?

This project addresses these questions using data analytics and business intelligence techniques.

## 📊 Dataset Information

The dataset contains ecommerce transaction records with the following columns:

- InvoiceNo – Unique transaction ID  
- StockCode – Product code  
- Description – Product name  
- Quantity – Number of units purchased  
- InvoiceDate – Transaction timestamp  
- UnitPrice – Price per unit  
- CustomerID – Unique customer identifier  
- Country – Customer location  

### 🔹 Feature Engineering

A new column was created:

Revenue = Quantity × UnitPrice

## 🛠 Tools & Technologies Used

**Python**
- Pandas – Data manipulation & cleaning
- NumPy – Numerical operations
- Matplotlib & Seaborn – Data visualization

**Power BI**
- Interactive dashboard creation
- KPI visualization
- Customer segmentation insights

**Google Colab / Jupyter Notebook**
- Data analysis environment

**GitHub**
- Project hosting & portfolio showcase

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Removed missing CustomerID values
- Removed duplicates
- Handled null descriptions
- Converted InvoiceDate to datetime
- Created Revenue column

## Output:

cleaned_retail_data.csv

### 2️⃣ Exploratory Data Analysis (EDA)

Analyzed key metrics:
- Total Revenue
- Revenue trends over time
- Top products by revenue
- Revenue distribution
- Country-wise revenue analysis

### 3️⃣ RFM Customer Segmentation

Created three customer metrics:

**Recency**
- Days since last purchase  
- Lower value = More recent customer  

**Frequency**
- Number of purchases  
- Higher value = More loyal customer  

**Monetary**
- Total amount spent  
- Higher value = More valuable customer  

Customers were segmented into:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk Customers
- Lost Customers

## Output:

rfm_customer_segments.csv

## 📈 Power BI Dashboard

An interactive dashboard was created showing:

- Total Revenue (KPI Card)
- Monthly Revenue Trend
- Top Products by Revenue
- Revenue by Country
- Customer Segment Distribution

This dashboard enables business stakeholders to quickly understand performance and customer behavior.

## 📂 Project Structure

end-to-end-ecommerce-analytics/

│
├── data/
│   ├── cleaned_retail_data.csv
│   └── rfm_customer_segments.csv
│
├── notebook/
│   └── ecommerce_analysis.ipynb
│
├── dashboard/
│   └── ecommerce_dashboard.pbix
│
├── screenshots/
│   └── sales-dashboard.png
│
└── README.md

## 💡 Key Insights

- A small percentage of customers contribute to majority of revenue
- Certain products consistently generate high sales
- Some customers are inactive and at risk of churn
- Loyal customers significantly drive revenue growth
- Revenue shows monthly and seasonal patterns

## 🚀 Business Impact

This project demonstrates how data analytics can help businesses:

- Identify high-value customers
- Improve customer retention strategies
- Optimize marketing campaigns
- Increase revenue through data-driven decisions

## 🧠 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation (RFM)
- Feature Engineering
- Business Intelligence
- Dashboard Design
- Python Programming
- Power BI Visualization

## ▶️ How to Run the Project

1. Open the Jupyter Notebook (`ecommerce_analysis.ipynb`)
2. Install required libraries:

pip install pandas numpy matplotlib seaborn

3. Run the notebook step-by-step
4. Open the Power BI dashboard file (`.pbix`) to view interactive visuals

## 🔮 Future Improvements

- Churn prediction model
- Customer Lifetime Value (CLV) prediction
- Automated dashboard updates
- Deployment using Streamlit or Power BI Service

## 👩‍💻 Author

Suhani  
Aspiring Data Analyst  

Skills: Python | SQL | Power BI | Data Analytics | Customer Segmentation

