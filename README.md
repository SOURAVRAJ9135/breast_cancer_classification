🧠 Breast Cancer Diagnosis Using Artificial Neural Network (ANN)
📌 Project Overview

This project implements an Artificial Neural Network (ANN) to predict whether a breast tumor is benign or malignant using diagnostic features extracted from breast cancer data. The model leverages 30 independent input features and achieves a high predictive performance with an accuracy of 99.6%, demonstrating the effectiveness of neural networks in medical classification tasks.

🎯 Objectives

Build a robust ANN model for breast cancer classification

Minimize false negatives, which is critical in healthcare applications

Evaluate model performance using accuracy metrics

Demonstrate end-to-end workflow from data preprocessing to model evaluation

🗂 Dataset

Dataset: Breast Cancer Wisconsin (Diagnostic)

Number of features: 30 numerical diagnostic measurements

Target variable:

0 → Benign

1 → Malignant

Each feature represents computed characteristics of cell nuclei obtained from digitized images.

⚙️ Model Architecture

The neural network was designed using a feed-forward multilayer architecture:

Input Layer

30 neurons (one for each diagnostic feature)

Hidden Layer 1

Fully connected

Activation function: ReLU

Hidden Layer 2

Fully connected

Activation function: ReLU

Output Layer

1 neuron

Activation function: Sigmoid (binary classification)

🧪 Training & Evaluation

Loss Function: Binary Cross-Entropy

Optimizer: Adam

Performance Metric: Accuracy

Final Accuracy Achieved: 99.6%

The model demonstrates excellent generalization and reliability on unseen data.

🛠 Technologies Used

Python

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Google Colab

🔄 Workflow

Data loading and exploration

Feature scaling and preprocessing

ANN model construction

Model training and validation

Performance evaluation

✅ Results

The trained ANN model successfully classifies breast cancer cases with high accuracy (99.6%), indicating its potential usefulness as a decision-support tool in early breast cancer diagnosis.

📌 Conclusion

This project highlights how deep learning techniques can be effectively applied to medical datasets for high-accuracy classification. The results demonstrate the power of ANNs in detecting complex, non-linear relationships among diagnostic features.
