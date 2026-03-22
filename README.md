# 🔋 Energy Consumption Prediction using Machine Learning and PowerBI

## 📌 Problem Statement
Energy consumption varies based on factors like building type, temperature, number of occupants, and appliances used. 
Manual estimation is inefficient and inaccurate.

The goal of this project is to predict energy consumption using machine learning regression models.

---

## 📊 Dataset
The dataset contains information about buildings and their energy usage.

**Features:**
- Building Type (Residential, Commercial, Industrial)
- Square Footage
- Number of Occupants
- Appliances Used
- Average Temperature
- Day of Week

**Target Variable:**
- Energy Consumption (kWh)

---

## ⚙️ Machine Learning Workflow
- Data Loading and Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing (Scaling + Encoding)
- Model Training using Pipelines
- Model Evaluation

---

## 🤖 Models Used
- Linear Regression (Best Model)
- Ridge Regression
- Lasso Regression
- ElasticNet Regression

---

## 📈 Results
- R² Score ≈ 1.00
- Very low MAE and RMSE
- Linear Regression achieved the highest accuracy

---

## 🔍 Key Insights
- Square Footage has the strongest impact on energy consumption
- Building Type significantly influences energy usage
- Temperature has minimal effect on energy consumption
- Data distribution is approximately normal (ideal for regression)

---

## 📊 Visualization
- Distribution plots
- Boxplots (Building Type vs Energy)
- Correlation Heatmap
- Actual vs Predicted graph

---

## 🚀 Conclusion
Linear Regression provided the best performance with high accuracy and interpretability. 
The model can effectively predict energy consumption for different building types.

---
## 📊 Project Presentation

You can view the complete project explanation here:

👉 [Download Presentation](./presentation/energy_consumption_presentation.pptx)
👉 [View Full Presentation](https://docs.google.com/presentation/d/1qs-r56lcnunWuMudDsJppxOfxwO0qSKH/edit?usp=sharing&ouid=114432283418290135554&rtpof=true&sd=true)

This presentation includes:
- Problem Statement
- Data Analysis
- Model Comparison
- Power BI Visualizations
- Key Insights

## 📁 Project Structure
electricity-consumption-ml/
│── EnergyConsumption.ipynb
│── model.pkl
│── data/
│── Presentation
│── README.md


---

## 👤 Author
Nivedhitha K 
📍 Coimbatore, India  
📧 nivedhitha.nivi15@gmail.com