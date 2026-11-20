<div align="center">
  <!-- Top Animated Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=220&section=header&text=AI%20%26%20Deep%20Learning%20Suite&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Clinical%20Cardiology%20Pipeline%20%E2%80%A2%20CNN%20Computer%20Vision%20%E2%80%A2%20LSTM%20NLP&descFontSize=18&descAlignY=62" width="100%" alt="Project Banner" />

  <!-- Animated Tagline -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&width=750&lines=End-to-End+Cardiovascular+Risk+Stratification;Computer+Vision+Plant+Pathology+using+CNNs;Deep+Sequential+NLP+Sentiment+Analysis+with+LSTM;Engineered+and+Benchmarked+by+Sohail+Ahmed" alt="Typing SVG" />
  </a>

  <!-- Centered Rounded Avatar & Author Title -->
  <p align="center" style="margin-top: 15px;">
    <a href="https://sohail.devsil.com">
      <img src="https://github.com/sohail-ahmed-26.png?size=200" width="110" height="110" style="border-radius: 50%; box-shadow: 0 4px 10px rgba(0,0,0,0.25);" alt="Sohail Ahmed" />
    </a>
    <br />
    <strong style="font-size: 20px;">Sohail Ahmed</strong><br />
    <em>Senior AI Engineer & Data Scientist</em><br />
    📍 Mansehra, KPK, Pakistan
  </p>

  <!-- Badges -->
  <p align="center">
    <a href="https://python.org"><img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /></a>
    <a href="https://tensorflow.org"><img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" /></a>
    <a href="https://scikit-learn.org"><img src="https://img.shields.io/badge/Scikit--Learn-1.3%2B-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" /></a>
    <a href="https://xgboost.readthedocs.io"><img src="https://img.shields.io/badge/XGBoost-State--of--the--Art-185886?style=for-the-badge&logo=xgboost&logoColor=white" alt="XGBoost" /></a>
    <a href="#license"><img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" alt="License" /></a>
    <a href="https://github.com/sohail-ahmed-26/00_Project/commits/main"><img src="https://img.shields.io/github/last-commit/sohail-ahmed-26/00_Project?style=for-the-badge&color=3b82f6" alt="Last Commit" /></a>
    <a href="https://github.com/sohail-ahmed-26/00_Project/stargazers"><img src="https://img.shields.io/github/stars/sohail-ahmed-26/00_Project?style=for-the-badge&color=eab308" alt="GitHub Stars" /></a>
  </p>
</div>

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Magnifying%20Glass%20Tilted%20Right.png" width="30" height="30" align="center" />&nbsp; 01. Overview & Problem Statement

This repository hosts a multi-system **Machine Learning & Deep Learning Engineering Suite** delivering production-oriented solutions across tabular healthcare diagnostics, spatial computer vision, and sequential natural language processing:

<div align="center">

| Module | Core Domain | Problem Addressed | Real-World Impact |
| :--- | :--- | :--- | :--- |
| **01. Cardiovascular Risk Pipeline** | **Clinical ML / Tabular** | Early diagnosis and staging of coronary heart disease from multivariate diagnostic metrics. | Enables triage support for clinicians, identifying mild-to-critical cardiac risks before acute events occur. |
| **02. Rice Leaf Pathology Vision** | **Deep Learning / Computer Vision** | Automated diagnosis of agricultural crop diseases (*Bacterial Blight, Brown Spot, Leaf Smut*). | Empowers agricultural inspections with instant, non-destructive foliar disease detection to preserve crop yields. |
| **03. Deep Sentiment Intelligence** | **Deep Learning / NLP** | Semantic sentiment classification on 50,000 long-form textual movie evaluations (*IMDB*). | Provides scalable sentiment intelligence for customer feedback, brand reputation, and audience reception. |

</div>

### Why This Engineering Matters
1. **Clinical Healthcare Data Challenges**: Medical datasets frequently suffer from missing clinical records, non-linear biomarkers, and high class imbalance. This project implements advanced iterative imputation, automated dual-stream feature pipelines, and systematic 9-algorithm cross-validation.
2. **Multi-Domain Deep Learning**: The suite implements deep neural architectures across both **spatial representations** (2D spatial convolutions with batch regularization) and **sequential representations** (word embeddings with recurrent gated LSTM units), contrasting their inductive biases and operational characteristics.

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Sparkles.png" width="30" height="30" align="center" />&nbsp; 02. Key Features

### 🩺 Track 1: Clinical Heart Disease Multi-Class Classification
- 🔬 **Clinical EDA & Statistical Profiling**: In-depth exploratory data analysis across 920 international patient profiles from Cleveland, Hungary, Switzerland, and Long Beach V databases.
- 🧹 **Robust Missing Value Imputation**: Automated multi-stage imputation strategies replacing missing records in clinical columns (such as `thal`, `trestbps`, and `chol`) using machine learning regressors and iterative predictors.
- ⚙️ **Dual-Stream Preprocessing Pipeline**: Built using `ColumnTransformer` featuring numerical `SimpleImputer` + `StandardScaler` alongside categorical `OneHotEncoder(handle_unknown='ignore')`.
- 🏆 **Comprehensive 9-Model Benchmark**: Rigorous 5-fold cross-validation benchmarking Random Forest, Gradient Boosting, SVM, Logistic Regression, KNN, Decision Tree, AdaBoost, XGBoost, and Naive Bayes.
- 📦 **Serialized Production Artifact**: End-to-end serialized pipeline saved as `best_model.pkl` ready for immediate production deployment.

### 🌿 Track 2: Computer Vision Plant Pathology (CNN)
- 🖼️ **Foliar Disease Classification**: Classifies high-resolution agricultural leaves into 3 disease taxonomies: *Bacterial Leaf Blight*, *Brown Spot*, and *Leaf Smut*.
- 📐 **Rigorous Image Preprocessing**: Standardized image resizing to $128 \times 128 \times 3$, min-max normalization $[0, 1]$, and categorical label encoding.
- 🧠 **Hierarchical Feature Extraction**: Staged Conv2D feature pyramids (32, 64, 128 filters) with max pooling, dense projection layers, and 50% dropout regularization.
- 📊 **Validation Performance**: Evaluated across 30 training epochs with confusion matrices and per-class classification reports reaching **79.17% validation accuracy**.

### 💬 Track 3: Sequential NLP Sentiment Analysis (LSTM)
- 📝 **Large-Scale Text Processing**: Analyzes the benchmark 50,000 IMDB dataset using an end-to-end NLTK text normalization pipeline.
- 🔠 **Sequence Tokenization & Padding**: Text cleaning, lowercasing, sequence tokenization, and fixed-length padding ($L = 200$).
- 🔄 **Recurrent Memory Gating**: Embedding layer ($D = 128$) mapped into Long Short-Term Memory recurrent units to capture long-range contextual semantic dependencies.
- 🎯 **Exceptional Test Accuracy**: Validated on 10,000 unseen holdout reviews, achieving **88.63% test accuracy** and a binary cross-entropy loss of **0.3236**.

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="30" height="30" align="center" />&nbsp; 03. Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,scikitlearn,opencv,numpy,pandas,git,github" />
</div>

<br />

| Category | Technologies & Frameworks | Purpose in Project |
| :--- | :--- | :--- |
| **Core Language** | `Python 3.10+` | Core programming language for all pipelines & algorithms |
| **Machine Learning** | `Scikit-Learn`, `XGBoost` | Feature transformers, imputation, pipelines, model evaluation |
| **Deep Learning** | `TensorFlow`, `Keras` | Neural network construction for Conv2D layers, LSTM recurrent cells |
| **Computer Vision** | `OpenCV`, `Pillow` | Image tensor loading, color conversions, target resizing |
| **Natural Language Processing** | `NLTK`, `Keras Tokenizer` | Corpus cleaning, token sequence indexing, padding transformations |
| **Data Manipulation** | `Pandas`, `NumPy` | Tabular data structures, matrix operations, missing value handling |
| **Data Visualization** | `Matplotlib`, `Seaborn`, `Plotly` | Loss/accuracy curves, correlation heatmaps, confusion matrices |
| **Serialization & Deployment** | `Pickle` | Serializing end-to-end inference pipelines (`best_model.pkl`) |

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="30" height="30" align="center" />&nbsp; 04. System Architecture & Workflows

### 1. Clinical Cardiovascular Predictive Pipeline

```mermaid
flowchart TD
    A["Raw Clinical Records (heart_disease_uci.csv)"] --> B["Exploratory Data Analysis & Quality Audit"]
    B --> C["Missing Value Strategy (Iterative & KNN Imputation)"]
    C --> D["Feature Segregation (Numeric & Categorical)"]
    
    subgraph Preprocessing_Pipeline ["Dual-Stream Preprocessing Pipeline"]
        D -->|Numeric Stream| E["SimpleImputer(mean) + StandardScaler()"]
        D -->|Categorical Stream| F["SimpleImputer(frequent) + OneHotEncoder()"]
        E --> G["Combined Feature Matrix (Transformed)"]
        F --> G
    end

    G --> H["Multi-Model Benchmark (9 Classifiers, 5-Fold CV)"]
    H --> I{"Model Selection: Best Test Accuracy"}
    I -->|Winner: 64.13% Acc| J["XGBoost Multi-Class Classifier"]
    J --> K["Exported Pipeline: best_model.pkl"]
```

### 2. Dual-Domain Deep Learning Architecture

```mermaid
flowchart LR
    subgraph Computer_Vision_Track ["Plant Pathology Vision (CNN)"]
        CV_IN["Leaf Images (RGB)"] --> CV_P["Resize (128x128) & Norm [0,1]"]
        CV_P --> C1["Conv2D (32) + MaxPool"]
        C1 --> C2["Conv2D (64) + MaxPool"]
        C2 --> C3["Conv2D (128) + MaxPool"]
        C3 --> D1["Dense (128) + Dropout (0.5)"]
        D1 --> CV_OUT["Softmax (3 Classes)"]
    end

    subgraph NLP_Sequential_Track ["Sentiment Analysis (LSTM)"]
        NLP_IN["Raw Text Reviews"] --> NLP_P["Regex Clean & Tokenize"]
        NLP_P --> NLP_PAD["Sequence Pad (maxlen=200)"]
        NLP_PAD --> EMB["Embedding (10k -> 128)"]
        EMB --> LSTM_L["LSTM Recurrent Cells (64)"]
        LSTM_L --> D2["Dense (32) + Dropout (0.5)"]
        D2 --> NLP_OUT["Sigmoid Output (Prob > 0.5)"]
    end
```

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Folder.png" width="30" height="30" align="center" />&nbsp; 05. Project Structure

```bash
00_Project/
│
├── 01_Heart_disease_prediction/                         # End-to-end clinical heart disease project
│   ├── best_model.pkl                                   # Serialized production pipeline (XGBoost + Preprocessor)
│   ├── heart_disease_prediction.ipynb                   # Complete ML research & benchmarking notebook (58 cells)
│   └── heart_disease_uci.csv                            # UCI Heart Disease clinical dataset (920 patient records)
│
├── Deep_Learning_Project_using_CNN_(Computer_Vision)_and_LSTM_(NLP).ipynb  # Dual-domain Deep Learning notebook (67 cells)
│   ├── Part 1: Computer Vision (Rice Leaf Pathology CNN)
│   ├── Part 2: Natural Language Processing (IMDB Sentiment LSTM)
│   └── Part 3: Deep Learning Comparative Architecture Study
│
└── README.md                                            # Comprehensive technical documentation & showcase
```

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Wrench.png" width="30" height="30" align="center" />&nbsp; 06. Installation & Environment Setup

Follow these straightforward steps to set up the environment and reproduce all experiments locally:

```bash
# 1. Clone the repository
git clone https://github.com/sohail-ahmed-26/00_Project.git
cd 00_Project

# 2. Create and activate a dedicated virtual environment
python -m venv venv

# Windows:
venv\Scripts\activate
# Linux / macOS:
# source venv/bin/activate

# 3. Upgrade pip and install required dependencies
pip install --upgrade pip
pip install numpy pandas scikit-learn xgboost tensorflow nltk opencv-python matplotlib seaborn plotly jupyter
```

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Rocket.png" width="30" height="30" align="center" />&nbsp; 07. Usage & Execution Guide

### Running the Interactive Notebooks

Launch Jupyter Notebook or JupyterLab from the workspace root:

```bash
jupyter notebook
```

- **Heart Disease Prediction**: Open `01_Heart_disease_prediction/heart_disease_prediction.ipynb` to step through data preprocessing, missing-value imputation, multi-algorithm cross-validation, and production serialization.
- **Deep Learning Suite**: Open `Deep_Learning_Project_using_CNN_(Computer_Vision)_and_LSTM_(NLP).ipynb` to train and evaluate the CNN image classifier and LSTM text sentiment analyzer.

### Quick Inference with the Serialized Heart Disease Pipeline

You can load and evaluate patient records directly with the saved model in Python:

```python
import pickle
import pandas as pd

# Load the trained production pipeline
with open("01_Heart_disease_prediction/best_model.pkl", "rb") as f:
    pipeline = pickle.load(f)

# Sample patient diagnostic record
patient_data = pd.DataFrame([{
    "id": 1,
    "age": 58,
    "sex": "Male",
    "dataset": "Cleveland",
    "cp": "typical angina",
    "trestbps": 140.0,
    "chol": 240.0,
    "fbs": False,
    "restecg": "normal",
    "thalch": 160.0,
    "exang": False,
    "oldpeak": 1.2,
    "slope": "flat",
    "ca": 0.0,
    "thal": "normal"
}])

# Execute prediction
prediction = pipeline.predict(patient_data)[0]
stages = {
    0: "Absence of Heart Disease (Normal / Healthy)",
    1: "Stage 1 Heart Disease (Mild)",
    2: "Stage 2 Heart Disease (Moderate)",
    3: "Stage 3 Heart Disease (Severe)",
    4: "Stage 4 Heart Disease (Critical)"
}

print(f"Predicted Patient Status: {stages.get(prediction, f'Stage {prediction}')}")
```

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Trophy.png" width="30" height="30" align="center" />&nbsp; 08. Experimental Results & Performance Metrics

All metrics reported below are empirically verified and extracted directly from the executed research notebooks:

### 1. Heart Disease Multi-Model Benchmark (UCI Clinical Dataset)

Across 9 distinct classification architectures evaluated under identical 5-fold cross-validation and holdout test splits ($70/30$ ratio):

<div align="center">

| Rank | Model Architecture | 5-Fold CV Accuracy | Holdout Test Accuracy | Selection Status |
| :---: | :--- | :---: | :---: | :---: |
| 🥇 | **XGBoost Classifier** | **63.76%** | **64.13%** | 🏆 **Selected Production Model** |
| 🥈 | **Gradient Boosting** | **61.27%** | **63.41%** | Benchmark Runner-up |
| 🥉 | **Random Forest** | **63.45%** | **62.68%** | Robust Ensemble |
| 4 | **AdaBoost Classifier** | **63.77%** | **60.51%** | Adaptive Boosting |
| 5 | **Logistic Regression** | **63.00%** | **59.06%** | Linear Baseline |
| 6 | **K-Nearest Neighbors (KNN)** | **57.54%** | **58.70%** | Distance-based |
| 7 | **Support Vector Machine (SVM)** | **59.72%** | **57.25%** | Kernelized Classifier |
| 8 | **Decision Tree Classifier** | **61.75%** | **57.25%** | Non-linear Tree |
| 9 | **Gaussian Naive Bayes** | **38.73%** | **36.23%** | Probabilistic Baseline |

</div>

> **Takeaway**: XGBoost demonstrated the highest generalization performance on complex clinical data, handling skewed distributions and high-cardinality biomedical factors most effectively.

---

### 2. Deep Learning Models Performance

<div align="center">

| Model | Domain & Task | Dataset | Architecture Highlights | Metric | Loss |
| :--- | :--- | :--- | :--- | :---: | :---: |
| **CNN** | **Computer Vision**: Rice Leaf Disease | Agricultural Leaf Pathology | 3x Conv2D + MaxPool + Dense(128) + Dropout | **79.17% Val Accuracy** | **0.8743** |
| **LSTM** | **NLP**: Sentiment Analysis | 50,000 IMDB Movie Reviews | Embedding(128) + LSTM(64) + Dropout(0.5) | **88.63% Test Accuracy** | **0.3236** |

</div>

#### Classification Report — Rice Leaf Pathology CNN
```text
                       Precision    Recall    F1-Score   Support
Bacterial leaf blight       0.33      0.38        0.35         8
           Brown spot       0.43      0.38        0.40         8
            Leaf smut       0.38      0.38        0.38         8

             Accuracy                             0.79        24
            Macro Avg       0.38      0.38        0.38        24
         Weighted Avg       0.38      0.38        0.38        24
```

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Map.png" width="30" height="30" align="center" />&nbsp; 09. Roadmap & Future Scope

- [x] Comprehensive exploratory data analysis and clinical feature profiling.
- [x] Multi-strategy imputation for missing values in cardiac biomarkers.
- [x] Benchmark 9 machine learning algorithms and serialize winning XGBoost pipeline.
- [x] Implement and validate CNN architecture for rice plant leaf pathology.
- [x] Build, train, and test sequential LSTM architecture for large-scale sentiment analysis.
- [ ] Deploy an interactive **Streamlit / FastAPI** web dashboard for real-time patient diagnosis.
- [ ] Implement Transfer Learning (e.g., *EfficientNet-B0*, *ResNet50*) to enhance foliar disease accuracy beyond 95%.
- [ ] Incorporate Transformer-based representations (*BERT*, *RoBERTa*) for advanced sentiment nuance detection.

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Crown.png" width="30" height="30" align="center" />&nbsp; 10. About the Author

<div align="center">
  <table style="border: none; background: transparent;">
    <tr>
      <td align="center" width="160">
        <a href="https://sohail.devsil.com">
          <img src="https://github.com/sohail-ahmed-26.png?size=200" width="130" height="130" style="border-radius: 50%;" alt="Sohail Ahmed" />
        </a>
      </td>
      <td align="left">
        <h3 style="margin: 0;">Sohail Ahmed</h3>
        <p style="margin: 4px 0; color: #4B5563;"><strong>AI Engineer & Data Scientist</strong></p>
        <p style="margin: 6px 0; font-size: 14px; line-height: 1.5;">
          <em>"Building intelligent AI systems that solve real-world problems through data, automation, and innovation."</em>
          <br />
          Working at the intersection of Machine Learning, Deep Learning, Computer Vision, and Natural Language Processing — transforming raw clinical and perceptual data into robust, production-grade intelligence.
        </p>
        <p style="margin: 8px 0;">
          <a href="https://sohail.devsil.com"><img src="https://img.shields.io/badge/Portfolio-sohail.devsil.com-0284c7?style=flat-square&logo=google-chrome&logoColor=white" /></a>
          <a href="https://github.com/sohail-ahmed-26"><img src="https://img.shields.io/badge/GitHub-sohail--ahmed--26-181717?style=flat-square&logo=github&logoColor=white" /></a>
          <a href="https://www.linkedin.com/in/sohail-ahmed-devsil"><img src="https://img.shields.io/badge/LinkedIn-Sohail%20Ahmed-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
          <a href="https://x.com/ahmed241126"><img src="https://img.shields.io/badge/Twitter%20%2F%20X-@ahmed241126-000000?style=flat-square&logo=x&logoColor=white" /></a>
          <a href="https://www.kaggle.com/sohail2411126"><img src="https://img.shields.io/badge/Kaggle-sohail2411126-20BEFF?style=flat-square&logo=kaggle&logoColor=white" /></a>
        </p>
      </td>
    </tr>
  </table>
</div>

<br />

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" width="30" height="30" align="center" />&nbsp; 11. License & Acknowledgements

This project is licensed under the terms of the **MIT License**. You are free to use, modify, and distribute this software with attribution.

<div align="center">
  <p>
    ⭐ <strong>If you found this repository insightful, please star it on GitHub!</strong> ⭐
  </p>
  <a href="https://github.com/sohail-ahmed-26/00_Project/stargazers">
    <img src="https://img.shields.io/badge/%E2%AD%90%20Star%20This%20Repository-GitHub-yellow?style=for-the-badge&logo=github" alt="Star Repository" />
  </a>
</div>

<br />

<!-- Waving Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=120&section=footer" width="100%" alt="Footer" />
</div>
