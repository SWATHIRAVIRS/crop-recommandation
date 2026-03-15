# crop-recommandation
# 🌱 Crop Recommendation System using Machine Learning

## 📌 Project Overview

The **Crop Recommendation System** is a machine learning project that helps farmers choose the **most suitable crop to grow based on soil and environmental conditions**.

By analyzing factors such as **soil nutrients, temperature, humidity, pH level, and rainfall**, the model predicts the best crop that can be cultivated for higher productivity.

This system can support farmers in making **data-driven agricultural decisions**.

---

## 🎯 Problem Statement

Farmers often face difficulty in deciding which crop to grow due to changing environmental conditions and soil properties.

The goal of this project is to **build a machine learning model that recommends the best crop based on soil nutrients and climate conditions.**

---

## 📊 Dataset

The dataset contains agricultural information used to recommend crops.

### Features in the Dataset

| Feature     | Description                   |
| ----------- | ----------------------------- |
| N           | Nitrogen content in soil      |
| P           | Phosphorus content in soil    |
| K           | Potassium content in soil     |
| Temperature | Temperature in degree Celsius |
| Humidity    | Relative humidity             |
| pH          | Soil pH value                 |
| Rainfall    | Rainfall in mm                |

### Target Variable

| Column | Description                 |
| ------ | --------------------------- |
| Label  | Crop name to be recommended |

Example crops in the dataset:

* Rice
* Wheat
* Maize
* Cotton
* Mango
* Banana
* Coffee

---

## ⚙️ Technologies Used

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading

The dataset is loaded using **pandas**.

### 2️⃣ Data Exploration

* Checking dataset structure
* Understanding feature distributions
* Visualizing relationships between variables

### 3️⃣ Data Preprocessing

* Feature selection
* Data scaling (if required)
* Splitting dataset into training and testing data

### 4️⃣ Model Training

Machine learning algorithms are used to train the crop prediction model.

Example models:

* KNearestNeighbours
### 5️⃣ Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📈 Model Performance

The trained model can accurately recommend crops based on environmental conditions.

Example output:

Input:

```
Nitrogen = 90
Phosphorus = 42
Potassium = 43
Temperature = 21°C
Humidity = 82%
pH = 6.5
Rainfall = 202 mm
```

Output:

```
Recommended Crop: Rice
```

---

## 📂 Project Structure

```
Crop-Recommendation-System
│
├── crop_recommendation.ipynb
├── crop_data.csv
└── README.md
```

---

## 🚀 Future Improvements

* Deploy the model using **Streamlit**
* Build a **web application for farmers**
* Integrate **real-time weather data**
* Improve model accuracy using ensemble methods

---

## 👩‍💻 Author

Swathi Ravi
Artificial Intelligence & Machine Learning Student
