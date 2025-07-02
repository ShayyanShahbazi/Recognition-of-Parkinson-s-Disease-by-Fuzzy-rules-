# Recognition-of-Parkinson-s-Disease-by-Fuzzy-rules-
This project showcases how fuzzy systems can assist in medical diagnosis tasks involving imprecise symptoms, with Parkinson's disease as a case study. The combination of domain knowledge and data-driven learning (via FCM and GA) makes the approach both interpretable and adaptable.


# Parkinson's Disease Recognition Using Fuzzy Systems

This project focuses on the diagnosis and assessment of Parkinson's disease using various fuzzy logic systems. The main goal is to demonstrate how fuzzy systems can model the uncertainty and imprecision of human symptoms in Parkinson's diagnosis. The systems are evaluated and compared using a combination of expert knowledge, machine learning clustering, and rule-based inference.

## 📌 Features

- **Input Parameters**: 
  - Bradykinesia (slowness of movement)
  - Tremor (shaking)
  - Rigidity (muscle stiffness)

- **Implemented Fuzzy Systems**:
  - **Expert-Based Fuzzy System**: Uses predefined trapezoidal membership functions and expert-defined rules.
  - **FCM-Based Fuzzy System**: Learns membership functions using the Fuzzy C-Means clustering algorithm.
  - **Sugeno Fuzzy Inference System**: Implements rules with numerical outputs and weighted averaging.
  - **Mamdani Fuzzy Inference System**: Classical fuzzy system with graphical outputs and centroid defuzzification.

- **Machine Learning Integration**:
  - Fuzzy C-Means (FCM) clustering is used to identify fuzzy membership values based on normalized symptom data.

- **Genetic Algorithm Optimization**:
  - A simple genetic algorithm searches for the combination of symptom values that maximizes Parkinson's likelihood.

- **Visualization**:
  - Comparative plots of membership functions
  - Decision surfaces for 2D inputs
  - Bar charts of test case evaluations and RMSE comparisons

## 📊 Evaluation

The systems are tested on various synthetic cases ranging from healthy individuals to severe Parkinsonian symptoms. Metrics such as **Root Mean Squared Error (RMSE)** are used to compare the performance of each fuzzy system against expected outputs.

## 🔧 Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `skfuzzy`
  - `sklearn`

You can install the required packages using:

```bash
pip install numpy pandas matplotlib scikit-fuzzy scikit-learn
