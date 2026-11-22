# Deep Learning Intelligence Suite - Clinical Prediction & Hybrid CNN-LSTM

<p align="center">
  <a href="https://sohail.devsil.com"><strong>Portfolio</strong></a> | 
  <a href="https://github.com/sohailahmed-bsrh"><strong>GitHub Profile</strong></a> | 
  <a href="https://github.com/sohailahmed-bsrh/deep-learning-cnn-lstm"><strong>Source Repository</strong></a>
</p>

---

## Executive Summary & Problem Statement

Modern artificial intelligence systems must solve both tabular clinical diagnostic problems and complex spatial-temporal sequence challenges. Clinical healthcare practitioners need predictive risk scoring from physiological biomarkers (such as the Cleveland Heart Disease registry), while advanced automation systems require neural architectures that extract spatial visual features and track long-term sequential dependencies.

This repository provides an integrated **Dual-Module Deep Learning Suite**:
1. **Module 1 - Clinical Cardiovascular Risk Predictor**: Machine learning pipeline for non-invasive heart disease classification (`01_Heart_disease_prediction/`).
2. **Module 2 - Hybrid CNN-LSTM Neural Network**: End-to-end spatial-temporal deep learning architecture combining Convolutional Neural Networks with Recurrent LSTM units (`notebooks/`).

<div align="center">
  <img src="https://raw.githubusercontent.com/sohailahmed-bsrh/myportfolio/main/assets/images/thumbnail/heart-disease-prediction.jpeg" width="650" alt="Deep Learning Intelligence Suite"/>
  <p><em>Clinical diagnostic classification coupled with spatial-temporal CNN-LSTM neural architectures.</em></p>
</div>

---

## Real-World Industry Applications

- **Cardiovascular Clinical Decision Support**: Flags early cardiovascular disease risk from patient clinical markers (cholesterol, resting ECG, blood pressure).
- **Medical Imaging & Video Analysis**: Analyzes echocardiograms and angiography sequences where spatial image features evolve temporally.
- **Biometric Sequence Tracking**: Processes sequential multi-lead ECG signals to identify cardiac arrhythmias.
- **Serialized Model Serving**: Deploys calibrated pickled model pipelines (`best_model.pkl`) into clinical production environments.

---

## Technical Architecture & Engineering Walkthrough

```
                      ┌────────────────────────────────────────┐
                      │    Deep Learning Intelligence Suite    │
                      └───────────────────┬────────────────────┘
                                          │
         ┌────────────────────────────────┴────────────────────────────────┐
         ▼                                                                 ▼
[Module 1: Clinical Heart Disease]                        [Module 2: Hybrid CNN-LSTM Architecture]
(Tabular Biomarker Pipeline)                              (Spatial-Temporal Neural Pipeline)
         │                                                                 │
         ▼                                                                 ▼
[Data Cleaning & Biomarker Scaling]                       [Input Tensor Sequence (Batch, Time, Spatial)]
(Resting BP, Cholesterol, Thalassemia)                                     │
         │                                                                 ▼
         ▼                                                [TimeDistributed Conv2D/Conv1D Spatial Extraction]
[Model Selection & Hyperparameter Tuning]                                   │
(Logistic, Random Forest, SVM, XGBoost)                                    ▼
         │                                                [Stacked LSTM Recurrent Temporal Memory]
         ▼                                                                 │
[Model Serialization: best_model.pkl]                                      ▼
                                                          [Dense Classification & Cross-Entropy Loss]
```

### Module 1: Cardiovascular Disease Predictive Pipeline
- **Dataset**: Cleveland Heart Disease registry (`heart_disease_uci.csv`) encompassing 14 clinical attributes including resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, and exercise-induced angina.
- **Preprocessing**: Handles missing values, performs one-hot encoding on categorical biomarkers, and applies `StandardScaler` to physiological features.
- **Evaluation**: Benchmarks multiple classifiers, selecting the optimal model based on ROC-AUC, Precision, and Recall. Serializes the champion estimator to `best_model.pkl`.

### Module 2: Hybrid CNN-LSTM Spatial-Temporal Network
- **Spatial Feature Representation**: Employs `TimeDistributed` convolutional layers to extract spatial representations from sequential frame matrices without weight drift across time steps.
- **Temporal Sequence Modeling**: Passes convolutional feature embeddings into stacked Long Short-Term Memory (LSTM) cells to capture long-range temporal dependencies.
- **Regularization**: Integrates Spatial Dropout, Recurrent Dropout, and Batch Normalization to prevent overfitting and guarantee convergence stability.

---

## Technology Stack & Implementation Specifications

| Component | Technology | Version | Architectural Function |
| :--- | :--- | :--- | :--- |
| **Deep Learning** | TensorFlow / Keras | 2.15+ | Hybrid CNN-LSTM architecture and TimeDistributed layers |
| **Machine Learning** | Scikit-Learn | 1.3+ | Clinical classification pipelines, metric validation, pickle |
| **Data Engine** | Pandas / NumPy | 2.x | Physiological data cleaning, matrix transformations |
| **Visualization** | Seaborn / Matplotlib | 3.8+ | ROC curves, confusion matrices, neural loss curves |

---

## Installation & Execution Guide

### 1. Clinical Heart Disease Module
```bash
cd 01_Heart_disease_prediction
python -m venv venv
# Windows: venv\Scriptsctivate | Unix: source venv/bin/activate
pip install -r ../requirements.txt
jupyter notebook heart_disease_prediction.ipynb
```

### 2. Hybrid CNN-LSTM Neural Network
```bash
# In repository root:
jupyter notebook "notebooks/Deep_Learning_Project_using_CNN_(Computer_Vision)_and_LSTM_(NLP).ipynb"
```

---

## Author & Contact Information

<table width="100%">
  <tr>
    <td width="150" align="center" valign="middle">
      <img src="https://avatars.githubusercontent.com/u/231165170?v=4" width="120" style="border-radius: 50%;" alt="Sohail Ahmed"/>
    </td>
    <td>
      <h3>Sohail Ahmed</h3>
      <p><strong>Senior Software Engineer & AI Systems Architect</strong></p>
      <p>Specializing in Full-Stack AI Application Development, Computer Vision, Deep Learning Pipelines, and Scalable Automation Architectures.</p>
      <p>
        <a href="https://sohail.devsil.com"><strong>Portfolio Website</strong></a> | 
        <a href="https://github.com/sohailahmed-bsrh"><strong>GitHub Profile</strong></a> | 
        <a href="https://www.linkedin.com/in/sohail-ahmed-546314316/"><strong>LinkedIn</strong></a> | 
        <a href="mailto:se906403@gmail.com"><strong>Email Contact</strong></a>
      </p>
    </td>
  </tr>
</table>
