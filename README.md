# Crop Prediction & Yield Forecasting Using Machine Learning  
*(Based on `nasatest.ipynb`)*

## 📘 Project Overview
This project focuses on predicting **crop type** and **expected agricultural yield** based on environmental and climatic parameters. The notebook demonstrates how machine learning models can be trained and used to support agricultural decision-making using rainfall patterns, area size, and climate anomaly indicators such as **El Niño** and **La Niña**.

The goal is to build a simple but effective predictive system that helps farmers, researchers, and policymakers estimate crop suitability and yield under varying climate conditions.

---

## 🚀 Features
- ✔️ Data preprocessing and feature engineering  
- ✔️ Rainfall pattern analysis  
- ✔️ Climate anomaly integration (El Niño / La Niña)  
- ✔️ Machine learning model for crop prediction  
- ✔️ Yield forecasting model  
- ✔️ Final prediction using user-provided inputs  

---

## 📂 Notebook Workflow

### **1. Environment Setup**
The notebook begins by mounting Google Drive and importing necessary libraries such as NumPy, pandas, scikit-learn, etc.

### **2. Dataset Loading & Preparation**
- Loads the dataset containing historical crop, rainfall, and climate information.  
- Cleans and preprocesses the data.  
- Extracts monthly rainfall features.  
- Encodes categorical variables.

### **3. Exploratory Data Analysis**
Includes:  
- Statistical summaries  
- Feature distribution plots  
- Detection of rainfall patterns impacting crop growth and yield  

### **4. Model Training**
Two predictive models are trained:

#### 🌾 **Crop Classification Model**
Predicts crop suitability based on:
- Area  
- Monthly rainfall  
- El Niño presence  
- La Niña presence  

#### 📈 **Yield Regression Model**
Predicts estimated yield (e.g., tons per hectare) for the recommended crop.

### **5. Prediction Function**
A single function is developed to produce:
- **Predicted crop type**  
- **Estimated yield value**  

Inputs required:
- Area (hectares)  
- 12 monthly rainfall values  
- El Niño / La Niña flags  

### **6. Example Prediction**
The notebook demonstrates prediction using example inputs for rainfall, climate conditions, and land area.

---

## 🧪 Example Inputs
- **Area:** 5000 hectares  
- **El Niño:** 0  
- **La Niña:** 1  
- **Monthly Rainfall:** 12-number list  

### Example Output:
- **Recommended Crop:** (Model Result)  
- **Expected Yield:** (Model Estimate)

---

## 📦 Requirements
To run this notebook, install the following:

- Python 3  
- NumPy  
- Pandas  
- Scikit-Learn  
- Matplotlib / Seaborn *(optional)*  
- Jupyter Notebook or Google Colab  

---

## ▶️ How to Use
1. Open the notebook in your preferred environment.  
2. Upload/point to the dataset file.  
3. Run the notebook **cell by cell**.  
4. Modify the input values in the final cell to generate predictions for any region.

---

## 📚 Future Improvements
- Add soil-quality and pH data as features  
- Integrate satellite climate datasets (NASA POWER API, ERA5, etc.)  
- Use LSTM or transformer-based models for time-series rainfall  
- Deploy as a web dashboard or FastAPI backend  

---


