#Student Productivity Prediction Using Machine Learning
#Project Overview
This project focuses on predicting **student productivity** based on their daily study hours using a **Linear Regression** model. The objective is to understand how study habits influence productivity and to implement an end-to-end **machine learning workflow**.

This is a **beginner-friendly data science project** designed to strengthen practical skills in Python, data analysis, and machine learning.

# Problem Statement
To analyze student study patterns and build a machine learning model that predicts the **Productivity Index** of students based on the number of hours they study daily.

#Dataset
* **File name:** `Students_Performance_data_set.csv`
* **Feature (Input):** `study_hours`
* **Target (Output):** `Productivity_Index`

The dataset contains information related to students' study behavior and corresponding productivity levels.

#Tools & Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook

#Methodology
1. **Data Loading & Exploration**
   * Loaded dataset using Pandas
   * Checked data types, missing values, and basic statistics

2. **Data Cleaning**
   * Handled missing values
   * Removed duplicates
   * Renamed columns for better readability

3. **Exploratory Data Analysis (EDA)**
   * Analyzed the relationship between study hours and productivity
   * Visualized data using scatter plots

4. **Feature Selection**
  * Selected relevant feature (`study_hours`) and target (`Productivity_Index`)

5. **Model Building**
   * Split data into training and testing sets
   * Built a **Linear Regression** model using Scikit-learn

6. **Model Evaluation**
     * Evaluated model performance using:
     * R² Score
     * Mean Absolute Error (MAE)

# Results
The Linear Regression model successfully learned the relationship between study hours and productivity. The model demonstrated reasonable performance on unseen test data, showing that study hours have a meaningful impact on student productivity.

#Key Learnings
* End-to-end machine learning workflow
* Data cleaning and preprocessing techniques
* Feature selection and model training
* Model evaluation using regression metrics
* Practical application of Linear Regression

# How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the Jupyter Notebook
4. Run all cells step by step

# Conclusion
This project helped me gain hands-on experience in **data science and machine learning** by applying theoretical concepts to a real dataset. It strengthened my understanding of how to build, evaluate, and interpret machine learning models.

*If you find this project useful, feel free to star the repository!*
