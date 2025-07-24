# 🌿 Smart Irrigation Using Sensor Data

### 📅 Week 1 & Week 2 Progress Report

**Internship Program:** AI/ML Internship – *Edunet Foundation*
* **Project Title:** Smart Irrigation Automation Using Machine Learning
* **Duration:** Week 1 & Week 2
* **Platform Used:** Google Colab

## 🔍 Problem Statement

Modern irrigation systems benefit significantly from intelligent automation. This project focuses on developing a machine learning model capable of predicting the irrigation requirements of different land parcels using sensor data. The goal is to optimize water consumption and ensure efficient farming practices.

## 📊 Dataset Overview

* **File Name:** `irrigation_machine.csv`
* **Total Records:** 2,000 entries
* **Features:**

  * `sensor_0` to `sensor_19` — Sensor readings from devices monitoring environmental and soil conditions.
* **Labels/Targets:**

  * `parcel_0`, `parcel_1`, `parcel_2` — Binary indicators (0 or 1) representing whether each of the three parcels needs irrigation.


## ✅ Tasks Completed

### 📅 Week 1: Data Exploration & Preprocessing

* ✔️ Imported necessary Python libraries:

  * `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`
* ✔️ Loaded the dataset and removed unnecessary column:

  * Dropped column: `Unnamed: 0`
* ✔️ Verified data integrity:

  * Checked data types
  * Confirmed no missing values
* ✔️ Generated statistical summaries using `.describe()`
* ✔️ Split the dataset:

  * **Features (X):** All 20 sensor columns
  * **Labels (y):** The 3 parcel columns
* ✔️ Verified dataset dimensions and feature-label alignment


### 📅 Week 2: Modeling Preparation

* ✔️ Imported models and preprocessing tools:

  * `RandomForestClassifier` for classification
  * `MultiOutputClassifier` to handle multiple target variables
  * `train_test_split` and `MinMaxScaler` from `sklearn`
  * Scale feature values using `MinMaxScaler`
  * Split the dataset into training and test sets
  * Train `RandomForestClassifier` using `MultiOutputClassifier`
  * Evaluate model accuracy using appropriate metrics (accuracy, F1-score, confusion matrix)
  * Visualize feature importance and model performance


## 🧠 Tools & Libraries Used

* **Languages & Environments:** Python, Google Colab
* **Libraries:**

  * **Data Handling:** `pandas`, `numpy`
  * **Visualization:** `matplotlib`, `seaborn`
  * **Machine Learning:** `scikit-learn` (Random Forest, MultiOutputClassifier, scaling, train/test split)
