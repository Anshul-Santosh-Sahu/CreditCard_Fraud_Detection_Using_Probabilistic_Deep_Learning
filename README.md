🧠 Credit Card Fraud Detection Using Probabilistic Deep Learning Models
📌 Problem Statement

Detect fraudulent credit card transactions using deep learning models that can quantify prediction uncertainty and identify anomalies effectively.

🧩 Techniques Used

Monte Carlo Dropout (MC Dropout) – Uncertainty-based classification through stochastic forward passes.

Ensemble Neural Networks (Ensemble NN) – Robust probabilistic prediction using multiple independent models.

Variational Autoencoder (VAE) – Anomaly detection using reconstruction error for unsupervised fraud identification.

🧠 Explanation

This project applies probabilistic deep learning to enhance fraud detection in financial transactions. Traditional classifiers often make overconfident predictions, which can be risky in detecting rare fraudulent activities.
By incorporating uncertainty estimation and anomaly detection, the proposed approach improves model reliability and interpretability.

MC Dropout introduces randomness at inference to estimate uncertainty.

Ensemble NN combines predictions from multiple networks to improve confidence calibration.

VAE learns the data distribution and detects anomalies based on reconstruction errors, identifying suspicious patterns.

📂 Dataset Link

The dataset used is the Credit Card Fraud Detection Dataset (Kaggle)
.
It contains transactions made by European cardholders in September 2013, with highly imbalanced labels (fraudulent vs. legitimate).
