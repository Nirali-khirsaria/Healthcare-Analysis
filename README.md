# Healthcare-Analysis
📌 Project Overview
This project analyzes global life expectancy data across countries to perform exploratory data analysis, build dashboards, and apply machine learning techniques to predict life expectancy using global healthcare and economic data.
sourced from a U.S. government public health dataset.

🎯 Objectives

Analyze historical life expectancy trends across countries

Identify key factors affecting life expectancy

Build predictive models to forecast future life expectancy

Visualize insights using dashboards

Deploy a user-facing application for life expectancy prediction
📊 Exploratory Data Analysis (EDA)

We conducted extensive EDA to understand data quality, trends, and relationships:

Trend analysis of life expectancy over time

Comparison between developed vs developing countries

Correlation analysis to identify influential features

Detection of missing values and data inconsistencies

📌 EDA helped uncover strong relationships between life expectancy and factors such as education, GDP, adult mortality, and immunization coverage.

📈 Dashboards & Visualizations

Interactive dashboards were created to:

Compare life expectancy by country and region

Visualize trends over time

Analyze healthcare and economic indicators

These dashboards simplify complex data and allow quick interpretation for decision-making.

🤖 Machine Learning Modeling
Data Preparation

Converted categorical variables (Country, Status) into numerical form

Selected highly correlated features using a correlation matrix

Ensured data was suitable for regression modeling

Model Selection

Several regression models were tested. The Extra Trees Regressor delivered the best performance due to:

High prediction accuracy

Ability to handle nonlinear relationships

Robustness to outliers

Prediction Process

Prepared data is passed to the trained model

Model computes predicted life expectancy values

Results are displayed in a user-friendly format

🌐 Web Application Deployment

A Flask-based web application was developed to make predictions accessible:

Backend: Flask (model loading, prediction logic)

Frontend: HTML & CSS

User Interaction: Form-based input for health and economic indicators

Users can input feature values and instantly receive predicted life expectancy.

✅ Key Insights & Conclusion

Life expectancy is strongly influenced by healthcare access, education, income level, and disease prevention

Preventative measures such as vaccination programs and health education play a critical role

Predictive analytics enables proactive health planning and policy decisions

Continuous model updates with new data will improve prediction accuracy

This project demonstrates how data analytics and machine learning can support global health improvement initiatives.
