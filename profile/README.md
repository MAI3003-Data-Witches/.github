# Data Witches - MAI3003 Medical AI Projects

Welcome to the **Data Witches** organization! We are a team of students working on Applying AI in Healthcare (MAI3003) projects at Maastricht University. Our work focuses on applying machine learning and AI techniques to healthcare challenges.

## 👥 Team Members

| Name | 
|------|
| Claessen, VVHJAE | 
| Ovsiannikova, AM | 
| Pubben, J | 
| Roca Cugat, M | 
| Záboj, J | 

---

## 📚 Our Projects

### 1. 🩺 Hepatitis C Screening
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MAI3003-Data-Witches/Data-Witches_Project1/HEAD?urlpath=%2Fdoc%2Ftree%2FMAI3003_Data_Witches_Assignment_1.ipynb)
[![Google CoLab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MAI3003-Data-Witches/Data-Witches_Project1/blob/main/MAI3003_Data_Witches_Assignment_1.ipynb)

**Repository:** [HepatitisC-Screening](https://github.com/MAI3003-Data-Witches/HepatitisC-Screening)

Our first project focuses on developing a machine learning solution for Hepatitis C screening. The project involves data analysis and classification techniques to aid in early detection of Hepatitis C.

**Key Features:**
- Data preprocessing and exploratory data analysis
- Machine learning model development for screening
- Interactive notebooks available via Binder and Google Colab

---

### 2. ❤️ Atrial Fibrillation Detection
[![DOI](https://zenodo.org/badge/1096405821.svg)](https://doi.org/10.5281/zenodo.17732910)

**Repository:** [AtrialFibrillation-detection](https://github.com/MAI3003-Data-Witches/AtrialFibrillation-detection)

**Documentation:** [Project Documentation](https://mai3003-data-witches.github.io/AtrialFibrillation-detection)

Our second project implements an Atrial Fibrillation classification system using ECG (Electrocardiogram) data and machine learning techniques. The project analyzes heart rate variability (HRV) features extracted from ECG signals to distinguish between Normal Sinus Rhythm and Atrial Fibrillation.

**Key Features:**
- ECG signal processing using NeuroKit
- HRV feature extraction (72 features including time-domain metrics like SDNN, RMSSD, pNN50, and frequency-domain features)
- Comprehensive ML model comparison (57 unique models tested)
- Best model: Voting Classifier ensemble (F1=0.8627, Accuracy=0.9685, evaluated on 20% held-out test set with stratified split)

**Models Implemented:**
- Logistic Regression (5 variants)
- Random Forest (14 variants)
- K-Nearest Neighbors (15 variants)
- AdaBoost (10 variants)
- Gradient Boosting (2 variants)
- Multi-Layer Perceptron Neural Network
- Voting Classifier (ensemble)
- And more...

**Dataset:** PhysioNet 2017 Training Data

---

### 3. 🤖 Medical Chatbot
**Repository:** [MedicalChatbot](https://github.com/MAI3003-Data-Witches/MedicalChatbot)

Our third project develops a medical chatbot specifically designed to assist COPD and asthma patients. The chatbot helps patients understand their symptoms and provides support during episodes.

**Objective:**
- Help COPD and asthma patients discern which symptoms are worrying and could indicate an exacerbation
- Provide calming exercises during episodes/attacks
- Refer patients to helpful resources
- Deliver drug information including side effects, general use, and drug interactions

**Target Population:** COPD and asthma patients

**Key Design Principles:**
- Good communication
- Empathy
- Patient safety through guardrails

**Planned Features:**
- Custom system prompt for respiratory conditions
- Safety guardrails implementation
- Comprehensive model testing
- Model Reporting Card
- Potential voice input integration

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy, SciPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-learn, TensorFlow/Keras
- **Signal Processing:** NeuroKit2
- **Model Interpretability:** SHAP
- **Environment:** Jupyter Notebooks, Google Colab

---

## 📖 Course Information

These projects are part of the **MAI3003 - Applying AI in Healthcare** course at Maastricht University.

---

*© 2025 Data Witches Team - Maastricht University*
