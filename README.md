# Crop Yield / Production Prediction using Machine Learning

## 1. Problem Understanding
The objective of this project is to build a machine learning model that predicts
an agricultural outcome using real-world data. In this project, crop production
is predicted based on historical agricultural records.

Predicting crop production helps in agricultural planning, food supply estimation,
and decision-making by farmers and policymakers. The focus of this project is on
understanding the data, building a reliable machine learning pipeline, and
explaining the model behavior rather than maximizing accuracy alone.

---

## 2. Dataset Description
The dataset used in this project is a publicly available agricultural dataset
containing crop production records across different states and districts in India.
It represents real-world farming conditions and includes both categorical and
numerical features.

### Features
- State Name  
- District Name  
- Crop Year  
- Season  
- Crop  
- Area (cultivated area)  

### Target Variable
- Production  

The dataset contains more than 240,000 records and does not include a direct
yield column. Therefore, production was chosen as the target variable.

---

## 3. Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset and checked data types and structure
- Verified that there were no missing values
- Removed unnecessary columns
- Encoded categorical features using Label Encoding
- Selected relevant features based on domain knowledge

---

## 4. Model Pipeline
The machine learning pipeline followed in this project consists of:
1. Data understanding and preprocessing  
2. Encoding categorical features  
3. Train–test split (80% training, 20% testing)  
4. Model training using Random Forest Regressor  
5. Model evaluation using regression metrics  
6. Inference on unseen data  

This ensures an end-to-end workflow from raw data to prediction.

---

## 5. Model Selection and Training
A Random Forest Regressor was used because crop production depends on multiple
interacting factors and the relationships are not strictly linear. The model
performs well on large tabular datasets and captures non-linear patterns.

---

## 6. Results and Evaluation Metrics
The model was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

A high R² score was observed, which is expected because crop production is strongly
dependent on cultivated area and crop type. This reflects realistic agricultural
behavior rather than overfitting.

---

## 7. Inference Explanation
After training, the model was used to predict crop production for unseen input
data. Given inputs such as crop type, location, season, year, and cultivated area,
the model outputs an estimated production value.

---

## 8. How to Run the Project
1. Clone the repository  
2. Install required dependencies:
  # Crop Yield / Production Prediction using Machine Learning

## 1. Problem Understanding
The objective of this project is to build a machine learning model that predicts
an agricultural outcome using real-world data. In this project, crop production
is predicted based on historical agricultural records.

Predicting crop production helps in agricultural planning, food supply estimation,
and decision-making by farmers and policymakers. The focus of this project is on
understanding the data, building a reliable machine learning pipeline, and
explaining the model behavior rather than maximizing accuracy alone.

---

## 2. Dataset Description
The dataset used in this project is a publicly available agricultural dataset
containing crop production records across different states and districts in India.
It represents real-world farming conditions and includes both categorical and
numerical features.

### Features
- State Name  
- District Name  
- Crop Year  
- Season  
- Crop  
- Area (cultivated area)  

### Target Variable
- Production  

The dataset contains more than 240,000 records and does not include a direct
yield column. Therefore, production was chosen as the target variable.

---

## 3. Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset and checked data types and structure
- Verified that there were no missing values
- Removed unnecessary columns
- Encoded categorical features using Label Encoding
- Selected relevant features based on domain knowledge

---

## 4. Model Pipeline
The machine learning pipeline followed in this project consists of:
1. Data understanding and preprocessing  
2. Encoding categorical features  
3. Train–test split (80% training, 20% testing)  
4. Model training using Random Forest Regressor  
5. Model evaluation using regression metrics  
6. Inference on unseen data  

This ensures an end-to-end workflow from raw data to prediction.

---

## 5. Model Selection and Training
A Random Forest Regressor was used because crop production depends on multiple
interacting factors and the relationships are not strictly linear. The model
performs well on large tabular datasets and captures non-linear patterns.

---

## 6. Results and Evaluation Metrics
The model was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

A high R² score was observed, which is expected because crop production is strongly
dependent on cultivated area and crop type. This reflects realistic agricultural
behavior rather than overfitting.

---

## 7. Inference Explanation
After training, the model was used to predict crop production for unseen input
data. Given inputs such as crop type, location, season, year, and cultivated area,
the model outputs an estimated production value.

---

## 8. How to Run the Project
1. Clone the repository  
2. Install required dependencies:
  # Crop Yield / Production Prediction using Machine Learning

## 1. Problem Understanding
The objective of this project is to build a machine learning model that predicts
an agricultural outcome using real-world data. In this project, crop production
is predicted based on historical agricultural records.

Predicting crop production helps in agricultural planning, food supply estimation,
and decision-making by farmers and policymakers. The focus of this project is on
understanding the data, building a reliable machine learning pipeline, and
explaining the model behavior rather than maximizing accuracy alone.

---

## 2. Dataset Description
The dataset used in this project is a publicly available agricultural dataset
containing crop production records across different states and districts in India.
It represents real-world farming conditions and includes both categorical and
numerical features.

### Features
- State Name  
- District Name  
- Crop Year  
- Season  
- Crop  
- Area (cultivated area)  

### Target Variable
- Production  

The dataset contains more than 240,000 records and does not include a direct
yield column. Therefore, production was chosen as the target variable.

---

## 3. Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset and checked data types and structure
- Verified that there were no missing values
- Removed unnecessary columns
- Encoded categorical features using Label Encoding
- Selected relevant features based on domain knowledge

---

## 4. Model Pipeline
The machine learning pipeline followed in this project consists of:
1. Data understanding and preprocessing  
2. Encoding categorical features  
3. Train–test split (80% training, 20% testing)  
4. Model training using Random Forest Regressor  
5. Model evaluation using regression metrics  
6. Inference on unseen data  

This ensures an end-to-end workflow from raw data to prediction.

---

## 5. Model Selection and Training
A Random Forest Regressor was used because crop production depends on multiple
interacting factors and the relationships are not strictly linear. The model
performs well on large tabular datasets and captures non-linear patterns.

---

## 6. Results and Evaluation Metrics
The model was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

A high R² score was observed, which is expected because crop production is strongly
dependent on cultivated area and crop type. This reflects realistic agricultural
behavior rather than overfitting.

---

## 7. Inference Explanation
After training, the model was used to predict crop production for unseen input
data. Given inputs such as crop type, location, season, year, and cultivated area,
the model outputs an estimated production value.

---

## 8. How to Run the Project
1. Clone the repository  
2. Install required dependencies:
  pip install pandas numpy scikit-learn
3. Open the notebook:
  crop_yield.ipynb
4. Run all cells sequentially to view preprocessing, training, evaluation, and
prediction outputs.

---

## 9. Notes
This project was developed as an academic learning exercise to demonstrate
machine learning fundamentals, data handling, model reasoning, and result
interpretation using real-world agricultural data.
