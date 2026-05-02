# Student Performance Analysis & Prediction

A data science project focused on identifying factors that influence academic success and building a predictive model to forecast student scores using Machine Learning.

---

## 📌 Project Overview
This project explores the relationship between study habits, attendance, and academic results. It follows a complete data science workflow, from **Exploratory Data Analysis (EDA)** to building and evaluating a **Linear Regression** model[cite: 1].

## 🚀 Key Features
*   **Comprehensive EDA:** Data cleaning and statistical summarization using Python[cite: 1].
*   **Data Visualization:** Interactive and static charts (Heatmaps, Histograms, Regression Plots) to identify trends[cite: 1].
*   **Machine Learning:** Implementation of a Scikit-Learn Linear Regression model[cite: 1].
*   **Predictive Analytics:** Forecasting student scores based on input features with high precision[cite: 1].

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn[cite: 1].
*   **ML Framework:** Scikit-Learn[cite: 1].
*   **Tools:** Jupyter Notebook / VS Code.

## 📊 Dataset Detail
The analysis utilizes the `Student_Performance_Data.csv` dataset, which contains 150 student records[cite: 1].
*   **Study_Hours**: Numeric (2 - 18 hours).
*   **Attendance_Percentage**: Numeric (60% - 100%).
*   **Scores**: The target variable (0 - 100).

## 📈 Insights & Results
1.  **Correlation:** There is a strong linear relationship (0.96) between study hours and final scores[cite: 1].
2.  **Model Performance:** 
    *   **Mean Absolute Error (MAE):** ~2.94
    *   **R-Squared Score:** 0.96 (The model explains 96% of the variance in scores)[cite: 1].
3.  **Visualization:** The regression analysis confirms that consistent study hours are the primary predictor of success in this dataset[cite: 1].

## ⚙️ Setup & Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/student-performance-prediction.git](https://github.com/YOUR_USERNAME/student-performance-prediction.git)
2. Install required packages:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
3. Run the notebook:
   ```bash
   jupyter notebook Task1.ipynb
## 📜 License
This project is licensed under the MIT License.
