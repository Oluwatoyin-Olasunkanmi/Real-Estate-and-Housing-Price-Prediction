# 🏠 Real-Estate and Housing Price Prediction

![Image](https://github.com/user-attachments/assets/809d330e-1f78-46e6-91d1-e811fdc2aede)

## 📌 Introduction
This project analyzes and predicts housing prices using statistical analysis and multiple linear regression. The objective is to identify key factors that influence house prices and quantify their impact through regression modeling.

The project emphasizes **data analysis, interpretation, and insight generation** rather than machine learning deployment.

## 🎯 Objectives
- Identify key factors influencing housing prices  
- Answer defined research questions using data  
- Apply regression analysis for price prediction  
- Interpret statistical outputs clearly and meaningfully  

---

## ❓ Research Questions
1. How does property size influence housing prices?  
2. What effect does the number of bedrooms have on housing prices?  
3. Do bathrooms significantly affect housing prices?  
4. Does furnishing status impact housing prices?  
5. How do location preferences influence housing prices?  
6. How well do structural, amenity, and location features explain variations in housing prices?  

---

## 🗂 Dataset Description
The dataset consists of **545 residential housing records**, including:

- Property size  
- Number of bedrooms  
- Number of bathrooms  
- Furnishing status  
- Amenities and structural features  
- Location attributes (main road access, preferred area)  
- Housing price (target variable)  

Data was cleaned to remove missing values, correct data types, and ensure suitability for regression analysis.

---

## 🛠 Tools & Techniques Used
- Microsoft Excel (Data Cleaning & Regression Analysis)  
- Descriptive Statistics  
- Multiple Linear Regression  
- Pivot Tables and Charts  
- Power BI (for visualization)  

---

## 📊 Exploratory Data Analysis (EDA)

### Descriptive Statistics (Sample)

| Variable | Mean | Min | Max |
|--------|------|-----|-----|
| Housing Price | — | — | — |
| Property Size | — | — | — |
| Bedrooms | — | — | — |
| Bathrooms | — | — | — |

**Interpretation:**  
Housing prices show substantial variability, suggesting that multiple factors contribute to price differences. Structural features such as size and room count vary widely across properties.

---

## 📈 Regression Analysis

### Model Specification
A multiple linear regression model was estimated as:

\[
\text{Housing Price} = \beta_0 + \beta_1(\text{Size}) + \beta_2(\text{Bedrooms}) + \beta_3(\text{Bathrooms}) + \beta_4(\text{Furnishing}) + \beta_5(\text{Location}) + \varepsilon
\]

---

## 🏗 Structural & Amenity Regression Summary

### Regression Statistics

| Metric | Value |
|------|------|
| Multiple R | 0.536 |
| R Square | 0.287 |
| Adjusted R Square | 0.281 |
| Standard Error | 1,783,124 |
| Observations | 545 |

**Interpretation:**  
Approximately **28.7% of the variation in housing prices** is explained by structural and amenity-related variables. This indicates **moderate explanatory power**, with room for improvement through additional predictors.

---

### ANOVA Summary

| Source | df | F | Significance F |
|------|----|----|---------------|
| Regression | — | — | < 0.05 |

**Interpretation:**  
The model is **statistically significant overall**, confirming that the included predictors jointly influence housing prices.

---

### Coefficient Interpretation (Summary)

| Variable | Effect on Price | Interpretation |
|--------|----------------|----------------|
| Property Size | Positive | Larger properties command higher prices |
| Bedrooms | Positive | Additional bedrooms increase value |
| Bathrooms | Moderate Positive | Incremental price increase |
| Furnishing Status | Positive | Furnished houses are priced higher |
| Amenities | Mixed | Some amenities show weak influence |

---

## 📍 Location Preference Analysis

This section evaluates the effect of **location-related factors** on housing prices, focusing on proximity to main roads and preferred residential areas.

### Regression Statistics (Location Model)

| Metric | Value |
|------|------|
| Multiple R | 0.405 |
| R Square | 0.164 |
| Adjusted R Square | 0.161 |
| Standard Error | 1,713,017 |
| Observations | 545 |

**Interpretation:**  
Location variables alone explain approximately **16.4% of the variation in housing prices**, demonstrating that location plays a **meaningful but partial role** in price determination.

---

### ANOVA Results

| Source | df | F | Significance F |
|------|----|----|---------------|
| Regression | 2 | 53.29 | 7.45 × 10⁻²² |
| Residual | 542 | | |
| Total | 544 | | |

**Interpretation:**  
The very low **Significance F** confirms that the location model is **highly statistically significant**, meaning location factors jointly have a strong effect on housing prices.

---

### Location Coefficients

| Variable | Coefficient | P-value | Interpretation |
|--------|------------|--------|----------------|
| Intercept | 3,366,651 | < 0.001 | Baseline housing price |
| Main Road | 1,290,807 | < 0.001 | Price premium for proximity to major roads |
| Preferred Area | 1,241,756 | < 0.001 | Higher prices in desirable neighborhoods |

**Interpretation:**  
- Properties near **main roads** experience an average price increase of approximately **₦1.29 million**.  
- Houses located in **preferred residential areas** command an average premium of **₦1.24 million**.  
- Both variables are **highly statistically significant**, confirming the importance of accessibility and neighborhood desirability.

---

## 🔍 Findings by Research Question
- Property size is the strongest predictor of housing prices.  
- Bedrooms and bathrooms positively influence prices, though with diminishing returns.  
- Furnishing status increases housing value.  
- Location preferences significantly affect prices, particularly access to main roads and preferred areas.  
- Combining structural and location variables improves overall model performance.

---

## ⚠️ Limitations
- Assumes linear relationships between variables  
- Excludes broader economic and geographic factors  
- Based on historical data  

---

## 🚀 Future Improvements
- Integrate location and structural variables into a unified model  
- Include economic and market indicators  
- Compare alternative regression techniques  
  

---

