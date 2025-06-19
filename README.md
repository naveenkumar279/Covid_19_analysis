# COVID-19 Data Analysis & Death Prediction using Regression Models

## 🔍 Project Description

This project focuses on analyzing a COVID-19 dataset to predict the number of deaths based on various features such as confirmed cases, active cases, recovered cases, and vaccination details. The main goal is to apply and compare different regression techniques:

- Simple Linear Regression (SLR)
- Multiple Linear Regression (MLR)
- Polynomial Regression

Through this analysis, the best-performing model is identified for predicting COVID-19 deaths using available data.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA) to understand patterns.
- Develop three regression models (SLR, MLR, Polynomial Regression).
- Compare model performance using R² Score and Mean Squared Error (MSE).
- Recommend the best model for predicting COVID-19 deaths.

---

## 📊 Dataset Description

- **Source**: Kaggle (COVID-19 State-wise Data)
- **Columns**:
  - `state`: State Name
  - `confirmed`: Confirmed Cases
  - `active`: Active Cases
  - `passive`: Recovered Cases
  - `deaths`: Number of Deaths
  - `dose1`, `dose2`, `dose3`, `precaution_dose`, `total_doses`: Vaccination Information
  - `population`: State Population

---

## 🛠️ Technologies Used

- Python 
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## ⚙️ Steps Performed

1. **Data Loading & Preprocessing**
   - Removed missing and duplicate values.
   - Verified data types and statistical summary.

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap.
   - Scatter plots & pairplots to visualize feature relationships.

3. **Model Development**
   - **Simple Linear Regression (SLR)** using 'confirmed' as predictor.
   - **Multiple Linear Regression (MLR)** using 'confirmed', 'active', 'passive'.
   - **Polynomial Regression** with degree 2 for non-linear modeling.

4. **Model Evaluation**
   - Evaluated models using R² Score and Mean Squared Error (MSE).
   - Plotted model prediction comparison for visual assessment.

5. **Model Comparison & Conclusion**
   - MLR and Polynomial Regression performed equally well (R² ~ 1.0).
   - **MLR chosen as best model** due to simplicity and interpretability.

---

## 📈 Results Summary

| Model                         | R² Score  | MSE            |
|------------------------------|----------|----------------|
| Simple Linear Regression (SLR)| 0.63     | High           |
| Multiple Linear Regression (MLR)| 1.0    | Low (Best)     |
| Polynomial Regression         | 1.0      | Very Low (Best)|

---

## ✅ Conclusion

- **Multiple Linear Regression (MLR)** is the best-performing and most practical model.
- MLR accurately predicts the number of deaths using confirmed, active, and passive cases.
- Simple Linear Regression underperforms due to limited feature usage.

---

## 💻 Author

- Naveen Kumar S- [Contact me ](https://github.com/naveenkumar279)
- Data Analyst & Python Enthusiast

