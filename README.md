# Electronics  Data Analysis

## Introduction
Imtiaz Mall, a renowned department store chain, is experiencing declining sales and a significant number of non-recurring customers in its electronics section. To address this challenge, as the newly appointed Senior Data Scientist, you are tasked with conducting a comprehensive analysis of the electronics section data and developing data-driven strategies for customer retention and sales growth. This project focuses on the initial steps of this analysis, specifically exploring the data through various techniques.

---

## Module 1: Data Acquisition and Preprocessing

### 1. Data Acquisition
- Download the provided historical sales data for the electronics section.
- Ensure the data includes:
  - Customer demographics
  - Purchase history
  - Product details
  - Spending amounts
  - Dates of transactions

### 2. Data Cleaning
- Identify and handle missing values using appropriate techniques:
  - Mean/median imputation
  - Dropping rows/columns with excessive missingness
- Analyze outliers and determine their impact:
  - Decide whether to retain or remove them
- Address inconsistencies in data format and encoding.

### 3. Data Transformation
- Create new features for deeper insights:
  - **Average spending per purchase**
  - **Purchase frequency per month**
  - **Brand affinity score** (based on product brand preferences)
  - **Product category preferences** (e.g., TVs, smartphones, laptops)
- Standardize or normalize numeric features to ensure equal contribution to algorithms.

---

## Module 2: Exploratory Data Analysis (EDA)

### 1. Univariate Analysis
- Analyze the distribution of key features using:
  - Histograms
  - Boxplots
  - Descriptive statistics
- Identify potential skewness or outliers in the data.

### 2. Bivariate Analysis
- Explore relationships between features using:
  - Scatterplots
  - Heatmaps
- Investigate correlations, such as:
  - Purchase amount vs. income level
  - Brand affinity vs. product category
  - Purchase frequency vs. age

### 3. Temporal Analysis
- Analyze trends in customer behavior over time:
  - Changes in purchase frequency
  - Average spending
  - Product preferences
- Identify seasonal variations or significant shifts in behavior patterns.

---

## Module 3: Regression and Decision Tree Analysis

### A. Linear Regression Analysis

#### 1. Problem Definition
- Predict the **average spending per purchase** based on customer demographics and purchase history.

#### 2. Model Building
- Preprocess the data by selecting relevant numerical and categorical variables:
  - Income level
  - Product category
  - Age
- Split the dataset into training and testing sets.

#### 3. Implementation
- Train a linear regression model using the training data.
- Evaluate the model using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared

#### 4. Visualization
- Plot predicted vs. actual values for the test dataset.
- Include regression lines for better interpretability.

### B. Decision Tree Analysis

#### 1. Problem Definition
- Classify whether a customer will make a purchase in the next month (binary target variable).

#### 2. Model Building
- Engineer a binary target variable:
  - 1 = Purchase made
  - 0 = No purchase
- Use features like:
  - Purchase frequency
  - Spending history
  - Product preferences

#### 3. Implementation
- Train a decision tree classifier using criteria such as **Gini Impurity** or **Entropy**.
- Evaluate the model using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

#### 4. Visualization
- Plot the decision tree.
- Highlight important features influencing decisions.

---

## Module 4: Clustering Analysis

### 1. Define the Number of Clusters (k)
- Use the **elbow plot** to determine the optimal number of clusters based on the sum of squared distances within clusters.

### 2. Apply K-Means Clustering
- Implement K-Means clustering with the chosen **k** value to segment customers based on their purchase behavior and preferences.

### 3. Analyze Cluster Characteristics
- Investigate key features of each cluster:
  - Average purchase amount
  - Brand affinity
  - Product category preferences
- Identify significant differences and similarities between clusters.

---

## Module 5: Comparison and Conclusion

### 1. Model Performance Comparison
- Compare the predictive performance of:
  - Linear Regression
  - Decision Tree Classifier
  - K-Means Clustering
- Discuss strengths, limitations, and real-world applicability for customer behavior analysis.

### 2. Recommendations
- Provide actionable recommendations for the electronics section based on the results of the analysis, including strategies for:
  - Customer retention
  - Sales growth

---
