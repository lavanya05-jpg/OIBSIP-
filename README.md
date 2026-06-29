# 🛒 Retail Sales EDA — Level 1 Task 1

## 📌 Objective
Perform a thorough Exploratory Data Analysis on a retail sales dataset to uncover patterns, customer behaviour trends, and actionable business insights.

## 🛠️ Tech Stack
- Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## 📊 Dataset
- 1000 transactions, 9 columns
- Columns: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount

## 📈 Charts & Insights

### 1. Monthly Sales Trend
- May 2023 had the highest sales
- September 2023 was the lowest performing month

### 2. Quarterly Sales
- Q2 performed best overall

### 3. Customer Age Distribution
- Customers range across all age groups

### 4. Gender Distribution
- 51% Female, 49% Male — nearly equal split

### 5. Revenue by Product Category
- Electronics and Clothing dominate revenue

### 6. Correlation Heatmap
- Price per Unit has 0.85 correlation with Total Amount
- Quantity has 0.37 correlation with Total Amount

### 7. Average Spending by Age Group (Bonus)
- Younger customers (<25) spend the most on average

## ✅ Business Recommendations
1. **Focus on high-price products** — Price per Unit strongly drives revenue. Promote premium Electronics and Beauty products.
2. **Target May & October** — Peak sales months. Plan campaigns and stock up inventory before these months.
3. **Equal gender marketing** — Nearly 50-50 customer base. Create inclusive promotions for all categories.

## 🔗 Internship
Oasis Infobyte Data Analytics Internship — Level 1 Task 1
# 🛍️ Customer Segmentation — Level 1 Task 2

## 📌 Objective
Segment customers into distinct groups using KMeans clustering based on purchasing behaviour.

## 🛠️ Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## 📊 Dataset
1000 customers with Age, Gender, Annual Income, Spending Score.

## 📈 Steps
- Data cleaning & null handling
- Feature scaling with StandardScaler
- Elbow Method → Optimal K = 4
- KMeans clustering
- Scatter plots & cluster profiling

## 👥 Cluster Summary
| Cluster | Type | Strategy |
|---------|------|----------|
| 0 | Budget-conscious | Discounts & loyalty programs |
| 1 | Impulsive buyers | Flash sales & trendy products |
| 2 | Potential high-value | Premium campaigns |
| 3 | VIP customers | Exclusive memberships |

## 🔗 Internship
Oasis Infobyte Data Analytics Internship — Level 1 Task 2
