# Amazon Sales Data – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on an Amazon sales dataset to understand product demand, pricing trends, and order fulfillment patterns.

The goal of this analysis is to extract meaningful insights that can help improve sales strategy and inventory planning.

---

## Dataset Information
- <a href="https://github.com/Sateeshkumar4425/Amazon-Sales-EDA/blob/main/Amazon%20Sale%20Report-checkpoint.csv">Dataset</a>
- Source: Public online dataset
- Total Records: ~128,000
- Total Features: 21 columns (cleaned to 19)
- Data Types: Numerical, Categorical, Boolean

---

## Key Analysis Performed
- Data cleaning (handling missing values and duplicates)
- Data type correction and normalization
- Univariate analysis on categorical and numerical columns
- Bivariate analysis to understand relationships
- Data visualization using Matplotlib and Seaborn

---

## Key Insights
- T-shirts and Shirts are the top-selling product categories
- Medium (M) size products are ordered the most
- Most orders are successfully shipped
- A positive correlation exists between order quantity and total amount

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---
## 📊 Key Visual Insights

### Category-wise Product Distribution
![Category Distribution](https://github.com/Sateeshkumar4425/Amazon-Sales-EDA/blob/main/image/category_sales.png)


1.T-shirts and Shirts contribute the highest number of orders, showing they are the most in-demand products.
2.Non-clothing categories (Wallets, Watches, Shoes) have very low order share, indicating limited customer interest.
3.Sales are heavily concentrated in a few categories, suggesting inventory and marketing should focus more on top-performing products.

### Sales Amount Distribution by Category
![Amount vs Category](https://github.com/Sateeshkumar4425/Amazon-Sales-EDA/blob/main/image/category_sales%20A.png)


1.Most categories show higher order density in the mid-price range, indicating customers are price-sensitive.
2.Apparel products generate consistent sales across different price points, making them reliable revenue drivers.
3.High-priced orders are relatively fewer, suggesting premium products have limited demand.

### Correlation Between Quantity and Amount
![Correlation Heatmap](https://github.com/Sateeshkumar4425/Amazon-Sales-EDA/blob/main/image/correlation_heatmap.png)


1.There is a moderate positive correlation between quantity and amount, meaning higher quantities usually lead to higher order value.
2.The correlation is not very strong, indicating most customers purchase small quantities per order.
3.Increasing quantity-based offers or bundles could help improve overall revenue per order.

### Order Status Across Product Sizes
![Size vs Status](https://github.com/Sateeshkumar4425/Amazon-Sales-EDA/blob/main/image/Status_VS_Size.png)


1.Medium (M), Large (L), and XL sizes have the highest number of successfully shipped orders.
2.Smaller and extreme sizes (XS, 5XL, 6XL) show lower demand, suggesting slower inventory movement.
3.Cancellation rates are relatively low across popular sizes, indicating good size availability and customer satisfaction.



## How to Run the Project
```bash
1. pip install -r requirements.txt

2. Launch Jupyter Notebook:jupyter notebook
   
3. Open the notebook and run all cells in order.

'''👤 About Me

Name: Patlegar Sateesh Kumar Role: Aspiring Junior Data Scientist | Amazon_sales Analytics Enthusiast

💼 Open to data science, analytics, and quant roles

📧 Email: patlegarsateeshkumar@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/patlegar-sateesh-kumar-868870258/'''


