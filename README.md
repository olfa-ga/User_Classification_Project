# User_Classification_Project

## Project Overview
This project is a **Machine Learning pipeline** to classify students as either **potential purchasers** or **unlikely purchasers** based on their platform activity.  
It demonstrates **data preprocessing**, **feature engineering**, and several classification models including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)

The goal is to predict which users are likely to purchase a subscription, allowing targeted marketing strategies.

---

## Dataset
The dataset **is not included** in this repository for privacy reasons.  

To run this project, you will need a CSV file named `ml_datasource.csv`  with the following structure:

| student_id | minutes_watched | courses_started | practice_exams_started | minutes_spent_on_exams | days_on_platform | student_country | purchased |
|------------|----------------|----------------|-----------------------|------------------------|-----------------|----------------|-----------|
| 1          | 120            | 2              | 1                     | 15                     | 10              | USA            | 0         |

- `purchased`: 1 if the student purchased a subscription, 0 otherwise.

---

## File Structure

User_Classification_Project/
 User_Classification.ipynb # Jupyter notebook with full workflow
 README.md # Project description and instructions


---

## Usage Instructions

1. **Provide your dataset**  
   Place your CSV file (`ml_datasource.csv`) in the same folder as the notebook.

2. **Open the notebook**  
   Open `User_Classification.ipynb` in Jupyter Notebook or VSCode Jupyter extension.

3. **Run all cells**  
   The notebook will:
   - Preprocess the data
   - Train Logistic Regression, KNN, and SVM models
   - Show performance metrics and visualizations
   - Compare model results

---

## Models Trained

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machines (SVM)**



---

## Notes

- The dataset is **not included** due to privacy concerns.
- Ensure all required libraries are installed: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels`.

