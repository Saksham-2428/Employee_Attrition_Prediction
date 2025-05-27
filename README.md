# Employee Attrition Prediction using Random Forest

This project uses a **Random Forest Classifier** to predict employee attrition based on a variety of HR-related features. The model is trained and evaluated on a dataset containing employee records, and visualizations are provided to understand model performance and feature importance.

---

## Dataset

The dataset used is `WA_Fn-UseC_-HR-Employee-Attrition.csv`, which contains employee information such as:

- Demographics (Age, Gender, Marital Status, etc.)
- Job-related attributes (Job Role, Department, Years at Company, etc.)
- Compensation and performance details
- Attrition label (whether the employee left the company)

---

## Project Structure

- **Data preprocessing:**  
  - Drop irrelevant or constant columns (`EmployeeCount`, `Over18`, `StandardHours`, `EmployeeNumber`).  
  - Convert categorical variables to numeric labels using `LabelEncoder`.

- **Model training:**  
  - Split data into training (80%) and testing (20%) sets, keeping class balance using stratification.  
  - Train a Random Forest classifier with 200 trees.

- **Evaluation:**  
  - Predict on the test set and compute accuracy, precision, recall, and F1-score.  
  - Visualize results with confusion matrix heatmap, feature importance bar plot, and attrition distribution plot.

---

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
