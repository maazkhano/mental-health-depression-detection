# 🧠 Mental Health Depression Detection using Machine Learning

This project demonstrates a machine learning-based approach to detect symptoms of **depression** based on five key mental health indicators: Mood, Energy, Sleep, Appetite, and Sadness.

---

## 📂 Project Contents

- **Dataset**: A custom-made dataset containing observations on mental health status.
- **Notebook**: A complete Jupyter notebook with preprocessing, modeling, evaluation, and conclusions.
- **Predictive System**: A basic input-based predictive function is implemented.
- **Evaluation**: Accuracy score and classification report included.

---

## 🔍 Features

- Binary and multi-class classification based on manually labeled data
- Clean and readable code for beginners
- Accuracy reaches up to ~90% with RandomForestClassifier
- Simple textual input predictive system

---

## 🧠 Dataset Overview

Each row in the dataset includes the following columns:

- `Mood`: (low, normal, high)
- `Energy`: (low, moderate, high)
- `Sleep`: (poor, normal, excessive)
- `Appetite`: (low, normal, high)
- `Sadness`: (low, moderate, high)
- `Depression`: Final classification status (Depressed vs Not Depressed)

---

## 🧪 Model Used

- Random Forest Classifier
- Train-test split with 80/20
- Evaluation: Accuracy score and classification report

---

## 📈 Results

Achieved up to **90% accuracy** on a clean and small-scale dataset, which is manually structured for conceptual clarity.

---

## ✅ Requirements

Install packages using:

```bash
pip install -r requirements.txt
