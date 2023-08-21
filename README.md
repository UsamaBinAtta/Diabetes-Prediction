# Diabetes-Prediction

Project Diabetes Prediction Using Support Vector Machine

Welcome to the "Diabetes Prediction Using Support Vector Machine" project repository! In this project, our goal is to predict the likelihood of an individual having diabetes using the Support Vector Machine (SVM) algorithm.

Table of Contents

Project Overview

Dataset

Requirements

Usage

Model Training

Evaluation

Results

Contributing

License

Project Overview

Diabetes is a prevalent chronic condition that requires early detection for effective management. This project showcases the utilization of the Support Vector Machine algorithm to predict diabetes based on a variety of health-related features.

Dataset

The dataset used in this project is sourced from [source-link], featuring attributes such as age, BMI, glucose levels, insulin levels, and more. The dataset is divided into training and testing subsets, enabling the training and evaluation of our SVM model.

Requirements

To run this project, ensure you have:

Python 3.7+
Required packages as specified in requirements.txt
You can install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt
Usage
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/usamabinatta/diabetes-prediction.git
cd diabetes-svm-prediction
Install the required packages listed in the Requirements section.

Prepare your dataset:

Download the dataset from Kaggle.Also I have attached dataset file
Place the dataset files in the data/ directory.
Run the SVM prediction script:

bash

Copy code
python predict_diabetes_svm.py

Model Training

Training of the SVM model is conducted on the training dataset. Details regarding the model parameters, kernel selection, and preprocessing steps can be found in the train_svm_model.ipynb Jupyter Notebook.

Evaluation

The trained SVM model is evaluated using the testing dataset. Evaluation metrics include accuracy, precision, recall, and F1-score. A comprehensive assessment of the evaluation results is available in the evaluation_results.ipynb Jupyter Notebook.

Results

Our SVM model achieved an accuracy of 85% on the testing dataset. Detailed evaluation metrics can be explored in the evaluation_results.ipynb notebook.

Contributing

We welcome contributions to improve the project! To contribute:

Fork this repository.

Create a new branch: git checkout -b feature/your-feature-name.
Implement your changes and commit: git commit -m "Add feature XYZ".
Push to your branch: git push origin feature/your-feature-name.
Submit a pull request detailing your modifications.

License

This project is licensed under the MIT License.
