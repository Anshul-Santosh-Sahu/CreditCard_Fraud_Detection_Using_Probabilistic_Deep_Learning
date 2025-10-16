## 💳 Credit Card Fraud Detection Using Probabilistic Deep Learning 

🧠 Problem Statement

Detect fraudulent credit card transactions using deep learning models that can quantify prediction uncertainty and identify anomalies effectively.

🧩 Techniques Used

🔹 Monte Carlo Dropout (MC Dropout) – Uncertainty-based classification through stochastic forward passes.

🔹 Ensemble Neural Networks (Ensemble NN) – Robust probabilistic prediction using multiple independent models.

🔹 Variational Autoencoder (VAE) – Anomaly detection using reconstruction error for unsupervised fraud identification.

📘 Explanation

This project applies probabilistic deep learning to enhance fraud detection in financial transactions. Traditional classifiers often make overconfident predictions, which can be risky in detecting rare fraudulent activities.
By incorporating uncertainty estimation and anomaly detection, the proposed approach improves model reliability and interpretability.

1. MC Dropout introduces randomness at inference to estimate uncertainty.

2. Ensemble NN combines predictions from multiple networks to improve confidence calibration.

3. VAE learns the data distribution and detects anomalies based on reconstruction errors, identifying suspicious patterns.

📂 Dataset Link

📊 Dataset used: Credit Card Fraud Detection Dataset (Kaggle)

This dataset contains real transactions made by European cardholders in September 2013, with a highly imbalanced class distribution (fraudulent vs. legitimate).

🧾 File Information

Notebook Name: CreditCard_Fraud_Detection_Using_Probabilistic_Deep_Learning.ipynb

Language: Python

Frameworks: TensorFlow / Keras, NumPy, Matplotlib, Scikit-learn
