# Data-Conscientiousness-MSDS-515-2-2025-Class---Project-2-Missing-Data-Visualization-and-Imputation

# 📊 Project 2: Missing Data Visualization and Imputation

## 🧾 Course Information

**Course:** Data Conscientiousness (MSDS 515)
**Project:** Project 2 – Missing Data Visualization and Imputation

---

## 👨‍🎓 Student Information

**Name:** *Opeyemi Omotosho*
**Institution:** *Meharry Medical College*

---

## 📌 Project Overview

Missing data is a common challenge in real-world datasets and can significantly impact data analysis and model performance if not handled properly.

This project focuses on:

* Identifying missing data patterns
* Visualizing missingness
* Applying multiple imputation techniques
* Evaluating imputation accuracy using a ground truth dataset

Two datasets were used:

* `Insertion_Depth_Dataset_missing_values.csv` → Dataset containing missing values
* `Insertion_Depth_Dataset.csv` → Complete dataset used as ground truth

---

## 🎯 Objectives

The primary objectives of this project are:

* Analyze missing data patterns in a real-world dataset
* Apply different imputation techniques
* Compare imputation results visually and quantitatively
* Evaluate accuracy using Mean Absolute Error (MAE)
* Identify the most effective imputation method

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Missingno
* Scikit-learn

---

## 🔍 Methodology

### 1. Data Loading

* Loaded both datasets using Pandas
* Identified numerical columns for analysis

---

### 2. Missing Data Analysis

* Computed:

  * Missing value counts
  * Missing percentages
* Visualized missing data using:

  * Missingno matrix plot
  * Missingness heatmap

---

### 3. Imputation Techniques

Three imputation methods were applied:

#### 🔹 Mean Imputation

* Replaced missing values with column mean
* Simple baseline approach

#### 🔹 K-Nearest Neighbors (KNN) Imputation

* Used `KNNImputer` (k = 3)
* Filled missing values based on similar observations

#### 🔹 Regression Imputation

* Used Linear Regression
* Predicted missing values using relationships between variables

---

### 4. Visualization

Histograms were used to compare:

* Original data (with missing values)
* Mean-imputed data
* KNN-imputed data
* Regression-imputed data

These visualizations helped assess how each method affects data distribution.

---

### 5. Evaluation

Performance was evaluated using **Mean Absolute Error (MAE)**:

<img width="220" height="61" alt="image" src="https://github.com/user-attachments/assets/1374693c-71d3-4adc-8341-441333632c38" />


Lower MAE indicates better reconstruction of the original dataset.

---

## 📊 Results

### 🔹 Mean Imputation

* Simplifies data
* Reduces variability
* Introduces bias toward the mean

### 🔹 KNN Imputation

* Preserves data structure
* Produces realistic values
* Achieved the **lowest MAE**

### 🔹 Regression Imputation

* Maintains relationships between variables
* Performs well when relationships are linear

---

## 🧠 Key Insights

* Missing data can distort distributions and relationships
* Simple imputation methods (mean) may introduce bias
* Advanced methods (KNN, regression) preserve data integrity better
* KNN performed best overall for this dataset

---

## ✅ Conclusion

This project demonstrates the importance of proper missing data handling in data science workflows.

* **KNN Imputation** is the most effective method for this dataset
* **Regression Imputation** is a strong alternative
* **Mean Imputation** should only be used as a baseline

---

## 📁 Project Structure

```
Project-2-Missing-Data-Imputation/
│
├── data/
│   ├── Insertion_Depth_Dataset_missing_values.csv
│   ├── Insertion_Depth_Dataset.csv
│
├── notebooks/
│   └── Project2_Missing_Data_Imputation.ipynb
│
├── reports/
│   ├── Project2_Report.pdf
│   └── Project2_Presentation.pptx
│
├── README.md
```
