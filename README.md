# Ecommerce Store Sales Report

A comprehensive Power BI dashboard providing insights into an e-commerce store's sales performance, analyzing data across multiple dimensions including products, customers, payment methods, and geographic locations.

![Dashboard Preview](Sales%20Report.png)

## 📊 Overview

This Power BI dashboard delivers real-time insights into e-commerce sales data, helping stakeholders make data-driven decisions. The dashboard features interactive visualizations that analyze sales patterns, customer behavior, and business performance across various dimensions.

## 🎯 Key Performance Indicators (KPIs)

- **Total Sales**: ₹62,000
- **Total Profit**: ₹9,684
- **Total Quantity**: 745 units

## 📈 Features

### Interactive Visualizations

1. **Sales by Category (Pie Chart)**
   - Electronics: ₹27K (43.35%)
   - Furniture: ₹21K (34.49%)
   - Clothing: ₹14K (22.16%)

2. **Sales by Sub-Category (Bar Chart)**
   - Top performers: Bookcases, Printers, Electronic Games, Accessories

3. **Top 5 Customers (Bar Chart)**
   - Top customers by sales: Shiva, Madan Mohan, Shreyshi, Shruti, Krutika

4. **Payment Mode Analysis (Donut Chart)**
   - COD: 37.8%
   - UPI: 18.43%
   - EMI: 17.93%
   - Credit Card: 15.31%
   - Debit Card: 10.53%

5. **Sales by State (Donut Chart)**
   - Maharashtra: 32.62%
   - Madhya Pradesh: 26.37%
   - Gujarat: 20.33%
   - Uttar Pradesh: 12.7%
   - Rajasthan: 7.98%

6. **Top 5 Cities (Bar Chart)**
   - Indore, Pune, Ahmedabad, Mathura, Mumbai

### Interactive Filters

- **Month Filter**: Filter data by month (e.g., January selected)
- **Quarter Filter**: Filter data by quarter (All quarters available)

## 📁 Datasets

The dashboard uses two CSV files:

### 1. Orders.csv
Contains customer and order information:
- Order ID
- Order Date
- Customer Name
- State
- City

### 2. Details.csv
Contains product and transaction details:
- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode

## 🛠️ Technology Used

- **Power BI Desktop**: Data visualization and dashboard creation
- **Power Query**: Data transformation and cleaning
- **DAX**: Calculated measures and columns

## 📊 Dashboard Functionality

### Data Insights
- **Sales Performance**: Track total sales and revenue
- **Profitability**: Monitor profit margins and trends
- **Customer Analysis**: Identify top customers and buying patterns
- **Product Performance**: Analyze sales by category and sub-category
- **Payment Trends**: Understand customer payment preferences
- **Geographic Analysis**: Sales distribution across states and cities

### Interactive Features
- Month and Quarter slicers for time-based filtering
- Click-through interactions between visualizations
- Drill-down capabilities for detailed analysis

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- Access to the dataset files (Details.csv and Orders.csv)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/E-Commerce-Store-Sales-Report.git
```

2. Open `Sales Dashboard.pbix` in Power BI Desktop

3. The dashboard will load with pre-configured visualizations and data connections

### Using the Dashboard

1. **View Overall Metrics**: Check the KPI cards at the top for overall performance
2. **Filter by Time**: Use the Month and Quarter slicers to filter data
3. **Analyze Categories**: Click on pie chart segments to filter other visuals
4. **Explore Locations**: Click on state/city visuals to see regional performance
5. **Payment Insights**: Analyze customer payment method preferences

## 📊 Dashboard Layout

The dashboard is organized as follows:
- **Top Row**: KPI cards showing key metrics
- **Top Slicers**: Month and Quarter filters
- **Left Column**: Category and Sub-category analysis (pie and bar charts)
- **Middle Column**: Customer and payment mode analysis
- **Right Column**: Geographic analysis (states and cities)

## 💡 Business Insights

- Electronics category generates the highest sales (43.35%)
- Maharashtra leads in sales (32.62% of total)
- COD (Cash on Delivery) is the preferred payment method (37.8%)
- Bookcases and Printers are top-performing sub-categories
- Top cities (Indore, Pune, Ahmedabad) drive significant revenue

## 📝 Notes

- Dashboard uses sample e-commerce data for demonstration
- Filters update all visuals dynamically
- Data can be refreshed by updating the source CSV files




