# RealEstateX

Welcome to the Real Estate Predictor project, a comprehensive capstone demonstrating the application of data science techniques to the real estate domain.

## Project Overview

The project unfolds through various stages, covering data gathering, cleaning, exploratory analysis, modeling, recommendation systems, and the deployment of a user-friendly application.

### Data Gathering

The project commenced with collecting real estate data, self-scraped from the 99acres website and other property listing sources, ensuring a diverse dataset.

### Data Cleaning and Merging

A meticulous data cleaning process handled missing values and ensured dataset consistency, followed by merging house and flat information into a unified dataset.

### Feature Engineering

The dataset underwent feature engineering to enrich its informativeness, introducing new features like room indicators, area specifications, possession age, furnish details, and a luxury score.

### Exploratory Data Analysis (EDA)

Univariate and multivariate analyses were conducted to uncover data patterns and relationships. Pandas Profiling was utilized for a deeper understanding of data distribution.

### Outlier Detection, Missing Value Imputation

Outliers were identified and removed to ensure robust analyses. Missing values, especially in critical columns, were addressed using appropriate imputation techniques.

### Feature Selection

Multiple techniques such as correlation analysis, feature importance from various models, and regularization methods were employed to select impactful variables for modeling.

### Model Selection & Productionalization

An exhaustive comparison of regression models (Linear Regression, SVR, Random Forest, MLP, etc.) determined the best model based on evaluation metrics. The chosen model was integrated into a prediction pipeline and deployed using Streamlit for an intuitive web interface.

### Building the Analytics Module

An analytics module was developed to visually represent key insights about real estate data using maps, word clouds, scatter plots, and other visualizations.

### Building the Recommender System

Three recommendation models focusing on facilities, price details, and location advantages were developed, with a user-friendly interface created using Streamlit for enhanced accessibility.

### Deploying the Application on AWS

The entire application, encompassing prediction, analytics, and recommendation functionalities, was deployed on Amazon Web Services (AWS) for scalability and accessibility.
