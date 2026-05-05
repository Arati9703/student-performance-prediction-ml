# 📚 Student Performance Prediction using Machine Learning

This project focuses on predicting whether a student is likely to pass or fail based on academic performance and a few demographic features using machine learning algorithms.

The project demonstrates a complete machine learning workflow including data preprocessing, exploratory data analysis, model training, evaluation, and deployment using Gradio.

## 📂 Dataset

The dataset used in this project was taken from **Kaggle**.

It includes student-related attributes such as:

* Gender
* Lunch type
* Test preparation course
* Math score
* Reading score
* Writing score

A target column was created:

* Result

  * Pass
  * Fail

## 🧠 Machine Learning Models Used

Three classification models were trained and evaluated:

| Model                    | Purpose                       |
| ------------------------ | ----------------------------- |
| Logistic Regression      | Baseline classification model |
| Decision Tree Classifier | Tree-based learning           |
| Random Forest Classifier | Ensemble model                |

The best-performing model was selected based on:

* Accuracy Score
* Confusion Matrix
* Classification Report

## 🚀 Deployment

The final model was deployed using **Gradio** to create an interactive web interface.

Users can input:

* Gender
* Test preparation status
* Lunch type
* Subject scores

Output:

* Pass
* Fail

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Gradio
