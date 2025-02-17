Bayes-KNN Analysis

Overview
This project explores Bayesian probability and K-Nearest Neighbors (KNN) in the context of test kit performance evaluation. The goal is to analyze test results using Bayes' Theorem to determine the accuracy of different test kits and assess how many tests are required to achieve a 90% confidence level in detecting COVID cases.

Project Objectives
Simulate random test results using NumPy and Python.

Compute True Positive Rate (TPR) and False Positive Rate (FPR) for two different test kits.

Use Bayes' Theorem to determine which test kit performs better.

Identify how many tests are needed to reach a 90% confidence level in detecting a positive case.

Methodology

Generating Test Data:

Three datasets (x1, x11, x111) are generated using random numbers to simulate test results.

The values are adjusted to represent positive (1) and negative (-1) cases.

Creating Test Kits:

TestKit1: Combines x1 and x11

TestKit2: Combines x11 and x111

Actual Diagnosis (fact): Derived from x1 and x111

Evaluating Performance:

Compute True Positive Rate (TPR) and False Positive Rate (FPR) for both test kits.

Use Bayes' Theorem to estimate accuracy.

Determine how many tests are needed to reach 90% confidence in detecting a positive case.

Key Findings
Comparison of Test Kits: By analyzing the TPR and FPR, we determine which test kit is more reliable.

Test Iterations for Confidence: Using Bayesian calculations, we estimate how many repeated tests are needed for 90% certainty of infection detection.

Technologies Used

Python (NumPy, Random)

Probability & Statistics (Bayes' Theorem, TPR, FPR)

Data Analysis (Logical comparisons, array manipulations)

Usage

Clone the repository and run the Python script:

# Clone the repository
git clone https://github.com/alamin19/bayes-knn-analysis.git
cd bayes-knn-analysis

# Run the script
python bayes_knn_analysis.py

Future Enhancements

Extend analysis to real-world datasets.

Implement machine learning classifiers to compare with Bayesian results.

Optimize test iteration calculations for faster predictions.

Author

Developed by Al Amin 
