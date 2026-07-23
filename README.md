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


# Level 1 - Task 4: Sentiment Analysis using Machine Learning

## 📌 Objective
The objective of this project is to build a Machine Learning model that classifies text reviews into **Positive**, **Negative**, and **Neutral** sentiments using Natural Language Processing (NLP) techniques.

## 📂 Dataset
**Dataset:** Sentiment Analysis Dataset  
**Source:** Kaggle

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK
- TF-IDF Vectorizer
- Google Colab
- Jupyter Notebook

## 📋 Project Workflow
- Loaded the dataset
- Explored the dataset structure
- Checked missing values
- Checked duplicate records
- Performed text preprocessing
- Converted text to lowercase
- Removed punctuation and special characters
- Removed stopwords
- Converted text into numerical features using TF-IDF Vectorization
- Split the dataset into training and testing sets
- Trained a Machine Learning classification model
- Predicted sentiments for test data
- Evaluated model performance
- Visualized sentiment distribution

## 🔍 Data Preprocessing
### Missing Values
The dataset was checked for missing values before training the model.

### Duplicate Records
Duplicate records were inspected to ensure data quality.

### Text Preprocessing
The following preprocessing steps were performed:
- Converted text to lowercase
- Removed punctuation
- Removed stopwords
- Cleaned unnecessary characters
- Applied TF-IDF Vectorization for feature extraction

## 🤖 Model Building
The dataset was divided into training and testing sets. A Machine Learning classification model was trained using the processed text features to classify reviews into Positive, Negative, and Neutral sentiments.

## 📊 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics were used to measure the model's classification performance.

## 📈 Visualization
- Sentiment Class Distribution
- Model Performance Visualization

## 📁 Output
- Trained Sentiment Analysis Model
- Predicted Sentiment Labels
- Performance Evaluation Results

## ✅ Conclusion
The Sentiment Analysis model was successfully developed using Machine Learning and Natural Language Processing techniques. Text data was preprocessed, transformed into numerical features using TF-IDF Vectorization, and used to train a classification model. The model effectively classified reviews into Positive, Negative, and Neutral sentiments, demonstrating the practical application of NLP for text classification tasks.

# Level 2 - Task 1: House Price Prediction using Linear Regression

## 📌 Objective
The objective of this project is to build a Linear Regression model that predicts house prices based on various housing features. The project demonstrates the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and interpretation of results.

## 📂 Dataset
**Dataset:** Housing Dataset  
**Source:** Kaggle

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## 📋 Project Workflow
- Loaded the dataset
- Performed Exploratory Data Analysis (EDA)
- Examined dataset information
- Generated descriptive statistics
- Checked missing values
- Visualized the distribution of the target variable (Price)
- Selected input features and target variable
- Converted categorical features into numerical values
- Generated a correlation heatmap
- Split the dataset into training and testing sets (80:20)
- Trained a Linear Regression model
- Predicted house prices
- Evaluated model performance using MSE, RMSE, and R² Score
- Visualized Actual vs Predicted Prices
- Generated a Residual Plot
- Performed Coefficient Analysis

## 🔍 Exploratory Data Analysis
### Dataset Information
The dataset structure, data types, and feature details were examined using Pandas.

### Descriptive Statistics
Statistical measures such as mean, median, standard deviation, minimum, and maximum values were analyzed for numerical features.

### Missing Values
The dataset was inspected for missing values.

**Result:** No missing values were found in the dataset.

### Target Variable Distribution
The distribution of house prices was visualized to better understand the target variable.

## 🧹 Data Preprocessing
### Missing Values
No missing values were present; therefore, no imputation was required.

### Categorical Feature Encoding
Binary categorical features were converted into numerical values, and categorical variables were encoded to prepare the dataset for Linear Regression.

### Correlation Analysis
A correlation heatmap was generated to identify the relationship between house prices and the input features.

## 🤖 Model Building
The dataset was divided into training and testing sets using an 80:20 ratio.

A Linear Regression model was trained using the training dataset to learn the relationship between the input features and house prices.

## 📊 Model Evaluation
The model performance was evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These evaluation metrics measured the prediction accuracy and overall performance of the model.

## 📈 Visualizations
- Distribution of House Prices
- Correlation Heatmap
- Actual vs Predicted House Prices Scatter Plot
- Residual Plot
- Feature Coefficient Analysis

## 📁 Output
- Trained Linear Regression Model
- Predicted House Prices
- Model Evaluation Metrics
- Data Visualizations

## ✅ Conclusion
A Linear Regression model was successfully developed to predict house prices using multiple housing features. The project included data exploration, preprocessing, visualization, model training, evaluation, and coefficient analysis. The results demonstrate the effectiveness of Linear Regression for predicting house prices and provide valuable insights into the factors influencing property values.
