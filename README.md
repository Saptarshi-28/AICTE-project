# AI-powered Medical Diagnosis System ⚕️

This project is an **AI-powered medical diagnostic web application** built to assist in the prediction of multiple diseases using Machine Learning models. The system is designed to help healthcare professionals and patients by providing preliminary diagnostic insights based on patient input data.

## 🔍 Features
- Predicts **five major diseases** using separate machine learning models.
- Interactive web interface built with **Streamlit**.
- Real-time disease prediction with **user-friendly input forms**.
- Visual representation of diagnostic outputs (e.g., prediction results, confidence scores).
- Lightweight and easily deployable system.

## 🧠 Models Used
| Disease                | Machine Learning Model                        |
|------------------------|-----------------------------------------------|
| Parkinson's Disease    | AdaBoost (base estimator: Decision Tree)      |
| Lung Cancer            | K-Nearest Neighbors (KNN)                     |
| Hypothyroidism         | Logistic Regression                           |
| Heart Disease          | Random Forest Classifier                      |
| Diabetes               | Gradient Boosting (base estimator: Decision Tree) |

## 🏗️ Tech Stack
- **Python 3.8+**
- **Streamlit** (for frontend and app deployment)
- **Scikit-learn** (for building ML models)
- **Pandas**, **NumPy** (for data manipulation)
- **Matplotlib**, **Seaborn** (for visualizations)
- **Pickle** (for model serialization)
