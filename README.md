# Student Performance Classification

This project focuses on predicting student performance based on multiple features using various classification algorithms. The dataset is preprocessed and analyzed using visualization techniques, followed by implementation and evaluation of models such as Logistic Regression, Decision Tree, and Random Forest.

## Contents

- Data Import and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model Evaluation:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Conclusion and Insights

## Dataset

The dataset used includes features such as:

- Gender
- Nationality
- Place of birth
- Stage of education
- Grade
- Section ID
- Topic
- Semester
- Parent's engagement and satisfaction
- Student absence days

The target variable is **Class** (L - Low, M - Middle, H - High performance).

## Requirements

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Running the Project
Open the Jupyter Notebook:
Run each cell sequentially to perform data preprocessing, modeling, and evaluation.

##Model Results

All models were evaluated based on classification accuracy, precision, recall, and F1-score. Insights about which features most influence student performance are also presented.

##Conclusion

   - Random Forest performed best among tested models.

   - Parental involvement and attendance were key indicators of performance.

   - Preprocessing and feature encoding significantly affected model accuracy.
