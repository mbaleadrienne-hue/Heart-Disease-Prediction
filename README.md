# Heart Disease Prediction - 90% Accuracy

Heart Disease Prediction using Machine Learning | Accuracy 90% | Random Forest vs Logistic Regression

### Dataset Source
Dataset from **Kaggle - Heart Failure Prediction Dataset** (918 patients, 11 clinical features)
Link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
Target: HeartDisease (0 = healthy, 1 = disease)

### Pipeline
1. Cleaning: fixed `FastingBS ` column
2. Preprocessing: StandardScaler for numeric, OneHotEncoder for categorical
3. Train/Test split: 80/20
4. Models: Logistic Regression and Random Forest

### Results
| Model | Accuracy | Precision | Recall |
| :--- | :--- | :--- | :--- |
| Logistic Regression | 0.85 | 0.90 | 0.84 |
| Random Forest | **0.90** | **0.92** | **0.90** |

Best Model: RandomForest - Only 19 errors on 184 test patients
[[69 8] [11 96]]

### How to run
pip install pandas scikit-learn
jupyter notebook Heart_PJT.ipynb

### Author
Project built by **Adrienne** - Data Science enthusiast | From Kaggle dataset to 90% accuracy with custom ML pipeline.
