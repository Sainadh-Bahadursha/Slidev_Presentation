---
theme: default
title: Introduction to Machine Learning
transition: fade
---

## <div style="text-align: center; font-size: 42px;">Introduction to Machine Learning</div>

<br/>

### <div style="text-align: center; font-size: 28px;">Bahadursha A V L Sainadh</div>

### <div style="text-align: center; font-size: 20px;">M.Tech Machine Design</div>

### <div style="text-align: center; font-size: 20px;">M.Sc AI & ML</div>

---
layout: two-cols-header
---

# Prerequisites

::left::

## Python Libraries
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  

## Mathematics
- Probability & Statistics  
- Linear Algebra  
- Calculus & Optimization  

::right::

## Data Visualization Concepts

1. One Variable Plots
   * Numerical → Histogram  
   * Categorical → Count Plot  

2. Two Variable Plots
   * Numerical vs Numerical → Scatter Plot  
   * Categorical vs Numerical → Bar Plot  
   * Categorical vs Categorical → Heatmap

3. Three Variable plots
   * Numerical, Numerical, Categorical → Scatter plot with category as color   
---

# Machine Learning vs Classical Programming

## Classical Programming
- Rigid rules written by programmers  
- Heavy use of hard coding  
- Rules do not change with data  

## Machine Learning
- Learns rules from data  
- Model is trained on data  
- Adapts based on patterns  

---
layout: two-cols
---

<div style="position: absolute; left: 50%; top: 10%; bottom: 10%; width: 2px; background: #ccc;"></div>

::left::

<div style="padding-right: 20px;">

# Example: Spam Detection

## Classical Programming
- Input: Text data  
- Use keywords and rules  
- Many if-else conditions  
- Rigid system  

## Machine Learning
- Input: Data + labels  
- Learns patterns automatically  
- No manual rule writing  

</div>

::right::

<div style="padding-left: 30px;">

# When to Use ML?

- When patterns are not clearly visible  
- When rules are difficult to define manually  
- When system needs to adapt with data  

<div style="margin-top: 25px;">

```mermaid
flowchart LR
A[New Email] --> B[ML Model h0]
B --> C[Decision: Spam / Non-Spam]
D[Training Data] --> B

subgraph Training
D --> B
end
```
</div>
</div>
---

# Types of Learning (Overview)

- Supervised Learning  
- Unsupervised Learning  
- Reinforcement Learning  

---

# Supervised Learning

- Output label (Y) is present  
- Model learns input → output mapping  

### Example
- House price prediction  
- Fraud detection  

---

# Unsupervised Learning

- No output labels  
- Finds hidden patterns in data  

### Example
- Customer segmentation  
- Document grouping  

---

# Reinforcement Learning

- Agent interacts with environment  
- Learns through reward and penalty  

### Key Components
- State  
- Action  
- Reward  

---

# Types of Tasks

- Classification  
- Regression  
- Clustering  
- Recommendation  
- Forecasting  

---

# Classification

- Predict category labels  

### Examples
- Churn prediction  
- Fraud detection  

---

# Regression

- Predict continuous values  

### Examples
- Credit score prediction  
- House price prediction  

---

# Clustering

- Group similar data points  

### Examples
- Customer segmentation  
- Document grouping  

---

# Recommendation

- Suggest relevant items  

### Examples
- Netflix movie recommendations  
- E-commerce product suggestions  

---

# Forecasting

- Predict future values  

### Examples
- Stock price prediction  
- Sales forecasting  

---

# ML Definition (ETP Framework)

> Machine learning is the study of algorithms that improve their performance (P) at a task (T) with experience (E).

---

# Components of ETP

## Task (T)
- Problem to solve  

## Experience (E)
- Training data  

## Performance (P)
- Evaluation metric  

---

# Example: Stock Price Prediction

- T: Predict stock price  
- E: Historical data  
- P: Mean Squared Error  

---

# Example: Customer Segmentation

- T: Segment customers  
- E: Transactional data  
- P: Cluster quality (intra vs inter distance)  

---

# Summary

- ML learns from data  
- Different learning types exist  
- Tasks vary based on problem  
- Performance improves with experience  

---