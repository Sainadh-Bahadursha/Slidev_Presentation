---
theme: default
title: Linear Regression
transition: fade
---

## <div style="text-align: center; font-size: 42px;">Linear Regression</div>

<br/>

### <div style="text-align: center; font-size: 28px;">Bahadursha A V L Sainadh</div>

### <div style="text-align: center; font-size: 20px;">M.Tech Machine Design</div>

### <div style="text-align: center; font-size: 20px;">M.Sc AI & ML</div>

---
layout: two-cols-header
---
::left::
## What is Linear Regression?

- Fundamental **supervised learning algorithm**  
- Models relationship between:
  - Independent variable (X)
  - Dependent variable (Y)
- Predicts **continuous values**

## Key Points
- Assumes linear relationship  
- Uses **best-fit line**  
- Used in:
  - Predictive modeling  
  - Forecasting  

::right::

<div style="text-align:center;">

<img src="./images/Linear_Reg_0.png" style="width:100%; margin-top:20px;" />

<p style="font-size:12px; margin-top:8px; color:#666;">
Figure: Linear Regression Overview <br/>
Source: GeeksforGeeks
</p>

</div>
---
layout: two-cols-header
---

# Intuition + Example
::left::
## Example: Exam Score Prediction

- Predict score based on **hours studied**
- X (Independent) → Hours studied  
- Y (Dependent) → Exam score  
- More hours → higher score  & Relationship ≈ straight line with positive slope

## Example: Car Price Prediction

- Predict car price based on **age of car**
- X (Independent) → age of car
- Y (Dependent) → car price 
- More age → less car price  & Relationship ≈ straight line with negative slope
::right::
<div style="padding-left: 20px;">

<img src="\images\Linear_Reg_1.png" style="width:75%; margin-top:20px;">

<img src="\images\Linear_Regression_1_2.png" style="width:75%; margin-top:50px;">

</div>
---
layout: two-cols-header
---

# Best Fit Line + Goal

<div style="display:flex; justify-content:center;">

  <img src="./images/Lin_reg_2_1.png" style="width:60%; margin:20px;" />

</div>

::left::

## What is Best Fit Line?

- Line that best represents data  
- Minimizes error between:
  - Actual values  
  - Predicted values  

### Goal
- Find line with **minimum error**

::right::

<div style="display:flex; justify-content:center;">

  <img src="./images/Lin_reg_2.png" style="width:80%; margin-top:20px;" />

</div>

---

# Equation + Interpretation

## Linear Equation


::contentReference[oaicite:0]{index=0}


### Meaning
- y → predicted value  
- x → input  
- m → slope (change rate)  
- b → intercept  

---

## Interpretation

- Slope (m):
  - Change in Y for 1 unit change in X  

- Intercept (b):
  - Value of Y when X = 0  

---

# Residuals + Error

## Residual

:contentReference[oaicite:1]{index=1}

- Difference between:
  - Actual value  
  - Predicted value  

---

## Least Squares

:contentReference[oaicite:2]{index=2}

- Minimize squared error  
- Ensures best-fit line  

---

<!-- 📌 IMAGE:
Residual lines from points to line
<img src="./images/residuals.png" style="width:75%; margin-top:20px;">
-->

---

# Hypothesis Function

## Simple Linear Regression

:contentReference[oaicite:3]{index=3}

---

## Multiple Linear Regression

:contentReference[oaicite:4]{index=4}

---

### Meaning
- β₀ → intercept  
- β₁, β₂ → feature importance  

---

# Cost Function + Optimization

## Cost Function (MSE)

:contentReference[oaicite:5]{index=5}

- Measures prediction error  
- Goal → minimize  

---

## Gradient Descent

- Start with random values  
- Compute error  
- Update parameters  
- Repeat  

---

<!-- 📌 IMAGE:
Cost curve + gradient descent steps
<img src="./images/gradient_descent.png" style="width:70%; margin-top:20px;">
-->

---

# Assumptions

- Linearity  
- Independence of errors  
- Constant variance (Homoscedasticity)  
- Normal distribution of errors  
- No multicollinearity  
- No autocorrelation  
- Additivity  

---

<!-- 📌 IMAGE:
Assumption plots (your infographic bottom section)
<img src="./images/assumptions.png" style="width:85%; margin-top:20px;">
-->

---

# Evaluation Metrics

- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R-Squared  
- Adjusted R-Squared  

---

# Types + Use Cases

## Types

- Simple Linear Regression  
- Multiple Linear Regression  

---

## Applications

- Real Estate → price prediction  
- Finance → stock forecasting  
- Agriculture → crop yield  
- E-commerce → sales prediction  

---

# Advantages vs Limitations

## Advantages
- Simple & interpretable  
- Fast & efficient  
- Good baseline model  

---

## Limitations
- Assumes linearity  
- Sensitive to outliers  
- Cannot capture complex patterns  

---