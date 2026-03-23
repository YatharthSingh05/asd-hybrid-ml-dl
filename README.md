# Autism Spectrum Disorder Prediction using Hybrid ML-DL Model

## Overview
This project presents an explainable hybrid machine learning and deep learning framework for early prediction of Autism Spectrum Disorder (ASD) using screening questionnaire data.

---

## Models Implemented
- Logistic Regression  
- Random Forest  
- XGBoost  
- Deep Neural Network (DNN)  
- Hybrid Model (DNN + XGBoost)  

---

## Methodology
- Data preprocessing and cleaning  
- Handling missing values  
- Feature encoding  
- SMOTE for class balancing  
- Train-test split (70–30)  
- Model training and evaluation  
- Deep feature extraction using DNN  
- Hybrid model using XGBoost  
- Explainability using SHAP  

---

## Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | 1.00 |
| Random Forest | 0.976 |
| XGBoost | 0.976 |
| DNN | 0.995 |
| Hybrid | 0.991 |

---

## Explainability
SHAP analysis indicates that the hybrid model relies predominantly on a dominant latent feature, suggesting effective feature compression by the neural network.

---

## Project Structure
asd-hybrid-ml-dl/
│
├── ASD_Project.ipynb
├── model_results.csv
├── ml_results.csv
├── README.md


---

## Key Insights
- The ASD dataset is highly predictive and nearly linearly separable  
- Simple models such as Logistic Regression achieve very high performance  
- Hybrid models improve stability and interpretability  
- Deep learning compresses features into a dominant representation  

---

## Future Work
- Evaluation on larger and diverse datasets  
- Implementation of cross-validation  
- Improved feature engineering  
- Real-world deployment and validation  

---

## Author
Yatharth Singh
