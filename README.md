
#  Student Performance Prediction using Logistic Regression

##  Objective
To build a simple machine learning model that predicts whether a student will **pass or fail** based on:
- Hours studied
- Attendance percentage

---

##  Dataset

A small, manually created dataset with the following columns:
- **Hours_Studied**: Number of hours the student studied.
- **Attendance (%)**: Percentage of classes attended.
- **Pass/Fail**: Output label (1 = Pass, 0 = Fail)

###  Sample Data:

| Hours_Studied | Attendance (%) | Pass/Fail |
|---------------|----------------|-----------|
| 5             | 85             | 1         |
| 2             | 60             | 0         |
| 4             | 75             | 1         |
| 1             | 50             | 0         |
| 6             | 90             | 1         |
| 0.5           | 40             | 0         |

---

##  Tools Used
- Python
- Google Colab / Jupyter Notebook
- Libraries:
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

---

##  ML Algorithm
- **Logistic Regression** from `sklearn`

---

##  Steps Performed
1. Created a small dataset manually.
2. Visualized the data using scatter plots.
3. Prepared features (`Hours_Studied`, `Attendance`) and labels (`Pass/Fail`).
4. Split the dataset into training and testing sets.
5. Trained a Logistic Regression model.
6. Evaluated the model using accuracy score.
7. Used `.predict()` to test new student data.

---

##  Example Prediction
```python
# Predict if a student who studied 3 hours and had 72% attendance will pass:
model.predict([[3, 72]])  # Output: [1] => "Pass"
```

---

##  How to Run the Code
1. Clone the repository or open the notebook in Google Colab.
2. Install required libraries (if not already installed).
3. Run all cells to train the model and test predictions.

---

##  GitHub Link (replace this with your actual link)
[👉 Click here to view the notebook on GitHub](https://github.com/shafsoft2010/student-performance-prediction)

---
