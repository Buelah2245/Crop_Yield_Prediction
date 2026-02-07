# Crop Yield / Production Prediction using Machine Learning

1. Problem Understanding

The objective of this project is to build a machine learning model that predicts
an agricultural outcome using real-world data. In this case, the model predicts
*crop production* based on historical agricultural records.

Predicting crop production is important for agricultural planning, food supply
management, and decision-making by farmers and policymakers. This project focuses
on understanding the data, building a reliable prediction pipeline, and explaining
model behavior rather than maximizing accuracy alone.

---

2. Dataset Description

The dataset used in this project is a publicly available agricultural dataset
containing crop production records across different states and districts in India.
It represents real-world farming conditions and includes both categorical and
numerical features.

Features
- State Name  
- District Name  
- Crop Year  
- Season  
- Crop  
- Area (cultivated area)  

Target Variable
- Production  

The dataset contains more than 240,000 records and does not include a direct
`Yield` column. Therefore, *Production* was chosen as the target variable, as it
is the directly available and measurable outcome.

---

3. Data Preprocessing

The following preprocessing steps were performed:
- Loaded the dataset and inspected data types and structure
- Verified that the dataset contains no missing values
- Removed unnecessary columns
- Encoded categorical variables (State, District, Season, Crop) using Label Encoding
- Selected relevant features based on domain knowledge

These steps prepared the data for effective model training.

---

4. Model Pipeline

The machine learning pipeline followed in this project consists of:
1. Data understanding and preprocessing  
2. Encoding categorical features  
3. Train–test split (80% training, 20% testing)  
4. Model training using Random Forest Regressor  
5. Model evaluation using regression metrics  
6. Inference on unseen data  

This ensures a complete end-to-end workflow from raw data to prediction.

---

5. Model Selection and Training

A *Random Forest Regressor* was used for this task because:
- Crop production depends on multiple interacting factors
- Relationships between features and production are non-linear
- Random Forest performs well on large, structured tabular datasets

The model was trained on the training dataset and tested on unseen data.

---

6. Results and Evaluation Metrics

The model was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

A high R² score was observed, which is expected because crop production is strongly
dependent on cultivated area and crop type. This reflects realistic agricultural
behavior rather than overfitting.

The evaluation focused on understanding model performance and limitations rather
than accuracy alone.

---

7. Inference Explanation

After training, the model was used to predict crop production for unseen input
data. Given values such as crop type, location, season, year, and cultivated area,
the model outputs an estimated production value.

This inference step demonstrates the practical applicability of the model in
real-world agricultural scenarios.

---

8. How to Run the Project

1. Clone the repository  
2. Install required dependencies:
    pip install -r requirements.txt
3. Open the notebook:
    crop_yield.ipynb
4. Run all cells sequentially to view preprocessing, training, evaluation, and
prediction outputs.

---

9. Notes

This project was developed as an academic learning exercise to demonstrate
machine learning fundamentals, data handling, model reasoning, and result
interpretation using real-world agricultural data.
