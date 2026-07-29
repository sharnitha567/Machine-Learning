# Support Vector Machine (SVM) Classification

## 📌 Project Overview
This project implements a Support Vector Machine (SVM) classifier using Python and the Scikit-learn library. The model is trained on a student dataset to predict whether a student will pass or fail based on study hours and attendance.

## 🎯 Objective
- Implement the Support Vector Machine (SVM) algorithm.
- Split the dataset into training and testing sets.
- Train the SVM model.
- Predict the output for test data.
- Evaluate the model using accuracy and a classification report.

## 🗂️ Dataset
The project uses a custom dataset named **student.csv**.

### Features
- StudyHours
- Attendance

### Target
- FinalGrade
  - 0 = Fail
  - 1 = Pass

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn

## 📚 Libraries
```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.svm import SVC
from sklearn.metrics import accuracy_score, classification_report
```

## ▶️ How to Run
1. Install Python.
2. Install the required libraries:
   ```
   pip install pandas scikit-learn
   ```
3. Place `student.csv` in the same folder as the program.
4. Run the Python file or Jupyter Notebook.

## 📊 Output
The program displays:
- Actual Values
- Predicted Values
- Accuracy
- Classification Report

## 📁 Project Structure
```
SVM-Classification/
│── README.md
│── Ex_2.ipynb
│── student.csv
```

## 📌 Author
**Sharnitha**
