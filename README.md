---

# Diabetes Prediction Project Using Machine Learning

This repository contains a machine learning project for predicting diabetes based on demographic and clinical data. The project leverages various machine learning models and techniques to develop an accurate predictive model. This was our undergraduate project for the CSE422 course at BRAC University.

## Project Overview

Diabetes is becoming a major public health concern around the world, necessitating the development of reliable prediction models to aid in early detection and intervention. Our project aims to create a prediction model for diabetes detection using Machine Learning methods.

## Dataset

The dataset used for this project contains demographic and clinical features, including age, gender, BMI, HbA1c level, blood glucose level, hypertension, heart disease, and smoking history. The target variable is binary, indicating the presence or absence of diabetes.

**Dataset Source**: [Kaggle Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

## Used Models

We have used 4 ML Models to train our dataset:

- k-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
  
While assessing the SVM model, we experimented with kernels including Linear, RBF, Poly, and Sigmoid.

## Contents

- **Notebook**: Jupyter notebook [`Diabetes Prediction Project.ipynb`](https://github.com/niloyahsan1/CSE422-ML-Project/blob/main/Diabetes%20Prediction%20Project.ipynb) containing the project code and analysis.
- **Dataset**: CSV file [`Diabetes Prediction Dataset.csv`](https://github.com/niloyahsan1/CSE422-ML-Project/blob/main/Diabetes%20Prediction%20Dataset.csv) containing the dataset used for training and testing.
- **Report**: Project report [`Project Report.pdf`](https://github.com/niloyahsan1/CSE422-ML-Project/blob/main/Project%20Report.pdf) summarizing the project objectives, methodology, results, and conclusions.

## Usage

To run the project code, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/niloyahsan1/CSE422-ML-Project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CSE422-ML-Project
   ```

3. Open and run the Jupyter Notebook (`Diabetes_Prediction_Project.ipynb`) to execute the project code.

## Dependencies

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Contributors

- Chaity Rani Ghosh ([@chaity-1234](https://github.com/chaity-1234))
