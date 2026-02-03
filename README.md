# Sampling Assignment
## Program 1: Sampling Techniques on Imbalanced Credit Card Dataset

## Objective
The objective of this assignment is to understand the importance of sampling techniques in handling imbalanced datasets and to analyze how different sampling strategies affect the performance of various machine learning models.

---

## Problem Statement
In real-world applications, datasets are often highly imbalanced, which can significantly impact model performance.  
In this experiment, a credit card dataset is balanced using oversampling, followed by the application of different sampling techniques.  
Five machine learning models are trained on five differently sampled datasets, and their accuracies are compared.

---

## Dataset
The dataset is taken from the following GitHub repository:

**Direct Download Link:**  
https://raw.githubusercontent.com/AnjulaMehto/Sampling_Assignment/main/Creditcard_data.csv

---

## Tools & Libraries Used
- Python 3
- pandas
- scikit-learn

---

## Sampling Techniques Used
1. **Simple Random Sampling**
2. **Systematic Sampling**
3. **Stratified Sampling**
4. **Bootstrap Sampling**
5. **Cluster-like Sampling**

---

## Machine Learning Models Used
- **M1:** Logistic Regression  
- **M2:** K-Nearest Neighbors (KNN)  
- **M3:** Decision Tree Classifier  
- **M4:** Random Forest Classifier  
- **M5:** Support Vector Machine (SVM)

---

## Steps Performed
1. Dataset downloaded using raw GitHub link
2. Analysis of class imbalance
3. Dataset balancing using oversampling
4. Creation of five samples
5. Application of different sampling techniques
6. Training of five machine learning models
7. Evaluation using accuracy metric
8. Comparison of results using an accuracy table

---

## How to Run the Code

### Step 1: Install Required Libraries
```bash
pip install pandas scikit-learn
```
### Step 2: Run the Python Script
```bash
python Sampling.py
```
## Results & Discussion
Sampling techniques significantly influence model performance.
Stratified and Bootstrap sampling generally provide more stable accuracy.
Tree-based models such as Random Forest and Decision Tree perform better on balanced datasets.
Improper sampling may lead to loss of important patterns in data.

## Conclusion
This experiment demonstrates the importance of handling class imbalance using appropriate sampling techniques.
Choosing the right combination of sampling strategy and machine learning model can greatly improve prediction accuracy.

### Submitted by: Dishavpreet Kaur
Roll no:102353006
Subgroup:3C18(L1)
