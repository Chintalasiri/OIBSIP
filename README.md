# OIBSIP
## Level 1 - Task 1: Exploratory Data Analysis (EDA) on Retail Sales Data

### 📌 Objective
The objective of this project is to perform Exploratory Data Analysis (EDA) on a retail sales dataset to identify sales trends, customer behavior, product performance, and generate actionable business insights.

---

## 📂 Dataset
- Dataset: Retail Sales Dataset (Sample Superstore)
- Source: Kaggle

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Project Workflow

- Loaded and inspected the dataset
- Checked missing values and data types
- Performed descriptive statistics
- Analyzed monthly and quarterly sales trends
- Identified the top 10 best-selling products
- Analyzed revenue by product category
- Created a correlation heatmap
- Performed additional visualization (Discount vs Profit)
- Generated business insights and recommendations

---

## 📈 Visualizations

- Monthly Sales Trend
- Quarterly Sales Trend
- Top 10 Best-Selling Products
- Revenue by Product Category
- Correlation Heatmap
- Discount vs Profit Analysis

---

## 💡 Business Insights

- Sales vary across different months and quarters.
- A few products contribute significantly to total sales.
- Higher discounts may reduce overall profitability.
- Product categories contribute differently to business revenue.

---

## ✅ Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can help businesses understand sales patterns, product performance, and profitability. The insights obtained can support better business decisions related to pricing, inventory management, and sales strategies.

## Level 1 - Task 2: Customer Segmentation Analysis

### 📌 Objective

The objective of this project is to perform customer segmentation using the K-Means clustering algorithm. Customers are grouped based on their purchasing behaviour using the RFM (Recency, Frequency, Monetary) model, helping businesses create targeted marketing strategies.

---

## 📂 Dataset

- Dataset: Online Retail Dataset
- Source: UCI Machine Learning Repository / Kaggle

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Project Workflow

- Loaded and inspected the dataset
- Handled missing values and removed duplicate records
- Calculated descriptive statistics
- Created RFM (Recency, Frequency, Monetary) features
- Standardized data using StandardScaler
- Applied the Elbow Method to determine the optimal number of clusters
- Performed customer segmentation using K-Means clustering
- Visualized customer clusters with scatter plots
- Created customer profiles based on cluster characteristics
- Analyzed the number of customers in each cluster
- Suggested marketing strategies for each customer segment

---

## 📈 Visualizations

- Elbow Method Graph
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Customers per Cluster Bar Chart

---

## 💡 Customer Segments

- **Cluster 0:** Loyal Customers
- **Cluster 1:** Inactive Customers
- **Cluster 2:** Premium Customers
- **Cluster 3:** Regular Customers

---

## 📌 Marketing Recommendations

- Reward loyal customers with exclusive offers and loyalty programs.
- Re-engage inactive customers through personalized campaigns and discounts.
- Retain premium customers using VIP memberships and premium services.
- Encourage regular customers to increase purchases through promotional offers and product recommendations.

---

## ✅ Conclusion

This project demonstrates how customer segmentation using the RFM model and K-Means clustering helps businesses understand customer behaviour. The identified customer groups enable organizations to implement personalized marketing strategies, improve customer retention, and increase overall business revenue.

# Oasis Infobyte Data Analytics Internship

## Level 1 - Task 3: Data Cleaning

### 📌 Objective

The objective of this project is to demonstrate professional-level data cleaning skills by transforming a raw dataset into a clean, analysis-ready dataset using Python and Pandas.

---

## 📂 Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

---

## 📋 Project Workflow

- Loaded the dataset
- Generated a Data Quality Report
- Checked missing values
- Checked duplicate records
- Standardized categorical values
- Detected outliers using the IQR Method
- Verified data types
- Compared dataset before and after cleaning
- Exported the cleaned dataset as a new CSV file

---

## 🔍 Data Quality Checks

- Dataset Shape
- Data Types
- Missing Values
- Duplicate Rows
- Value Inspection

---

## 🧹 Data Cleaning Techniques

### Missing Values
No missing values were found in the dataset.

### Duplicate Records
No duplicate rows were identified.

### Standardisation
The categorical values were already standardized; therefore, no formatting changes were required.

### Outlier Detection
The IQR (Interquartile Range) method was applied to detect outliers in the Age column.

The identified outliers represented genuine elderly passengers rather than data entry errors. Hence, they were retained to preserve the integrity of the dataset.

### Data Type Verification
All columns already had appropriate data types, so no corrections were necessary.

---

## 📊 Before vs After Summary

| Metric | Before | After |
|---------|--------|-------|
| Rows | 887 | 887 |
| Missing Values | 0 | 0 |
| Duplicate Rows | 0 | 0 |
| Data Type Issues | None | None |

---

## 📁 Output

**Cleaned Dataset**

`Titanic_Cleaned_Dataset.csv`

---

## ✅ Conclusion

The Titanic dataset was successfully inspected and cleaned using Python and Pandas. The dataset contained no missing values or duplicate records, data types were correct, and the detected outliers represented valid observations. The cleaned dataset is now ready for further analysis and machine learning applications.

