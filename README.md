# 🚗 Car Price Prediction using Machine Learning

This project is a **Car Price Prediction System** built using **Machine Learning (Scikit-learn)**.  
It predicts the **car price (in lakhs)** based on important features like insurance validity, fuel type, kilometers driven, ownership, and transmission type.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that can predict the **selling price of a car** based on given car details.

This project includes:
- Data preprocessing
- Feature encoding
- Training multiple ML models
- Comparing model performance
- Saving the best model using Pickle (`.pkl` file)

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## 📂 Dataset

Dataset file used in this project:

📌 **Car Dataset Processed.csv**

### Dataset contains columns like:
- insurance_validity
- fuel_type
- kms_driven
- ownsership
- transmission
- price(in lakhs)

---

## ⚙️ Features Used

### Input Features (X)

| Feature Name | Description |
|------------|-------------|
| insurance_validity | Insurance type |
| fuel_type | Petrol / Diesel / CNG |
| kms_driven | Total kilometers driven |
| ownsership | First/Second/Third owner |
| transmission | Manual / Automatic |

### Target Column (y)

| Column Name | Description |
|------------|-------------|
| price(in lakhs) | Car price in lakhs |

---

## 🔄 Data Preprocessing

Categorical columns were converted into numerical values using mapping.

### Insurance Validity Encoding
```python
{'Comprehensive':0,
 'Third Party insurance':1,
 'Zero Dep':2,
 'Not Available':3,
 'Third Party':1}
