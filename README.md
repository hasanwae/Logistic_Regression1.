# Heart Disease and Iris Classification with Machine Learning

This repository contains two machine learning projects for classification tasks:
1. **Iris Classification** using Support Vector Machine (SVM).
2. **Heart Disease Prediction** using Logistic Regression.

Both projects are implemented in Jupyter Notebooks, utilizing Python libraries such as `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, and `imblearn`.

## Project 1: Iris Classification with SVM

### Overview
This project focuses on classifying iris flowers into three species (Iris-setosa, Iris-versicolor, and Iris-virginica) based on four features: sepal length, sepal width, petal length, and petal width. The analysis is implemented in `Support_Vector_Machine_(SVM).ipynb`.

### Dataset
The dataset (`ir.csv`) is the classic Iris dataset with 150 records and the following columns:
- `sepal_length`: Float (4.3–7.9 cm)
- `sepal_width`: Float (2.0–4.4 cm)
- `petal_length`: Float (1.0–6.9 cm)
- `petal_width`: Float (0.1–2.5 cm)
- `species`: Categorical (Iris-setosa, Iris-versicolor, Iris-virginica)

### Notebook Structure
- **Data Loading**: Load `ir.csv` using `pandas`.
- **Data Exploration**: Display summary statistics and visualize feature relationships with `seaborn.pairplot`.
- **Preprocessing**: Encode the target variable (`species`) using `LabelEncoder`.
- **Future Steps**: Scale features, split data, train SVM model, and evaluate performance.

### Dependencies
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-iris-classification.git
