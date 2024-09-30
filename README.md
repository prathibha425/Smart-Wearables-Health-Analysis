# Smart-Wearables-Health-Analysis
A data science project leveraging wearable technology data to provide personalized health guidance using machine learning models. This project explores the use of health metrics collected from wearable devices, such as Apple Watches, to predict fitness levels and analyze the impact of gender and activity on exercise intensity.
# Project Overview
This project focuses on utilizing data from wearable technology to predict Intensity Karvonen, a key metric for prescribing personalized exercise intensities. By using data science techniques, we aim to create predictive models that provide personalized health recommendations, transforming traditional fitness assessments into continuous and dynamic health insights.
# Dataset
The dataset was sourced from Kaggle and consists of physiological and activity metrics such as:

Age and Gender
Heart Rate (resting and active)
Steps and Distance
Calories Burned
Activity Type (walking, lying, etc.)
Intensity Karvonen (derived exercise intensity)

The dataset can be found in the **data** folder:
aw_fb_data-1.csv
# Methodology

**Data Preprocessing:**
Data was cleaned by removing irrelevant columns, encoding categorical variables, and handling missing values.
Outliers were detected and removed to improve the reliability of the models.

**Feature Engineering:**
New features such as Body Mass Index (BMI) were created to enhance the predictive power of the models.
Standardization was applied to features like age, BMI, and heart rate.

**Statistical Analysis:**
T-test: Performed to analyze the effect of gender on Intensity Karvonen.
ANOVA: Conducted to compare activity levels and their impact on exercise intensity.

**Predictive Modeling:**
Linear Regression: A basic model used to predict Intensity Karvonen.
Random Forest: An advanced ensemble learning method used for better accuracy and handling complex relationships in the data.
Both models were evaluated using metrics like Mean Squared Error (MSE) and R-squared values.
# Results
Linear Regression showed good performance but was outperformed by the Random Forest model, which provided higher accuracy and better predictions.
The statistical analysis revealed that both gender and activity level significantly influence exercise intensity, helping personalize fitness guidance.
