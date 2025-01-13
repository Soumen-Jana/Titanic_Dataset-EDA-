## Project Overview :

This repository contains an Exploratory Data Analysis (EDA) project on the Titanic dataset. The primary objective is to derive insights and understand the factors influencing passenger survival. The analysis involves data cleaning, visualization, and feature engineering.

## Data Source :
The dataset used for this analysis is the [Titanic dataset] provided by [Kaggle](https://www.kaggle.com/c/titanic). It contains information about passengers on the Titanic, including demographics, ticket details, and survival outcomes.

## Table of Contents :

  1. Dataset Description

  2. Analysis Steps

  3. Key Insights

  4. Visualizations

  5. Conclusion
   

## 1. Dataset Description :

The Titanic dataset includes information about passengers aboard the Titanic, such as demographic details, ticket information, and survival status. The key columns in the dataset are:

* PassengerId: Unique identifier for each passenger

* Survived: Survival status (0 = No, 1 = Yes)

* Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

* Name: Name of the passenger

* Sex: Gender of the passenger

* Age: Age of the passenger

* SibSp: Number of siblings/spouses aboard

* Parch: Number of parents/children aboard

 * Ticket: Ticket number

* Fare: Ticket fare

* Cabin: Cabin number

* Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 2. Analysis Steps :

### Data Loading and Exploration:-

* Inspect the dataset structure and contents.

* Check for missing values and data types.

### Data Cleaning:-


* Handle missing values (e.g., Age, Cabin, Embarked).

* Address outliers in numeric columns.

### Create New Columns :-
 * Create Family Size Column for better analyze.
  
  *  Fare column by grouping.




## 3. Key Insights :

* Gender and Survival: Females had a higher survival rate than males.

* Class and Survival: Passengers in 1st class had better survival rates compared to 2nd and 3rd class passengers.

* Age and Survival: Children were more likely to survive than adults.




## 4. Visualizations :

### Key visualizations include:-

* Survival rates by passenger class.

* Survival rates by gender.

* Age distribution and survival.

* Combined impact of class and gender on survival.




## 5. Conclusion :

* The analysis reveals key factors that influenced survival on the Titanic:

* Gender played a significant role, with females having higher survival chances.

* Social-economic status, represented by ticket class, significantly influenced survival.

* Children were prioritized during rescue operations.
