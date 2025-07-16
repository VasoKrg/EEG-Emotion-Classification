# EEG-Emotion-Classification

This project explores emotion recognition using EEG (electroencephalogram) signals, applying deep learning models to classify emotional states based on brainwave data. It was developed as part of my diploma thesis at the University of Patras.

## Objective

To build and evaluate machine learning models capable of classifying human emotions from EEG signals, contributing to real-world applications in neurotechnology, affective computing, and mental health monitoring.

## Dataset

- Models trained and evaluated with the public DEAP dataset.

## Technologies Used

- Python
- NumPy
- PyTorch + PyTorch Lightning
- TensorFlow
- Weights & Biases (wandb)
- Scikit-learn
- Matplotlib 

## Models Implemented

- **LSTM (Long Short-Term Memory)**
- **CNN (Convolutional Neural Network)**
- **Transformer-based models**

Each model was trained and evaluated using k-fold cross-validation. 

## Model Training & Experiment Tracking

Model training was managed using **PyTorch Lightning**, allowing for modular and scalable training loops.  
Experiments were logged and tracked with **Weights & Biases (wandb)**, including:

- Live loss and metric plots
- Model versioning
- Hyperparameter tuning
- Experiment comparison dashboard

## Full Thesis Document

A detailed explanation of methodology, experiments, and analysis is available in the full thesis (Greek Language only):

📎 [Download Thesis (PDF)](./KARAGIANNIDI_Thesis.pdf)
