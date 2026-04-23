# ⚡ Electric Motor Condition Analysis with Machine Learning

## 📌 Overview
This project focuses on analyzing sensor data from a Permanent Magnet Synchronous Motor (PMSM) to understand its operational conditions using machine learning techniques.

The dataset contains multiple measurements such as current, voltage, temperature, speed, and torque collected from different sessions. These features are used to discover hidden patterns and build predictive models for motor condition monitoring.

---

## 📊 Dataset
- Source: Kaggle  
- Dataset: Electric Motor Temperature  
- Link: https://www.kaggle.com/datasets/wkirgsn/electric-motor-temperature  

---

## 🎯 Objectives
- Cluster motor data based on similarity using **K-Means**
- Define cluster labels from unsupervised learning results
- Build classification models to predict cluster labels:
  - Decision Tree
  - Random Forest (Bagging Ensemble)
- Compare model performance between Decision Tree and Random Forest

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Data cleaning
- Feature selection
- etc

### 2. Clustering (Unsupervised Learning)
- Algorithm: **K-Means**
- Goal: Group data into clusters based on similar characteristics

### 3. Labeling
- Assign cluster results as labels for supervised learning

### 4. Classification (Supervised Learning)
Models implemented **from scratch**:
- Decision Tree
- Random Forest (ensemble of multiple decision trees)

### 5. Evaluation
- Accuracy comparison between models
- Analysis of model performance

### 6. Graphical User Interface 
Simple tkinter gui for user to use the trained model

---

## 🧠 Key Features
- Full implementation **from scratch**
- No use of high-level ML libraries (e.g., scikit-learn)
- Combination of:
  - Unsupervised Learning (Clustering)
  - Supervised Learning (Classification)
- Focus on real-world industrial data

---

## 📈 Results
- K-Means successfully grouped the motor sensor data into **3 clusters**: Light, Medium, and Heavy operating conditions.
- Undersampling did not significantly improve performance, indicating the dataset was relatively balanced (**60:40**).
- **Random Forest** outperformed **Decision Tree** with better accuracy, precision, and recall.
- The combination of clustering and classification proved effective for predicting motor operating conditions.
- **Random Forest** was the best-performing model for this project.

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🚀 How to Run

# Clone repository
git clone https://github.com/wahyuayesha/Electric-Motor

# Open notebook
jupyter notebook
