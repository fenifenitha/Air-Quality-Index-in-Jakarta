🌍 Air Quality Index Prediction in Jakarta using Machine Learning






📌 Project Overview

Air pollution is one of the most critical environmental challenges affecting urban populations worldwide. The Air Quality Index (AQI) is a standardized indicator used to measure and communicate air pollution levels and their potential health impacts.

This project focuses on analyzing and predicting the Air Quality Index in Jakarta, Indonesia, using machine learning techniques. By analyzing historical air quality data and environmental factors, the model aims to provide insights into pollution patterns and help predict future air quality levels.

Such predictive models can support environmental monitoring, public health awareness, and policy decision-making.
🎯 Project Objectives

Analyze historical air pollution data in Jakarta

Perform Exploratory Data Analysis (EDA) to understand pollution trends

Identify key factors influencing air quality levels

Develop a machine learning model to predict AQI

Evaluate model performance using appropriate regression metrics




📊 Dataset Description

The dataset includes multiple environmental variables used to calculate and analyze AQI levels.

Typical features in the dataset include:

| Feature     | Description                               |
| ----------- | ----------------------------------------- |
| PM2.5       | Fine particulate matter concentration     |
| PM10        | Particulate matter with diameter ≤10 µm   |
| NO₂         | Nitrogen dioxide concentration            |
| SO₂         | Sulfur dioxide concentration              |
| CO          | Carbon monoxide level                     |
| O₃          | Ozone concentration                       |
| Temperature | Ambient temperature                       |
| Humidity    | Relative humidity                         |
| AQI         | Air Quality Index value (target variable) |




🔍 Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand the structure and patterns within the dataset.

Key techniques used:

Histogram to examine pollutant distribution

Scatter plots to analyze relationships between variables

Heatmaps to identify correlations among pollutants

Boxplots to detect outliers in environmental measurements

EDA helps reveal pollution trends and influential environmental factors.




🧠 Machine Learning Approach

The project applies supervised machine learning techniques to predict the Air Quality Index.

Common regression algorithms used include:

Linear Regression

Random Forest Regressor

Decision Tree Regressor

These models are trained on historical pollution data to learn patterns and predict AQI levels.

📈 Model Evaluation

The performance of the prediction model is evaluated using regression metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)
R² Score



⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

📂 Project Structure
Air-Quality-Index-Jakarta
│
├── dataset
│   └── aqi_jakarta_data.csv
│
├── notebooks
│   └── aqi_analysis.ipynb
│
├── src
│   └── aqi_prediction_model.py
│
├── images
│   └── visualizations.png
│
├── README.md
└── requirements.txt



🌱 Future Improvements

Deploy the prediction model using Streamlit or Flask

Integrate real-time air quality data

Apply deep learning models for time-series prediction

Develop an interactive dashboard for AQI monitoring

🌍 Real-World Impact

Predicting air quality levels can help:

Improve public health awareness

Assist environmental policy planning

Enable early pollution alerts

Support sustainable urban development



👩‍💻 Author

Fenitha
BTech Computer Science Engineering
Interested in Machine Learning, Data Science, and Artificial Intelligence
