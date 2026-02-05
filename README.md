# Breast Cancer Classification using PCA and Logistic Regression

## 📌 Project Overview
This project demonstrates a complete machine learning workflow for **binary classification** using **Principal Component Analysis (PCA)** and **Logistic Regression**.  
The goal is to classify tumors as **Malignant (M)** or **Benign (B)** using the Breast Cancer dataset.

---

## 📂 Dataset
- Dataset: Breast Cancer Wisconsin Dataset
- File used: `data.csv`
- Target column: `diagnosis`
  - `M` → Malignant
  - `B` → Benign

---

## ⚙️ Workflow

1. **Data Loading**
   - Load dataset using Pandas
   - Inspect shape, columns, and data types

2. **Data Cleaning**
   - Remove unnecessary columns
   - Handle missing values
   - Check duplicates

3. **Exploratory Data Analysis**
   - Basic statistical summary
   - Feature inspection

4. **Feature Scaling**
   - Standardization using `StandardScaler`
   - Required before applying PCA

5. **Dimensionality Reduction**
   - Applied **Principal Component Analysis (PCA)**
   - Reduced high-dimensional feature space while preserving variance

6. **Model Building**
   - Logistic Regression classifier
   - Train-test split

7. **Model Evaluation**
   - Classification Report
   - Confusion Matrix
   - Accuracy Score
   - ROC Curve & AUC Score

---

## 🧠 Algorithms Used

- Principal Component Analysis (PCA)
- Logistic Regression

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

---

## 🛠️ Libraries & Tools

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/pca-logistic-regression-breast-cancer.git
   ```
Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook PCA_logistic_regression.ipynb

📌 Key Learnings

Importance of feature scaling before PCA

How PCA helps reduce dimensionality

Logistic Regression for binary classification

Model evaluation using multiple metrics

🚀 Future Improvements

Try different number of PCA components

Compare with models without PCA

Use other classifiers (SVM, Random Forest)

Hyperparameter tuning

👤 Author

Devendra Kushwah

Feel free to ⭐ the repository if you found it useful!
