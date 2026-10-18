# 🛍️ Shopping Behavior Data Analysis

**Internship Project | Data Analytics & Machine Learning**

## 📌 Project Overview

This project was completed as part of my internship at **Eagle-Hitech Softclou Private Limited, Chennai**. The project focuses on analyzing customer shopping behavior to understand purchasing patterns, customer preferences, spending trends, and relationships between different shopping attributes.

Using Python, exploratory data analysis (EDA), statistical hypothesis testing, data visualization, and machine learning, the project explores how customer shopping data can be transformed into meaningful business insights.

## 🎯 Project Objectives

- Understand customer demographics and purchasing behavior.
- Analyze purchase amounts and seasonal spending patterns.
- Explore product category and payment method preferences.
- Examine customer review ratings and previous purchase behavior.
- Apply statistical tests to investigate relationships and differences in the data.
- Build machine learning models for category prediction and purchase amount estimation.
- Segment customers using clustering techniques.
- Generate insights that can support data-driven business decisions.

## 🛠️ Technologies and Tools

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

## 📂 Project Files

| File | Description |
|---|---|
| `shopping_behavior_analysis.ipynb` | Jupyter Notebook containing data exploration, visualizations, statistical tests, and machine learning experiments. |
| `shopping_behavior_updated.xls` | Shopping behavior dataset used for analysis. |
| `README.md` | Project overview, technologies, methodology, and instructions. |

## 📊 Dataset Description

The dataset contains customer shopping information, including demographic details, purchasing preferences, spending amounts, and shopping habits.

Key attributes analyzed include:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Season
- Review Rating
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases
- Subscription Status

## 🔍 Project Workflow

### 1. Data Loading and Exploration

- Loaded the shopping behavior dataset using Pandas.
- Inspected the first and last records.
- Examined dataset dimensions, column names, and data types.
- Generated descriptive statistics for numerical and categorical variables.
- Identified unique values and checked for missing data.

### 2. Data Preprocessing

- Created a copy of the dataset for preprocessing.
- Applied Label Encoding to categorical columns for machine learning experiments.
- Prepared features and target variables for model training.

### 3. Exploratory Data Analysis (EDA)

The following visualizations were created to explore customer shopping patterns:

- **Age Distribution:** Examined the distribution of customer ages.
- **Purchase Amount Distribution:** Explored customer spending patterns.
- **Gender Distribution:** Compared the number of male and female customers.
- **Seasonal Spending:** Compared average purchase amounts across seasons.
- **Product Category Distribution:** Examined the distribution of purchases across product categories.
- **Review Ratings by Gender:** Compared review rating distributions.
- **Payment Method Analysis:** Explored customer payment preferences.
- **Correlation Heatmap:** Examined correlations among age, purchase amount, review rating, and previous purchases.

### 4. Statistical Analysis

The project includes statistical tests to investigate customer shopping behavior.

- **Independent Samples T-Test:** Compared purchase amounts between male and female customers.
- **Pearson Correlation:** Examined the relationship between customer age and purchase amount.
- **Chi-Square Test of Independence:** Investigated the association between shopping season and product category.

These tests help evaluate whether observed differences or associations are statistically significant.

### 5. Machine Learning

#### A. Product Category Classification

A Random Forest Classifier was trained to predict product categories using selected customer and shopping attributes.

**Steps performed:**
- Prepared input features and target labels.
- Split the data into training and testing sets.
- Trained a Random Forest model with 100 estimators.
- Evaluated the model using classification accuracy.

#### B. Purchase Amount Prediction

A Linear Regression model was developed to estimate purchase amounts based on selected customer and shopping features.

**Evaluation metrics:**
- R² Score
- Mean Absolute Error (MAE)

These metrics help assess how well the model estimates purchase amounts on the test data.

#### C. Customer Segmentation

K-Means clustering was applied to explore groups of customers with similar data characteristics.

**Steps performed:**
- Used the Elbow Method to examine potential cluster counts.
- Created four customer clusters.
- Applied Principal Component Analysis (PCA) to reduce the feature space to two dimensions.
- Visualized customer clusters in a two-dimensional scatter plot.

### 6. Business Insights

The notebook generates summary information about:

- The most frequently represented product category.
- The season with the highest average purchase amount.
- The most frequently used payment method.
- Average customer purchase amount.
- Number of customers with active subscriptions.
- Number of customers using discounts.

These summaries provide a starting point for understanding purchasing patterns and identifying potential business opportunities.

## 📈 Results and Evaluation

The project explores multiple analytical approaches:

- Descriptive statistics and visualizations for customer behavior.
- Statistical hypothesis tests for comparing groups and investigating associations.
- Random Forest classification for product category prediction.
- Linear Regression for purchase amount estimation.
- K-Means clustering and PCA for customer segmentation.

Actual model scores and statistical conclusions should be taken from the executed notebook outputs. Model performance should be interpreted using the evaluation metrics rather than assumed to be accurate or business-ready.

## 💡 Key Learning Outcomes

Through this internship project, I gained practical experience in:

- Data exploration and preprocessing using Pandas.
- Creating meaningful visualizations using Matplotlib and Seaborn.
- Applying statistical tests using SciPy.
- Preparing datasets for machine learning.
- Training and evaluating classification and regression models.
- Exploring customer segmentation using K-Means and PCA.
- Translating data analysis into potential business insights.

## ⚙️ How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook on your system.

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

Replace the example repository URL and folder name with your actual GitHub details.

### Step 2: Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter openpyxl xlrd
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open and run the notebook

Open `shopping_behavior_analysis.ipynb` and execute the cells in order.

**Note:** Update the dataset-loading cell to use the correct local file path. The uploaded dataset is named `.xls`, while the original notebook uses `pd.read_csv()` with a `.csv` path. For an Excel `.xls` file, use `pd.read_excel("shopping_behavior_updated.xls")` after ensuring the file is in the notebook's working directory.

## 🔮 Future Enhancements

- Develop an interactive dashboard using Power BI or Streamlit.
- Improve predictive performance through feature engineering and model comparison.
- Add suitable classification and regression evaluation metrics.
- Create interpretable customer segments and targeted marketing recommendations.
- Validate analytical findings using additional or real-world datasets.

## 👩‍💻 Author

**Sandhiya S**  
MCA – Data Science Graduate  
Takshashila University

## 🏢 Internship Details

**Organization:** Eagle-Hitech Softclou Private Limited, Chennai  
**Project:** Shopping Behavior Data Analysis  
**Internship Period:** February 2026 – April 2026

---

*This project demonstrates practical application of data analytics, statistical analysis, data visualization, and machine learning to customer shopping behavior data.*
