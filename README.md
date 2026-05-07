Calories Burn Prediction System
An end-to-end Machine Learning project that predicts calories burned during physical activities based on physiological data, featuring an interactive Power BI dashboard for data-driven insights.

📌 Project Overview
Monitoring energy expenditure is vital for fitness tracking. This project utilizes a supervised learning approach to predict calories burned with high precision, achieving an R² score of 99.8%.

🛠️ Tech Stack & Tools
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, XGBoost.

Algorithm: XGBoost Regressor (Extreme Gradient Boosting).

Visualization: Power BI (Interactive Dashboard).

Model Deployment: Serialization via JSON.

📊 Dataset Description
The dataset contains information on 15,000 exercise sessions, including:

User Demographics: Age, Gender, Height, Weight.

Activity Metrics: Duration of exercise, Heart Rate, Body Temperature.

Target Variable: Calories burned.

📈 Key Findings (EDA)
Duration & Heart Rate: Show the strongest positive correlation with calorie burn.

Body Temp: Increases significantly with exercise intensity.

Model Performance: The XGBoost model outperformed linear models, handling non-linear relationships effectively.
How to Run the Project
Clone the repository:

Bash
pip install pandas numpy xgboost matplotlib
Run the Jupyter Notebook Calories_Prediction_Project.ipynb.

Load the calories_model.json to make real-time predictions.

🏆 Achievements
Achieved an MAE (Mean Absolute Error) of 1.48, indicating very high prediction accuracy.

Successfully integrated ML results with an interactive Power BI dashboard.
