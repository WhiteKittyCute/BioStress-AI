# BioStress AI
## AI-Based Physiological Stress Analysis using HRV Data

### Author
Valeria Martinez Ramirez

---

# Project Overview

BioStress AI is a biomedical data analysis project focused on identifying physiological patterns associated with cognitive stress using Heart Rate Variability (HRV) metrics and Machine Learning techniques.

The project explores how different stress conditions affect autonomic nervous system behavior and evaluates the potential of AI-based models for physiological state classification.

---

# Objectives

- Analyze HRV metrics under different cognitive stress conditions
- Identify physiological patterns associated with stress
- Apply Exploratory Data Analysis (EDA) techniques
- Develop a Machine Learning model for stress classification
- Interpret biomedical signal behavior using AI methods

---

# Dataset

This project uses the SWELL HRV Dataset, which contains physiological measurements collected under multiple cognitive stress conditions:

- No Stress
- Interruption
- Time Pressure

The dataset includes several HRV-related metrics such as:

- Heart Rate (HR)
- RMSSD
- SDRR
- LF/HF Ratio
- pNN50
- Total Power (TP)

Dataset source:
https://www.kaggle.com/datasets/qiriro/swell-heart-rate-variability-hrv

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Exploratory Data Analysis

The project includes:

- Statistical analysis of HRV metrics
- Boxplots and violin plots
- Correlation heatmaps
- Logarithmic transformations for skewed physiological data
- Physiological interpretation of stress responses

---

# Machine Learning

A Random Forest classifier was implemented to classify physiological stress conditions based on HRV metrics.

The model achieved extremely high classification performance, suggesting strong physiological separability between stress conditions.

Feature importance analysis identified:

1. Heart Rate (HR)
2. RMSSD
3. SDRR

as the most relevant variables for stress classification.

---

# Key Findings

- Time pressure conditions showed higher LF/HF ratios and increased physiological variability.
- HRV metrics demonstrated meaningful physiological correlations.
- Machine Learning models can effectively classify cognitive stress conditions using biomedical data.

---

# Future Work

Potential future improvements include:

- Real-time stress monitoring systems
- Integration with wearable devices
- Advanced AI and Deep Learning models
- Smart healthcare applications
- Neurological disorder analysis using physiological signals

---

# Biomedical Relevance

This project demonstrates the potential of combining biomedical engineering, physiological signal analysis, and Artificial Intelligence for intelligent healthcare applications.

---

# Project Status

Completed – Version 1.0
