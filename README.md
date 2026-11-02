# Heart-Disease-Prediction
Predicting heart disease by comparing machine learning models 
# 🫀 Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using machine learning classification algorithms. It analyzes patient health-related attributes and compares multiple models to identify the best-performing algorithm based on prediction accuracy.

The project demonstrates the application of data preprocessing, feature scaling, model training, and performance evaluation using Python and Scikit-learn.

## 🎯 Objectives

* Analyze patient health data to understand the features associated with heart disease.
* Prepare the dataset for machine learning.
* Train and evaluate multiple classification models.
* Compare model performance using accuracy scores.
* Identify the best-performing model among the selected algorithms.

## 🛠️ Technologies Used

* **Python** — Programming language
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical computing
* **Scikit-learn** — Machine learning and model evaluation
* **Jupyter Notebook** — Development environment

## 📂 Dataset Information

The project uses a dataset named `heart.csv`, containing **1,025 records and 14 columns**, including the target variable.

The dataset includes attributes such as:

| Feature    | Description                                        |
| ---------- | -------------------------------------------------- |
| `age`      | Patient's age                                      |
| `sex`      | Sex-related coded value                            |
| `cp`       | Chest pain type                                    |
| `trestbps` | Resting blood pressure                             |
| `chol`     | Serum cholesterol level                            |
| `fbs`      | Fasting blood sugar indicator                      |
| `restecg`  | Resting electrocardiographic results               |
| `thalach`  | Maximum heart rate achieved                        |
| `exang`    | Exercise-induced angina indicator                  |
| `oldpeak`  | ST depression value                                |
| `slope`    | Slope of the peak exercise ST segment              |
| `ca`       | Number of major vessels, as encoded in the dataset |
| `thal`     | Thalassemia-related coded value                    |
| `target`   | Target class used for prediction                   |

**Target variable:** The `target` column is used to train the classification models.

## ⚙️ Project Workflow

### 1. Data Loading

Loaded the heart disease dataset into a Pandas DataFrame.

### 2. Exploratory Data Inspection

Examined the dataset's structure, dimensions, data types, and initial records.

### 3. Missing Value Analysis

Checked all columns for missing values. The notebook reports no missing values in the dataset.

### 4. Feature Selection

Separated the independent variables (`X`) from the target variable (`y`).

### 5. Train-Test Split

Split the dataset into:

* **80% training data**
* **20% testing data**

Used `random_state=42` for reproducibility.

### 6. Feature Scaling

Applied `StandardScaler` to standardize the input features.

### 7. Model Training

Trained three machine learning classification algorithms:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

### 8. Model Evaluation

Compared model accuracy and evaluated the KNN model using a confusion matrix and classification report.

## 🤖 Machine Learning Models

| Algorithm                 | Accuracy |
| ------------------------- | -------: |
| Logistic Regression       |   50.73% |
| K-Nearest Neighbors (KNN) |   52.20% |
| Decision Tree             |   48.78% |

**Best-performing model in this experiment:** K-Nearest Neighbors (KNN), with an accuracy of approximately **52.20%**.

These results reflect the notebook's current execution and should not be interpreted as evidence of clinical reliability.

## 📊 Model Evaluation

The project uses the following evaluation methods:

* **Accuracy Score:** Measures the proportion of correct predictions.
* **Confusion Matrix:** Summarizes correct and incorrect classifications.
* **Classification Report:** Provides precision, recall, F1-score, and support for each target class.

The KNN model achieved approximately 52.20% accuracy on the test set. The results indicate that further model improvement and validation are needed.

## 🚀 How to Run the Project

### Prerequisites

Install Python and the required libraries.

```bash
pip install numpy pandas scikit-learn jupyter
```

### Steps

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/heart-disease-prediction.git
```

**2. Navigate to the project folder**

```bash
cd heart-disease-prediction
```

**3. Add the dataset**

Place `heart.csv` in the project directory, or update the dataset path in the notebook to match your file location.

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open and run the notebook**

Open `Heart_Disease_Prediction_(Riswan).ipynb` and execute the cells in order.

## 💡 Key Learnings

* Working with real-world-style healthcare datasets.
* Performing data inspection and missing value analysis.
* Separating features and target variables.
* Applying feature scaling with StandardScaler.
* Implementing multiple machine learning classification algorithms.
* Comparing models and interpreting evaluation metrics.

## 🔮 Future Improvements

* Improve predictive performance through systematic hyperparameter tuning.
* Investigate class distributions, data quality, and possible duplicate records.
* Explore additional classification algorithms, such as Random Forest.
* Use cross-validation for more reliable model comparison.
* Evaluate precision, recall, F1-score, and ROC-AUC across models.
* Improve the preprocessing pipeline and validate the results on suitable independent data.

## ⚠️ Disclaimer

This project is intended for educational and portfolio purposes only. It is not a clinically validated diagnostic tool and must not be used to diagnose heart disease or make medical decisions.

## 👨‍💻 Author

**Riswan CK**
