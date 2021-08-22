# Prueba
This repository contains 3 Python scripts
## Fraud_Detection_CML_unbalanced
This script shows the efficiency of different classical machine learning algorithms (IsolationForest and the LocalOutlierFactor) for detecting Fraudulent transactions of unbalanced data. 
The main problem is not the accuracy (over 99% of the total transactions) but the way the Fraud number is being counted. This arises due to the unbalanced data. 
As a matter of fact, the best of them (IsolationForest) gives rise to only 30% detection of the total fraudulent transactions.
## Fraud_Detection_CML_balanced
This script shows the efficiency of different classical machine learning algorithms (DecisionTreeClassifier and RandomForestClassifier) for detecting Fraudulent transactions of balanced data. In both cases, the efficiency of detection rounds 90% of success. This occurs due to pre-data processing.
## # Neural Networks
This script shows a commented QISKIT tutorial of Neural Networks as data classifiers. Among them, one can find the accuracy of OpflowQNN, CircuitQNN, and VQC.
