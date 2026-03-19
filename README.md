Comparison Analysis of Ensemble Models for Intrusion Detection in IoT Systems
📌 Overview

This project focuses on evaluating and comparing the performance of individual and hybrid machine learning/deep learning models for intrusion detection in IoT (Internet of Things) environments.

The goal is to improve detection accuracy and robustness by leveraging ensemble and hybrid architectures, combining the strengths of different models.

Objectives

Build and train individual models for intrusion detection

Develop hybrid/ensemble models for improved performance

Perform comparative analysis using key evaluation metrics

Visualize results through an interactive dashboard

Models Implemented
🔹 Individual Models

GRU (Gated Recurrent Unit)

CNN (Convolutional Neural Network)

LSTM (Long Short-Term Memory)

Autoencoder

XGBoost

🔹 Hybrid / Ensemble Models

GRU + XGBoost

Autoencoder + XGBoost

CNN + LSTM
These hybrid models combine feature extraction (deep learning) with classification (machine learning) to enhance detection performance.

📊 Data Analysis & Evaluation

The models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Comparative analysis was performed to determine:

Best-performing model

Trade-offs between models

Efficiency in detecting anomalies in IoT systems

Dashboard & Visualization

An interactive dashboard was developed to present results and insights.

🛠 Technologies Used:

Python

Flask – for backend integration

Dash (Plotly) – for interactive data visualization

📌 Dashboard Features:

Model performance comparison charts

Real-time metric visualization

Confusion matrix display

Interactive filtering and analysis

Tech Stack

Programming Language: Python

Machine Learning: XGBoost, Scikit-learn

Deep Learning: TensorFlow / Keras / PyTorch

Data Processing: Pandas, NumPy

Visualization: Plotly, Dash

Web Framework: Flask
