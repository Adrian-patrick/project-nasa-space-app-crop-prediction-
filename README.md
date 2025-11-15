📘 Project Overview

This project focuses on predicting crop type and expected agricultural yield based on environmental and climatic parameters. The notebook demonstrates how machine learning models can be trained and used to support agricultural decision-making using rainfall patterns, area size, and climate anomaly indicators such as El Niño and La Niña.

The goal is to build a simple but effective predictive system that helps farmers, researchers, and policymakers estimate crop suitability and yield under varying climate conditions.

🚀 Features

✔️ Data preprocessing and feature engineering

✔️ Rainfall pattern analysis

✔️ Climate anomaly integration (El Niño / La Niña)

✔️ Machine learning model for crop prediction

✔️ Yield forecasting model

✔️ Final prediction using user-provided inputs

📂 Notebook Workflow
1. Environment Setup

The notebook begins by mounting Google Drive and importing necessary libraries such as NumPy, pandas, scikit-learn, etc.

2. Dataset Loading & Preparation

Loads the dataset containing historical crop, rainfall, and climate information.

Cleans and preprocesses the data.

Extracts monthly rainfall features.

Encodes categorical variables.

3. Exploratory Data Analysis

Includes:

Statistical summary

Feature distribution

Detection of patterns in rainfall impacting crop yield

4. Model Training

Two predictive models are trained:

🌾 Crop Classification Model

Determines the most suitable crop depending on:

Total area

Monthly rainfall

Presence of El Niño

Presence of La Niña

📈 Yield Regression Model

Predicts the yield (e.g., tons per hectare) for the recommended crop.

5. Prediction Function

A unified function is created to generate:

Predicted crop type

Estimated yield

Given:

Area (hectares)

12 monthly rainfall values

El Niño / La Niña indicators

6. Example Prediction

The notebook ends with a demonstration prediction using sample values.

🧪 Example Inputs

Area: 5000 hectares

El Niño: 0

La Niña: 1

Monthly Rainfall: 12-month vector

The model outputs:

Recommended Crop

Expected Yield

📦 Requirements

To run this notebook you need:

Python 3

NumPy

Pandas

Scikit-Learn

Google Colab (optional)

Matplotlib / Seaborn (optional for visualization)

▶️ How to Use

Open the notebook in Google Colab or Jupyter.

Upload the dataset or update the path.

Run the cells sequentially.

Modify the input section at the end to test predictions for your own parameters.

📚 Future Improvements

Integrate satellite rainfall data (e.g., NASA POWER API)

Add soil quality parameters

Use deep learning models for sequential rainfall patterns

Create a web API or dashboard for real-time predictions
