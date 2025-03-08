E-commerce Customer Analysis Project

📌 Project Overview

This project analyzes customer purchasing behavior based on e-commerce transaction data. The goal is to extract meaningful insights regarding customer demographics, purchasing trends, discount patterns, and sales performance.

📂 Dataset Information

The dataset consists of 55,000 customer transactions with the following features:

Column Name

Description

CID

Unique Customer ID

Gender

Customer Gender (e.g., Male, Female)

Age

Age of the Customer

Product Category

Category of the purchased product

Discount Availed

Whether a discount was applied (Yes/No)

Discount Amount (INR)

Amount of discount received

Gross Amount

Total purchase amount before discounts

Purchase Method

Mode of purchase (Online, In-Store)

Location

Geographical location of purchase

🛠️ Technologies Used

Python for data analysis

Pandas for data manipulation

Matplotlib & Seaborn for data visualization

Scikit-learn for clustering and predictive analysis

🔍 Key Steps in the Analysis

1️⃣ Data Preprocessing

Handling missing values and data inconsistencies.

Converting categorical variables into numeric formats where needed.

Standardizing age values (if non-numeric values exist).

2️⃣ Exploratory Data Analysis (EDA)

Demographic Analysis: Gender and Age distribution.

Sales Performance: Distribution of Gross Amount across categories.

Discount Trends: Relationship between Discount Amount and Gross Amount.

Purchase Behavior: Analysis of Purchase Method and Location.

3️⃣ Business Insights

Identifying high-value customer segments.

Understanding the impact of discounts on purchasing behavior.

Determining the most profitable product categories.

Evaluating the most popular purchase methods and locations.

4️⃣ Predictive Analysis (Optional)

Customer Clustering: Using K-Means to segment customers based on purchase behavior.

Discount Optimization: Predicting which customers are more likely to avail discounts.

📈 Example Visualizations

Age & Gender Distribution 📊

Sales Trends by Product Category 📉

Impact of Discounts on Spending 💰

Heatmap of Purchases by Location 🗺️

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install pandas matplotlib seaborn scikit-learn

2️⃣ Run the Analysis Script

python ecommerce_analysis.py

📌 Key Takeaways

Identifying the best-selling products and highest revenue-generating categories.

Understanding how customer demographics influence purchasing behavior.

Evaluating the effectiveness of discounts and promotions.

🔗 Future Improvements

Develop an interactive dashboard for real-time data visualization.

Implement customer recommendation models based on purchasing patterns.

Integrate machine learning for predictive insights on customer behavior.

