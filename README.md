# ANFIS-Based Liver Disease Prediction Using Fuzzy Inference System

## Overview

This project implements **Fuzzy Inference System (FIS)** and **Adaptive Neuro-Fuzzy Inference System (ANFIS)** to predict liver disease using the **Indian Liver Patient Dataset (ILPD)**.

The goal of this project is to demonstrate how **fuzzy logic and neural learning can be combined** to build interpretable medical decision systems.

Two models are implemented:

• Rule-based **Fuzzy Inference System (FIS)**
• Data-driven **Adaptive Neuro-Fuzzy Inference System (ANFIS)**

Their performance is evaluated and compared on a medical dataset.

---

## Dataset

The project uses the **Indian Liver Patient Dataset (ILPD)** from the UCI Machine Learning Repository.

Features include:

* Age
* Gender
* Total Bilirubin
* Direct Bilirubin
* Alkaline Phosphatase
* Albumin
* Albumin and Globulin Ratio

Target variable:

```
1 → Liver Disease
0 → Normal
```

---

## Project Workflow

1. Data preprocessing and normalization
2. Feature selection
3. Fuzzy membership function design
4. Rule-based FIS implementation
5. ANFIS model training
6. Performance comparison

---

## Fuzzy Inference System (FIS)

The FIS model uses **expert-defined rules** with triangular membership functions.

### Key Components

* Linguistic variables
* Membership functions
* Rule base
* Mamdani inference
* Defuzzification

### FIS Architecture

![FIS Architecture]
<img width="1220" height="542" alt="image" src="https://github.com/user-attachments/assets/022bec6b-5ede-4c74-8ef0-68bb328028be" />


---

## ANFIS Architecture

The ANFIS model combines neural networks with fuzzy logic.

### Five-Layer Structure

Layer 1 – Fuzzification
Layer 2 – Rule Layer
Layer 3 – Normalization
Layer 4 – Consequent Layer
Layer 5 – Output Layer

![ANFIS Architecture]<img width="1220" height="542" alt="image" src="https://github.com/user-attachments/assets/c4e59d9e-87a4-463c-8cda-16a267946ab2" />


![ANFIS Network Architecture](<img width="1105" height="541" alt="image" src="https://github.com/user-attachments/assets/80473b07-eeca-47b4-bd63-0957ddf3e78b" />

)
---

## Results

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC Curve
---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Scikit-Fuzzy
* Matplotlib
* Seaborn

---

## Key Insight

The **ANFIS model outperforms the traditional rule-based FIS** because it can automatically learn optimal parameters from data while preserving fuzzy interpretability.

---

## How to Run

Clone the repository

```
git clone https://github.com/fatimasood/anfis-liver-disease-prediction.git
```

Install dependencies

```
pip install -r requirements.txt
```
Run the notebook

```
jupyter notebook notebooks/liver_disease_fis_anfis.ipynb
```

Note: The objective of this project was learning Fuzzy Inference System (FIS) and an AdaptiveNeuro-Fuzzy Inference System (ANFIS) not to acheive high accuracy....

