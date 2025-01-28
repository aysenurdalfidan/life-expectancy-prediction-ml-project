# Life Expectancy Prediction Using Machine Learning

This project utilises machine learning techniques to predict life expectancy based on socioeconomic and health factors, using a dataset from the World Health Organisation (WHO). The project includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## Project Overview

Life expectancy is a critical metric used to gauge the overall health and well-being of populations globally. This project aims to explore the factors influencing life expectancy and develop a predictive model that provides actionable insights.

The dataset includes indicators such as GDP, schooling, healthcare expenditure, mortality rates, and more. Using this information, we build machine learning models to predict life expectancy.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:  
[Life Expectancy Data](https://www.kaggle.com/kumarajarshi/life-expectancy-who).

### Description:
The dataset contains various health, economic, and demographic indicators for countries worldwide, including:
- **Life Expectancy:** Target variable
- **Year:** Year of observation
- **Status:** Developed or Developing countries
- **Adult Mortality:** Mortality rate of adults
- **Alcohol Consumption:** Per capita alcohol consumption
- **GDP, Schooling, Population:** Economic and demographic indicators
- **Hepatitis B, Polio, Diphtheria Vaccinations:** Vaccination coverage
- **HIV/AIDS:** Prevalence rate and its impact

---

## Project Workflow

### 1. Problem Framing
This is a **supervised regression problem**, where the target variable is **Life Expectancy**. The aim is to predict life expectancy using a set of health, economic, and demographic predictors.

### 2. Steps Involved
1. **Data Loading:** The dataset is loaded and inspected for completeness.
2. **Exploratory Data Analysis (EDA):**
   - Visualisations to identify correlations and distributions.
   - Summary statistics and data profiling.
3. **Data Preprocessing:**
   - Handling missing values.
   - Encoding categorical features.
   - Feature scaling.
4. **Model Training:**
   - Multiple machine learning models (e.g., Linear Regression, Random Forest, Gradient Boosting) are trained and evaluated.
5. **Fine-Tuning:**
   - Hyperparameter optimisation using GridSearchCV.
6. **Model Evaluation:**
   - Performance measured with R², Mean Absolute Error (MAE), and Mean Squared Error (MSE).

---

## Results

### Key Insights:
- **Socioeconomic factors such as GDP and schooling have a strong positive correlation with life expectancy.**
- **Diseases like HIV/AIDS negatively impact life expectancy significantly.**

### Model Performance:
- The final Random Forest model achieved:
  - **R² score:** 0.85
  - **Mean Absolute Error (MAE):** 2.3 years