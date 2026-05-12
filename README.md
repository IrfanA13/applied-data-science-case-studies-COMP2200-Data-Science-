# Applied-data-science-case-studies-COMP2200-Data-Science-
Applied data science case studies covering data cleaning, EDA, regression, and classification across e-commerce, mobile pricing, and health datasets.

## Applied Data Science Case Studies
This repository contains a collection of applied data science case studies using Python. The work demonstrates an end-to-end analytical workflow across multiple domains, including e-commerce, mobile pricing, and healthcare.

## Repository Description

Applied data science case studies using Python for data cleaning, exploratory analysis, regression, and classification across e-commerce, mobile pricing, and health datasets.

## Repository Structure
```text
applied-data-science-case-studies/
│
├── README.md
│
├── portfolio-1-ecommerce-data-cleaning-eda/
│   ├── portfolio-1-ecommerce-cleaning-eda.ipynb
│   └── The E-commerce Dataset.csv
│
├── portfolio-2-ecommerce-rating-prediction/
│   ├── portfolio-2-ecommerce-rating-prediction.ipynb
│   └── cleaned_ecommerce_dataset.csv
│
├── portfolio-3-mobile-price-classification/
│   ├── portfolio-3-mobile-price-classification.ipynb
│   └── Mobile_Price_Data.csv
│
└── portfolio-4-heart-disease-prediction/
    ├── portfolio-4-heart-disease-prediction.ipynb
    └── heart.csv


### Portfolio Overview
### Portfolio 1: E-commerce Data Cleaning and Exploratory Data Analysis

This section focuses on understanding and preparing an e-commerce dataset for analysis. The work begins with raw customer and product-related data, then applies cleaning, filtering, descriptive statistics, and visual exploration.

The analysis explores how customer ratings vary across different groups and product-related variables. It also identifies how missing values, invalid review entries, and outliers can affect the reliability of insights.

Dataset used: The E-commerce Dataset.csv

Key tasks:

Removed missing and invalid records
Filtered non-informative review values
Calculated descriptive statistics
Explored customer rating patterns
Created visualisations to compare variables
Identified and removed outliers

Analytical value:

This part demonstrates the importance of preparing data before modelling or decision-making. It shows that poor-quality records, missing values, and outliers can distort patterns in customer behaviour and lead to misleading conclusions.

### Portfolio 2: E-commerce Rating Prediction

This section extends the e-commerce analysis by using machine learning to predict customer ratings. The work applies regression modelling to understand how different variables may influence customer review scores.

The notebook includes feature selection, categorical encoding, train-test splitting, model training, and model evaluation. It also reflects on ethical considerations in data science, especially when using customer-related data for prediction.

Dataset used: cleaned_ecommerce_dataset.csv

Key tasks:

Explored relationships between ratings and other features
Encoded categorical variables
Prepared training and testing datasets
Built linear regression models
Compared model performance under different feature selections
Discussed ethical considerations in data science

Analytical value:

This part shows how predictive modelling can be used to estimate customer satisfaction. It also highlights that model performance depends heavily on feature quality, data preparation, and responsible use of customer data.

### Portfolio 3: Mobile Price Classification

This section applies classification techniques to predict mobile phone price ranges based on technical specifications. The analysis explores which product features are most closely associated with price category.

The work compares Logistic Regression and K-Nearest Neighbours models, including tuning the KNN model using different K values. This provides a practical example of how classification models can support product positioning and pricing analysis.

Dataset used: Mobile_Price_Data.csv

Key tasks:

Explored mobile phone specification data
Analysed feature relationships with price range
Selected important predictors such as RAM, battery power, and pixel resolution
Built Logistic Regression and KNN classification models
Tuned KNN using different K values
Compared classification accuracy

Analytical value:

This part demonstrates how machine learning can classify products into market segments. It shows how technical specifications can help explain price differences and support decisions related to product strategy, pricing, and competitive positioning.

###
Portfolio 4: Heart Disease Prediction

This section applies classification models to a healthcare dataset to predict the likelihood of heart disease. The analysis includes data exploration, categorical encoding, feature relationship analysis, model training, and performance evaluation.

The notebook uses Logistic Regression and K-Nearest Neighbours to compare model performance. A confusion matrix is also used to evaluate classification results, which is especially important in healthcare-related prediction problems where false positives and false negatives have different consequences.

Dataset used: heart.csv

Key tasks:

Explored patient health data
Encoded categorical health variables
Analysed relationships between features and heart disease
Selected important predictive features
Built Logistic Regression and KNN models
Evaluated model performance using accuracy and confusion matrix

Analytical value:

This part shows how classification models can support risk prediction in healthcare. It also highlights the importance of model evaluation beyond accuracy, since prediction errors in health-related contexts can have serious practical implications.
