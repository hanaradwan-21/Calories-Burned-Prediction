
# Calories Burned Prediction: A Linear Regression Journey 

##  Overview
This project is part of my specialized path in **Artificial Intelligence**. It focuses on predicting calories burned during physical activities. Unlike using automated libraries, I chose to implement the core logic of the algorithm manually to deeply understand the mechanics of machine learning.

##  What’s Special in this Project?
* **Manual Implementation:** I built the **Linear Regression** model from scratch using Python and NumPy.
* **Mathematical Logic:** Instead of just calling a function, I implemented the **Gradient Descent** and **Cost Function** using custom loops to see how the weights ($W$) and bias ($b$) optimize over time.
* **Step-by-Step Transparency:** Every part of the code is dissected to show the underlying logic of the algorithm.

## 📊 Dataset Description
The dataset used is `calories.csv`, which includes various features that affect the energy expenditure:
- **User_ID**: Unique identifier.
- **Duration**: Time spent exercising (in minutes).
- **Heart_Rate**: Beats per minute during the activity.
- **Body_Temp**: Body temperature during the workout.
- **Calories**: The target variable we aim to predict.

##  Tech Stack & Tools
* **Language:** Python
* **Libraries:** * `Pandas` for data manipulation.
    * `NumPy` for mathematical operations and array handling.
    * `Matplotlib` & `Seaborn` for data visualization and exploratory data analysis (EDA).
* **Environment:** Jupyter Notebook.

## 📈 Project Workflow
1.  **Data Preprocessing:** Cleaning the data and handling any missing values.
2.  **Exploratory Data Analysis (EDA):** Visualizing correlations between features (e.g., how Heart Rate affects Calories).
3.  **Model Building:** * Defining the Linear Regression hypothesis.
    * Implementing the Cost Function (Mean Squared Error).
    * Applying Gradient Descent to minimize the error.
4.  **Evaluation:** Testing the model's accuracy on unseen data.

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/Calories-Burned-Prediction.git
   ```
2. Ensure you have `calories.csv` in the project directory.
3. Open the `.ipynb` file in Jupyter Notebook or VS Code and run the cells sequentially.

---



