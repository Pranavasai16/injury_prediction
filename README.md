# Injury Prediction using Machine Learning

This project applies multiple machine learning models to predict injury outcomes based on structured data. It includes preprocessing, model training, evaluation, and visualization for a variety of classifiers.

## 📁 Files

- `ml_injurypred.py`: Main Python script.
- `injury_prediction_dataset.csv`: Dataset file included in the repository.

## 🔍 Features

- Label encoding for categorical data
- Standardization of features
- Training with 10 different ML classifiers
- Evaluation using:
  - Accuracy
  - Classification report
  - Confusion matrix
  - ROC curves
  - Prediction count bar plots

## 🧠 Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- XGBoost
- LightGBM
- Neural Network (MLPClassifier)

## 🛠️ Installation

1. Clone this repo or download the files.
2. Install the required packages:

```bash
pip install -r requirements.txt
Ensure the dataset (injury_prediction_dataset.csv) is in the same directory as the script or update the file path in the script.

Run the script:

bash
Copy
Edit
python ml_injurypred.py
📊 Output
Printed accuracy and classification report per model

Plotted confusion matrix and ROC curve

Bar chart of prediction counts

📌 Note
You can modify the models or visualizations easily in the script.

Designed to run in a local Python environment (e.g., VSCode, Jupyter, etc.).