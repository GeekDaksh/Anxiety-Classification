# 🧠 EEG-Based Anxiety Classification

This project investigates the use of machine learning techniques to classify anxiety levels using features extracted from EEG signals. EEG recordings from 23 participants were analyzed and labeled into two categories: **Normal** and **Ansiedade Severa**.

---

## 📌 Overview

Anxiety disorders are complex and often difficult to assess objectively. This project explores how EEG-derived features can be leveraged with machine learning models to automatically classify anxiety severity, offering insights into computational mental health analysis.

---

## 📊 Dataset

- **Participants:** 23  
- **Labels:** Normal, Ansiedade Severa  
- **Data Type:** EEG recordings  

---

## 🧪 Feature Extraction

The following statistical and frequency-domain features were extracted from EEG signals:

- Mean  
- Median  
- Standard Deviation  
- Variance  
- Signal Energy  
- Power Spectral Density (PSD)  

---

## 🤖 Models Implemented

- **Random Forest Classifier**  
- **Multi-Layer Perceptron (MLP)**  

To address class imbalance, **SMOTE (Synthetic Minority Over-sampling Technique)** was applied before model training.

---

## 📈 Results

- **Random Forest Accuracy:** 96.5%  
- **MLP Accuracy:** 95.5%  

The Random Forest model achieved the best overall performance.

---

## 📁 Project Files

- `Anxiety_Classification.ipynb` — Complete implementation, experiments, and results  

---

## 🎯 Applications

- Anxiety level assessment  
- EEG-based mental health analysis  
- Brain–computer interface research  
- Machine learning in healthcare  

---

## ⚠️ Disclaimer

This project is intended for academic and research purposes only and should not be used for clinical diagnosis or treatment.
