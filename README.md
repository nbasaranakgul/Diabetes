# Diabetes Risk Analysis

## Project Description

This project analyzes a diabetes risk dataset to uncover key patterns, relationships, and insights that can inform healthcare decision-making. The dataset includes features such as blood glucose levels, BMI, physical activity, medication adherence, stress level, sleep hours, hydration level, and more, alongside a calculated risk score.

The primary objectives of this project are:

*   To load and explore the provided diabetes risk dataset.
*   To perform exploratory data analysis (EDA) to understand the characteristics of the data, including distributions of key features and correlations between them.
*   To preprocess the data for potential modeling.
*   To visualize the data to gain deeper insights into patterns and trends related to diabetes risk.

## Dataset
The dataset used in this project is a synthetically generated health dataset designed to support the prediction and analysis of diabetes risk. Covering a simulated time span from 2021 to 2023, it closely mimics real-world health data while maintaining user anonymity and avoiding privacy concerns.

Dataset url : http://www.kaggle.com/datasets/kevintan701/diabetes-prediction-datasets/diabetes_data.csv

The dataset used in this project is named `diabetes_data.csv`. It contains 1000 entries with the following columns:

*   `user_id`: Unique identifier assigned to each user to ensure data privacy and tracking.
*   `date`: Represents the specific date for each record, indicating the time-series nature of the dataset.
*   `weight (kg)`: The user's body weight in kilograms. 
*   `height (cm)`: Height of the individual.
*   `blood_glucose (mg/dL)`: The user's blood glucose level in milligrams per deciliter. This is one of the most crucial indicators for diagnosing diabetes, with values typically ranging between 70 and 300 mg/dL.
*   `physical_activity (minutes/day)`: The daily duration of physical activity, measured in minutes. Physical activity plays a critical role in managing blood glucose levels and reducing diabetes risk.
*   `diet`: A categorical variable describing the quality of the user's diet, labeled as either 'healthy' or 'unhealthy'. Diet plays an important role in diabetes prevention and management.
*   `medication_adherence`: Indicates the extent of the user's adherence to prescribed medication, categorized as 'good' or 'poor'. Proper adherence is crucial for managing blood glucose levels effectively.
*   `stress_level`: The stress level reported by the user, categorized as 'low', 'medium', or 'high'. Chronic stress can significantly impact blood glucose levels and contribute to diabetes risk.
*   `sleep_hours`: The number of hours the user sleeps each day. Adequate sleep is vital for maintaining overall health and stabilizing blood sugar levels.
*   `hydration_level`: Indicates whether the user is adequately hydrated, with values of 'yes' or 'no'. Proper hydration supports optimal body function, which includes maintaining blood glucose balance.
*   `BMI`: Body Mass Index, calculated using the weight and height of the user. BMI is an important indicator of whether an individual is underweight, of normal weight, overweight, or obese, which is directly linked to diabetes risk.
*   `risk_score`: The calculated risk score for each user, generated based on various health metrics. This score helps categorize users into different risk levels:
  -Low Risk (< 30): Users are considered to have a low likelihood of developing diabetes.
  -Moderate Risk (30-60): Users are given preventive advice to lower their risk.
  -High Risk (> 60): Users are at high risk and receive urgent recommendations to manage their condition.

## Project Structure

The project is organized as follows:

*   `diabetes_data.csv`: The dataset file.
*   `notebook.ipynb`: Jupyter Notebook containing the code for data loading, exploration, analysis, visualization, and modeling.
