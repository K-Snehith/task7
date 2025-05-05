# 🧠 Task 7 - Support Vector Machine (SVM) Classification

## 🎯 Objective  
Use Support Vector Machine (SVM) to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer dataset from `sklearn`.

---

## 📁 Dataset  
- Dataset: Breast Cancer (from `sklearn.datasets.load_breast_cancer`)  
- Features: 30 numeric features  
- Target:  
  - `0`: Malignant  
  - `1`: Benign

---

## 🛠 Tools Used  
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn

---

## 📚 Steps Performed  

1. Loaded the Breast Cancer dataset using sklearn  
2. Converted it to a Pandas DataFrame for easier handling  
3. Split the dataset into training and testing sets (75% training, 25% testing)  
4. Trained a Support Vector Machine classifier (`SVC`)  
5. Made predictions on the test data  
6. Evaluated the model using:  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

---

## 📈 Sample Output  

```text
✅ Dataset loaded successfully!
   mean radius  mean texture  ...  worst fractal dimension  target
0        17.99         10.38  ...                  0.11890       0
1        20.57         17.77  ...                  0.08902       0
...

📊 Classification Report:

              precision    recall  f1-score   support

           0       0.93      0.95      0.94        43
           1       0.97      0.96      0.96        71

    accuracy                           0.96       114
   macro avg       0.95      0.96      0.95       114
weighted avg       0.96      0.96      0.96       114

📉 Confusion Matrix:
[[41  2]
 [ 3 68]]

✅ Accuracy Score: 0.956140350877193
