# E-Commerce Sales Analytics

## Project Overview

This project analyzes transactional e-commerce sales data using Python, Pandas, Matplotlib, Seaborn, and Microsoft Power BI.

The objective is to clean and prepare the raw transaction data, perform exploratory data analysis (EDA), identify important sales and customer patterns, and create an interactive dashboard for business decision-making.

---

## Dataset

**Dataset:** UCI Online Retail Dataset

**Source:** UCI Machine Learning Repository

The dataset contains transactional information from a UK-based online retail business.

### Original Columns

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

### Dataset Period

December 2010 – December 2011

---

## Technologies Used

- Python 3.12
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- JupyterLab
- Microsoft Power BI
- Git
- GitHub

---

## Project Structure

```text
ecommerce-sales-analytics/
│
├── data/
│   ├── Online Retail.xlsx
│   └── online_retail_clean.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│
├── visualizations/
│   ├── monthly_revenue_trend.png
│   ├── top_countries_revenue.png
│   ├── top_products_revenue.png
│   ├── top_customers_revenue.png
│   ├── revenue_distribution.png
│   ├── correlation_heatmap.png
│   ├── yearly_revenue.png
│   └── weekday_revenue.png
│
├── powerbi/
│   └── ecommerce_sales_dashboard.pbix
│
├── report/
│   └── insights_and_recommendations.md
│
├── presentation/
│
├── requirements.txt
├── .gitignore
└── README.md
Data Preparation
The raw dataset was cleaned before analysis.
Cleaning steps
1. Removed duplicate records.
2. Removed rows with missing product descriptions.
3. Identified transactions with missing CustomerID.
4. Removed cancelled invoices.
5. Removed transactions with negative quantities.
6. Removed transactions with non-positive unit prices.
7. Created a Revenue column.
Revenue Calculation
Revenue = Quantity × UnitPrice
Feature Engineering
The following date-related features were created:
- Year
- Month
- MonthName
- Day
- Weekday
Final Dataset
After cleaning:
- Rows: 524,878
- Columns: 14
- Total Revenue: approximately 10.64M
- Total Quantity Sold: approximately 5.57M
- Distinct Orders: approximately 19,960
- Identifiable Customers: approximately 4,338
- Countries: 38
- Products: 3,922
Exploratory Data Analysis
The following analyses were performed:
Sales Analysis
- Overall revenue
- Monthly revenue trends
- Yearly revenue
- Quantity sold
- Weekday sales patterns
Country Analysis
Revenue was analyzed across countries to identify the strongest markets.
Product Analysis
Products were ranked according to total revenue to identify high-performing products.
Customer Analysis
Customers with valid CustomerID values were analyzed according to their revenue contribution.
Correlation Analysis
The relationship between:
- Quantity
- UnitPrice
- Revenue
was examined using a correlation matrix.
Quantity and Revenue showed a strong positive correlation of approximately 0.91.
Power BI Dashboard
An interactive Power BI dashboard was created containing:
KPI Cards
- Total Revenue
- Total Orders
- Total Quantity Sold
- Total Customers
Visualizations
- Monthly Revenue Trend
- Top 10 Countries by Revenue
- Top 10 Products by Revenue
- Top 10 Customers by Revenue
Interactive Filters
- Year
- Month
- Country
The dashboard allows users to interactively filter the sales data and explore business performance.
Key Insights
1. The United Kingdom is the dominant revenue-generating market.
2. Several European markets such as the Netherlands, EIRE, Germany, and France contribute significant additional revenue.
3. Revenue is concentrated among a relatively small number of high-performing products.
4. A group of high-value customers contributes significantly to overall revenue.
5. Quantity and Revenue have a strong positive correlation of approximately 0.91.
6. Missing CustomerID values limit customer-level analysis for some transactions.
Business Recommendations
1. Maintain strong inventory availability in the UK market.
2. Explore expansion opportunities in promising international markets.
3. Prioritize high-revenue products for inventory planning.
4. Develop loyalty programs and personalized promotions for high-value customers.
5. Use monthly sales trends for demand forecasting and inventory planning.
6. Improve customer information collection to strengthen customer segmentation.
7. Monitor cancellations and returns separately to identify operational issues.
How to Run the Project
1. Clone the repository
git clone https://github.com/fazilkhan-dev/ecommerce-sales-analytics.git
2. Navigate to the project
cd ecommerce-sales-analytics
3. Create a virtual environment
py -3.12 -m venv .venv
4. Activate the environment
Windows PowerShell:
.\.venv\Scripts\Activate.ps1
5. Install dependencies
pip install -r requirements.txt
6. Open the notebook
jupyter lab
Open:
notebooks/EDA.ipynb
Project Deliverables
- Cleaned dataset
- EDA notebook
- Data visualizations
- Power BI dashboard
- Business insights and recommendations
- Project documentations
- Presentation
Author
FAZIL KHAN
GitHub: fazilkhan-dev