🌫️ PM2.5 Pollution Predictor

A modular machine learning project that predicts PM2.5 pollution levels using weather features like temperature, humidity, hour, and month. Built with clarity, reproducibility, and beginner-friendly design, this project showcases how environmental data can be transformed into actionable insights.


📌 Project Summary

This project was developed to address the unpredictability of PM2.5 pollution levels, which vary based on weather and time. By building a predictive model using accessible features, the goal was to enable proactive environmental monitoring and demonstrate a reproducible ML workflow for peer learning.


🧠 What I Did

 1. **Data Cleaning & Exploration**
- Imported raw pollution and weather data from CSV files.
- Cleaned missing values and standardized column formats.
- Mapped numeric months to labels (e.g., 1 → Jan) for readability.
- Explored seasonal and hourly patterns in temperature, humidity, and PM2.5.
- Calculated monthly averages to uncover environmental trends.

 2. **Feature Selection & Model Training**
- Selected four key features: `temperature`, `humidity`, `hour`, and `month`.
- Split the dataset into training and testing sets.
- Trained two models: **Linear Regression** and **Random Forest Regressor**.
- Evaluated both using **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.
- Saved the best-performing model using `joblib` for later use.

 3. **Prediction & Simulation**
- Loaded the saved model and simulated predictions on sample inputs.
- Verified prediction accuracy and ensured the model responded to realistic weather conditions.
- Generated visual outputs:
  - Monthly averages (bar chart)
  - Hourly PM2.5 trends (line chart)
  - PM2.5 distribution (histogram)
  - PM2.5 vs hour (line chart)

 4. **Documentation & Deployment**
- Structured the project into clear folders: `Week_1_Dataset`, `Week_2_Model`, `Week_3_Deployment`.
- Documented every step with comments and markdown cells in Jupyter Notebooks.
- Pushed the entire project to GitHub with a clean commit history.
- Prepared screenshots of outputs for presentation and validation.


 🛠️ Tools & Technologies

- **Python** – Core language  
- **Pandas** – Data manipulation  
- **scikit-learn** – ML modeling  
- **Joblib** – Model saving/loading  
- **Matplotlib** – Visualization  
- **Jupyter Notebook** – Development & documentation  
- **Git & GitHub** – Version control & deployment  
- *(Optional)* **Firebase Hosting** – For frontend dashboard integration

📁 Folder Structure

ML_Project/
│
├── Week_1_(Dataset_Preparation)/
│   └── Week1_Dataset_Preparation.ipynb
│
├── Week_2_(Model_Implementation)/
│   ├── Week2_Model_Implementation.ipynb
│   └── saved_model/
│       └── pollution_predictor.pkl
│
├── Week_3_(Deployment_and_Presentation)/
│   └── Week3_Deployment_and_Presentation.ipynb
│
├── requirements.txt
└── README.md


