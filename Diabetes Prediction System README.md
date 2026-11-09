# Diabetes Prediction System 🩺

## Overview
This project uses Machine Learning to predict whether a person is diabetic or not based on medical and health-related information. It uses a Support Vector Machine (SVM) classifier to make predictions.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Support Vector Machine (SVM)

## Dataset
The project uses the diabetes dataset containing 768 records and 8 independent features.

**Features:**
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

**Target Variable:** Outcome
- 0 = Non-Diabetic
- 1 = Diabetic

## Project Workflow

1. **Data Collection:** Load the diabetes dataset using Pandas.
2. **Data Analysis:** Explore the dataset using `info()`, `describe()`, and `value_counts()`.
3. **Data Preprocessing:** Separate input features and target variables.
4. **Data Standardization:** Apply `StandardScaler` to standardize the input features.
5. **Train-Test Split:** Split the dataset into 80% training data and 20% testing data.
6. **Model Training:** Train a Support Vector Machine (SVM) classifier with a linear kernel.
7. **Model Evaluation:** Evaluate model performance using `accuracy_score`.
8. **Prediction System:** Predict diabetes outcomes using new input data.

## Model Performance

| Dataset | Accuracy |
|---|---:|
| Training Data | 78.66% |
| Testing Data | 77.27% |

## Libraries Used

```python
import numpy as np
import pandas as pd
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn import svm
from sklearn.metrics import accuracy_score
```

## How to Run the Project

1. Clone this repository.
2. Install the required libraries:

```bash
pip install numpy pandas scikit-learn
```

3. Open `Diabetes_Prediction.ipynb` using Jupyter Notebook or Google Colab.
4. Make sure `diabetes.csv` is available in the correct location.
5. Run all cells to train the model and make predictions.

## Conclusion

This project demonstrates how Machine Learning can be used to predict diabetes outcomes using a Support Vector Machine classifier. It provides practical experience with data preprocessing, standardization, model training, and evaluation.

**Note:** This project is for educational purposes only and is not a substitute for professional medical diagnosis.
