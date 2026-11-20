Random Forest Classification – Six Optimization Algorithms

Project Overview

This project implements a Random Forest Classification model for binary classification and compares six optimization algorithms used for hyperparameter optimization.

The main objective is to evaluate the performance of different optimization strategies using classification metrics and compare their effectiveness.

Dataset

Breast Cancer Wisconsin Diagnostic Dataset

* Source: Scikit-learn
* Problem Type: Binary Classification
* Features: 30 numerical features
* Classes: Benign and Malignant

Machine Learning Algorithm

* Random Forest Classifier

Optimization Algorithms

The project compares six optimization algorithms:

1. Gradient Descent (GD)
2. Stochastic Gradient Descent (SGD)
3. Mini-Batch Gradient Descent
4. Momentum
5. RMSprop
6. Adam

Note: Since Random Forest does not use gradient descent internally, the optimization algorithms are adapted using Simultaneous Perturbation Stochastic Approximation (SPSA) to optimize the model’s hyperparameters.

Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Log Loss
* Confusion Matrix
* ROC Curve and AUC

Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Kaggle Notebook

Project Structure

Random-Forest-Classification/
│
├── Random_Forest_Classification_Optimization.ipynb
└── README.md

How to Run

1. Download or clone this repository.
2. Open the Jupyter Notebook using Kaggle or Google Colab.
3. Run all cells in order.
4. Review the evaluation metrics, visualizations, and comparison results.

Project Goals

* Implement Random Forest Classification.
* Apply six optimization strategies for hyperparameter tuning.
* Evaluate model performance.
* Compare optimization algorithms.
* Identify the best-performing optimization strategy in this experiment.

Author

Hussein Zaid Al-Otoum

Data Science and Artificial Intelligence Student

Conclusion

This project provides a comparative study of six optimization algorithms for Random Forest hyperparameter tuning, highlighting their impact on classification performance and model evaluation metrics.
