# Insurance Data Analysis: Linear Algebra & Machine Learning

A comprehensive data science project applying linear algebra concepts to solve real-world insurance business problems, including customer similarity analysis, benefit prediction, and privacy-preserving data obfuscation.

## 🎯 Project Overview

This project was completed as part of the TripleTen Data Science bootcamp and demonstrates practical applications of linear algebra in machine learning, specifically:

1. **Customer Similarity Analysis** using k-Nearest Neighbors (kNN)
2. **Insurance Benefit Prediction** using classification models
3. **Linear Regression** for benefit amount estimation
4. **Data Obfuscation** for privacy protection using matrix transformations

## 📊 Dataset

- **Source**: Sure Tomorrow Insurance Company customer data
- **Size**: 5,000 customer records
- **Features**: Gender, Age, Income, Family Members, Insurance Benefits
- **Task**: Predict insurance benefits and find similar customers while protecting privacy

## 🔑 Key Findings

### 1. Feature Scaling Impact
- **Unscaled KNN**: F1 score dropped from 0.65 (k=1) to 0.02 (k=8)
- **Scaled KNN**: Consistent F1 scores of 0.91-0.95 across all k values
- **Conclusion**: Scaling is critical for distance-based algorithms

### 2. Model Performance
- **Scaled KNN Classifier**: F1 = 0.95 (k=5)
- **Dummy Models**: F1 ≤ 0.20
- **Linear Regression**: RMSE = 0.34, R² = 0.43

### 3. Data Privacy Innovation
- Successfully implemented matrix-based data obfuscation
- **Zero performance loss**: Predictions identical before/after obfuscation
- Customer data completely protected while maintaining model accuracy

## 🛠️ Technologies Used

- **Python 3.9+**
- **Libraries**: 
  - NumPy - Matrix operations and linear algebra
  - Pandas - Data manipulation
  - Scikit-learn - Machine learning algorithms
  - Seaborn/Matplotlib - Data visualization
  - Jupyter Notebook - Development environment
