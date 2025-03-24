# Stroke Prediction Project

## Overview
This project predicts the likelihood of a stroke using **machine learning** and **deep learning** techniques. It includes **exploratory data analysis (EDA)**, data preprocessing, and model training with traditional and ensemble learning methods.

## Features and Methodology
### **Exploratory Data Analysis (EDA)**
- Analyzing feature distributions
- Correlation analysis with stroke occurrence

### **Data Preprocessing**
- Handling missing values
- Feature scaling and encoding
- **SMOTE** for dataset balancing

### **Machine Learning Models**
- **KNN**, **Logistic Regression**, **Decision Tree**, **Naive Bayes**, **SVM**

### **Ensemble Learning Models**
- **Voting Classifier**, **Bagging Classifier**, **Stacking Classifier**

### **Deep Learning Models**
- **Neural Networks (MLP)** with dropout & early stopping
- **Recurrent Neural Networks (RNN)** with hyperparameter tuning

## Libraries Used
### **Data Manipulation & Visualization**
- `pandas`, `numpy`, `seaborn`, `matplotlib`

### **Machine Learning**
- `sklearn`, `imblearn`

### **Deep Learning**
- `tensorflow`, `keras`

## How to Use
1. **Clone the repository and install dependencies:**
   ```bash
   git clone <repo_link>
   cd stroke_prediction
   pip install -r requirements.txt
   ```
2. **Run the Jupyter Notebook** for data analysis and model training.
3. **Evaluate models** using accuracy, confusion matrix, and classification reports.

## Results
- Multiple models are evaluated to determine the best-performing classifier.
- **Stacking Classifier** and **Neural Networks** achieve the highest accuracy.
