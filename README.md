# 🧠 Parkinson’s Disease Detection using XGBoost

## 📌 Project Overview
This project builds a machine learning model to classify whether a person has Parkinson’s disease using voice measurement features. The model uses XGBoost, an advanced gradient boosting algorithm based on decision trees.

## 📊 Dataset
- Source: UCI Machine Learning Repository  
- Dataset: Parkinson’s Dataset  
- Features: Biomedical voice measurements  
- Target Variable: `status`  
  - 0 → Healthy  
  - 1 → Parkinson’s Disease  

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- XGBoost  

## 🚀 Steps Performed
1. Imported required libraries  
2. Loaded dataset from UCI repository  
3. Removed unnecessary column (`name`)  
4. Split data into features (X) and target (y)  
5. Performed train-test split  
6. Built XGBoost classifier model  
7. Trained the model on training data  
8. Made predictions on test data  
9. Evaluated model using accuracy, confusion matrix, and classification report  
10. Visualized feature importance  

## 🤖 Model Details
- Algorithm: XGBoost Classifier  
- Evaluation Metric: Log Loss  
- Random State: 42  

## 📈 Performance
- Accuracy: **94.87%**

### Confusion Matrix
[[ 5 2]
[ 0 32]]

### Classification Report
- High precision and recall for detecting Parkinson’s patients  
- Balanced performance across classes  

## 📊 Visualization
- Feature importance plot shows which attributes most influence prediction  

## 📁 Project Structure
parkinsons-disease-detection-xgboost/
│
├── notebook.ipynb
├── README.md
## 🔮 Output
The model predicts whether a person is healthy or has Parkinson’s disease with high accuracy based on input features.

## 🎯 Conclusion
This project demonstrates how machine learning, especially XGBoost, can be effectively used for medical diagnosis and early disease detection.
- Accuracy: **94.87%**  

### Confusion Matrix
