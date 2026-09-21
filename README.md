# 📊 Sales & Revenue Analysis Dashboard

An interactive **Power BI dashboard** for analyzing sales and revenue performance using transactional sales data.

## 🎯 Project Objective

The objective of this project is to transform raw sales data into meaningful business insights using **Power BI, Power Query, Excel, and DAX**.

## 🛠️ Tools & Technologies

- Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Visualization

## 📂 Repository Structure

```text
Sales-Revenue-Analysis-Dashboard/
├── README.md
├── Dataset/
│   └── sales_data.xlsx
├── PowerBI/
│   ├── DAX_Measures.txt
│   └── Dashboard_Design.md
├── Screenshots/
│   └── dashboard.png
└── Documentation/
    └── Project_Report.md
```

## 📌 Dataset

The sample dataset contains 600 sales transactions with:

- Order ID
- Order Date
- Product
- Category
- Region
- Quantity
- Unit Price
- Sales
- Discount
- Revenue
- Payment Method

## 📈 Dashboard KPIs

- Total Sales
- Total Revenue
- Total Orders
- Units Sold
- Average Order Value

## 📊 Visualizations

- Monthly Revenue Trend
- Sales by Category
- Top 10 Products by Revenue
- Revenue by Region
- Revenue by Payment Method
- Interactive slicers for date, region, category, product and payment method

## 🧮 Key DAX Measures

```DAX
Total Sales = SUM(Sales[Sales])

Total Revenue = SUM(Sales[Revenue])

Total Orders = DISTINCTCOUNT(Sales[Order ID])

Units Sold = SUM(Sales[Quantity])

Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

## 🔄 Data Workflow

```text
Excel Dataset
     ↓
Power BI
     ↓
Power Query
     ↓
Data Cleaning
     ↓
Data Model
     ↓
DAX Measures
     ↓
Interactive Dashboard
     ↓
Business Insights
```

## 💡 Business Questions

1. Which products generate the highest revenue?
2. Which category has the highest sales?
3. Which region contributes the most revenue?
4. How does revenue change month by month?
5. Which payment method is most frequently used?
6. Which products have relatively low sales?

## 🎯 Expected Outcome

The project demonstrates practical skills in:

- Data cleaning
- Data transformation
- KPI development
- DAX
- Data visualization
- Dashboard design
- Business insight generation

## 👨‍💻 Author

**Vasanth Ruban SV**

B.Tech Information Technology

Interested in Data Analytics & Data Science
