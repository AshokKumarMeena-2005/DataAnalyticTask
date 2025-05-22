# DataAnalyticTask
#Car Price Prediction & Data Analysis Project

This project focuses on exploring and understanding the key features that influence car prices using a real-world dataset. The goal was to clean, transform, and visualize the data to gain meaningful insights and prepare it for predictive modeling.

## 📌 Project Objectives

- Clean and preprocess the dataset
- Perform exploratory data analysis (EDA)
- Engineer relevant features
- Visualize relationships between variables
- Generate insights for better pricing strategies

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** Data Cleaning, Feature Engineering, Correlation Analysis, EDA, One-Hot Encoding

---

## 📊 Key Highlights

### ✅ Data Cleaning
- Removed columns with high null percentage
- Dropped rows with excessive missing values
- Fixed spelling errors in car brand names
- Extracted car brand from `CarName`

### 🔍 Data Preparation
- Created new feature: `car_stability = wheelbase / carlength`
- Handled categorical variables using one-hot encoding
- Removed multicollinear features based on correlation heatmap

### 📈 Visualization
- Pairplots and heatmaps to understand variable relationships
- Histograms and bar charts for feature distributions
- Insights derived from visual trends and statistical correlations

---

## 📈 Key Insights

- **Engine size** and **horsepower** strongly correlate with price.
- **Brand** plays a major role in pricing — premium brands like BMW, Audi, and Porsche are significantly costlier.
- **Fuel efficiency** has a negative correlation with price.
- **Highly correlated features** (e.g., wheelbase, carlength) were dropped to avoid redund










