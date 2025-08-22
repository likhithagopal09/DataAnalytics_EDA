📊 Global Superstore Sales Analysis
This project explores the Global Superstore dataset using Python to analyze sales, profits, and discounts across regions and categories. It includes data cleaning, visualization, correlation analysis, and a simple machine learning model (Linear Regression) to predict sales. Insights and recommendations are auto-generated to highlight business trends and decision-making points.


## ⚙️ Steps in the Project
1. **Data Loading & Cleaning**
   - Load the `Global_Superstore2.csv` dataset
   - Handle encoding issues (`latin1` fix)
   - Convert date columns to proper datetime format

2. **Exploratory Data Analysis (EDA)**
   - Sales by Region
   - Sales by Category
   - Sales over Time

3. **Feature Engineering**
   - Extract `Year` and `Month` from `Order Date`

4. **Correlation Analysis**
   - Relationship between `Discount`, `Profit`, and `Sales`

5. **Machine Learning**
   - Built a **Linear Regression Model**
   - Features: `Profit`, `Discount`
   - Target: `Sales`
   - Evaluated using **MSE** and **R² Score**

6. **Insights & Recommendations**
   - Auto-generated insights into top regions & categories
   - Impact of discounts on sales
   - Average sales per discount bucket
   - Model performance summary


## 📊 Sample Insights
- **Top Region by Sales:** `West`
- **Top Category by Sales:** `Technology`
- **Discount vs Sales Correlation:** Slightly negative
- **Model R² Score:** ~0.6 (moderate prediction power)


BY AUTHOR - Likhitha Gopal
