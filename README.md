# 🚢 Titanic Dataset Analysis --- Pandas Project

This project is a complete exploratory data analysis (EDA) of the
Titanic dataset using **Python**, **Pandas**, **Matplotlib**, and
**Seaborn**.\
The goal is to clean the data, explore important features, visualize
patterns, and extract insights about passenger survival.

## 📘 Dataset Description

The dataset contains information about passengers aboard the Titanic,
including: - **Survival** (0 = No, 1 = Yes)\
- **Age**, **Sex**, **Class**, **Fare**\
- Number of siblings/spouses (`SibSp`)\
- Number of parents/children (`Parch`)\
- **Embarked** port\
- **Cabin** (mostly missing)

Total rows: **891**\
Total columns: **12**

## 🎯 Project Objectives

-   Clean the dataset (handle missing values in Age, Cabin, Embarked)\
-   Explore patterns that influenced passenger survival\
-   Visualize key relationships using Seaborn and Matplotlib\
-   Practice Pandas skills: indexing, filtering, groupby, aggregation\
-   Build a portfolio-quality Jupyter Notebook and GitHub project

## 🧹 Data Cleaning Steps

### 1. Cabin

-   Too many missing values → dropped completely.

### 2. Embarked

-   Only 2 missing values → filled using the most frequent port.

### 3. Age

-   \~177 missing ages → filled using median age grouped by Sex and
    Pclass.

### 4. Final check

-   All missing values removed or imputed successfully.

## 🔍 Exploratory Data Analysis (EDA)

### 1. Overall survival rate

-   Survival rate ≈ 39%

### 2. Survival by gender

-   Women had a much higher survival rate than men.

### 3. Survival by class

-   1st class passengers survived the most.\
-   3rd class passengers survived the least.

### 4. Survival by age

-   Children (0--12) had a higher survival rate.

### 5. Fare patterns

-   Higher fares increased the probability of survival.

## 📊 Visualizations Included

-   Correlation heatmap\
-   Barplots for survival vs gender, class, age groups\
-   Scatterplots (Age vs Fare)\
-   Countplots for categorical distributions

## 📝 Notebook

The full analysis is in:\
`notebooks/01_exploration.ipynb`

## ▶️ How to Run the Notebook

### Install dependencies:

    pip install -r requirements.txt

### Launch Jupyter:

    jupyter notebook

## 📚 What I Learned

-   Cleaning real-world data with Pandas\
-   Handling missing values\
-   Using groupby for aggregations\
-   Visualizing with Seaborn\
-   Working with Git & GitHub\
-   Clear documentation and analysis

## 🚀 Future Improvements

-   Feature engineering\
-   Logistic regression survival prediction\
-   Dashboards with Plotly/Streamlit
