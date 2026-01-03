# 🩺 Diabetes Prediction Using Machine Learning

## 📘 Project Overview
This project aims to predict whether a patient has diabetes based on diagnostic measurements.  
Using the **PIMA Indians Diabetes Dataset**, the notebook compares the performance of four popular classification algorithms:
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes (GaussianNB)**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

The project uses **Scikit-learn** for model implementation and evaluation.

---

## ⚙️ Workflow
1. **Import Libraries:** NumPy, Pandas, and Scikit-learn modules.
2. **Load Dataset:** Reads `diabetes.csv`.
3. **Data Preparation:** Splits dataset into features (`X`) and labels (`y`).
4. **Train-Test Split:** 80-20 ratio using `train_test_split`.
5. **Model Training:** Trains KNN, Naive Bayes, Logistic Regression, and SVM models.
6. **Prediction & Evaluation:** Generates predictions and prints a **classification report** for each model.

---

## 📊 Evaluation Metrics
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The results help determine which model performs best for diabetes prediction.

---

## 🧠 Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/diabetes-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd diabetes-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook diabetes_prediction.ipynb
   ```

---

## 📈 Future Improvements
- Add data visualization (Seaborn/Matplotlib).
- Hyperparameter tuning for each model.
- Compare deep learning methods (e.g., ANN).

---

## ✨ Author
Developed by **Mansi Madrewar**  
Feel free to connect and contribute!
