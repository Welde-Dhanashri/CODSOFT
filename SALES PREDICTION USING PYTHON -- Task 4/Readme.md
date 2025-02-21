
# Sales Prediction Using Python

## Overview
The purpose of this project is to analyze the impact of different advertisement platforms (**TV, Radio, Newspaper**) on sales and build a predictive model for estimating future sales based on advertising investments.

## Objectives
- 📌 Identify which advertising platform has the **strongest impact** on sales.
- 📌 Develop a predictive model for sales based on advertisement spending.

## Dataset Description
- The dataset consists of information on advertising expenditures and their influence on **sales figures**.
- Features in the dataset:
  - 📊 **TV**: Advertising cost spent on TV.
  - 📻 **Radio**: Advertising cost spent on Radio.
  - 📰 **Newspaper**: Advertising cost spent on Newspaper.
  - 💰 **Sales**: The dependent variable representing total sales.

## Exploratory Data Analysis (EDA)
- ✅ Checked for **missing values** and **data types**; no null or duplicate entries were found.
- ✅ Performed **univariate analysis** to understand feature distributions.
- ✅ Identified and treated **outliers** in the dataset.
- ✅ Created a **correlation heatmap** to examine relationships between features:
  - 📈 **TV has a strong positive correlation (~0.90) with Sales.**
  - 📊 **Radio has a moderate correlation (~0.41) with Sales.**
  - 📰 **Newspaper has a weak correlation (~0.15) with Sales.**
- ✅ The absence of **collinearity** among features indicates that each platform contributes independently to sales.

## Model Building
- 🔹 Split the data into **training and test sets**.
- 🔹 Trained a **Linear Regression Model** to predict sales.
- 🔹 Evaluated model performance using:
  - 📌 **R-squared (R²) score**
  - 📌 **Mean Squared Error (MSE)**

## Findings
- ✅ **TV advertising has the most significant impact** on sales.
- ✅ The **linear regression model achieves a reasonable level of accuracy**.
- ✅ **Newspaper advertising has minimal impact on sales.**

## Key Insights
- 📢 Investing in **TV advertisements** results in **higher sales growth**.
- 📻 **Radio contributes to sales**, but its impact is **moderate compared to TV**.
- 📰 **Newspaper ads show little to no significant effect** on sales performance.

