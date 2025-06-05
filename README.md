# Task-7-SVM
# SVM Classification on Breast Cancer Dataset 

To build and compare **Linear** and **Non-linear (RBF kernel)** Support Vector Machine (SVM) models for binary classification on the Breast Cancer Wisconsin Diagnostic dataset using Python.

---

##  Tools & Libraries Used:
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn (SVM, PCA, GridSearchCV, Metrics)

---

##  Dataset Description:
- **Dataset:** Breast_cancer_wisconsin.csv
- **Features:** 30 numerical features representing characteristics of cell nuclei.
- **Target Variable:** Diagnosis
  - M → Malignant (1)
  - B → Benign (0)

---

##  Objectives 
- Load and preprocess the dataset.
- Train two SVM models:
  - Linear SVM
  - RBF SVM (Non-linear)
- Visualize decision boundaries using PCA.
- Tune hyperparameters 'c' and 'gamma' using GridSearchCV.
- Evaluate model performance with cross-validation and metrics.

---

##  Program Flow:

1. **Load the dataset**
   Load and remove unnecessary columns like id and Unnamed: 32.
   
2. **Encode the target**
   Column: 'M' as 1 and 'B' as 0.
   
4. **Standardize features**
   Using StandardScaler.

5. **Reduce to 2 dimensions**
    Using PCA for visualization purposes.
   
6. **Train SVM models**:
   - Linear SVM (kernel='linear')
   - RBF SVM (kernel='rbf')
     
7. **Plot decision boundaries**
   In 2D space.
   
8. **Tune hyperparameters**
   Using GridSearchCV.
   
9. **Evaluate performance**
   Using:
   - Accuracy score
   - Confusion matrix
   - Classification report
   - Cross-validation

## Visual Outputs
- Best Tuned RBF SVM (PCA)
- ![Best Tuned RBF SVM (PCA)](https://github.com/user-attachments/assets/db8705e5-a1c5-4bb6-aa6a-885b1046f441)
- Linear SVM Desicion Boundary (PCA)
- ![Linear SVM Desicion Boundary (PCA)](https://github.com/user-attachments/assets/6eeb1eb8-cf66-45e9-991c-d49c30d8a993)
- RBF SVM Decision Boundary (PCA)
- ![RBF SVM Decision Boundary (PCA)](https://github.com/user-attachments/assets/14fd865e-8f70-42ed-a9a2-e793486c35d5)
     
## Conclusion:
RBF kernel SVM slightly outperforms the Linear SVM, indicating the presence of non-linearity in data.
PCA helped us visualize high-dimensional decision boundaries effectively in 2D.
With proper scaling and tuning, SVM performs extremely well on medical classification problems, achieving 97%+ accuracy.

## About

-  SVM Classification on Breast Cancer Datase(task) is completed by Intern- Pavithra
- Tool used to build the project: colab
- learning tool: Google webesite(geek for geeks,w3school, and Ai)
- Thanks to **Elevate Labs**


