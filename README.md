# 🚦 Uber Traffic Volume Prediction using Machine Learning

This project focuses on analyzing historical traffic data and building machine learning models to predict hourly traffic volumes at different road junctions.

The project was completed as part of a **Mentor-Led Data Science Internship offered by Uber in collaboration with upGrad Campus.**

Accurate traffic prediction can help transportation authorities and ride-sharing platforms improve traffic management, reduce congestion, and optimize travel planning.

---

# 📌 Project Objectives

The main objectives of this project are:

• Analyze historical traffic congestion patterns  
• Identify peak traffic hours across different junctions  
• Understand the impact of weather conditions and special events  
• Build machine learning models to forecast hourly traffic volumes  
• Evaluate model performance using statistical metrics  

---

# 📊 Dataset Description

The dataset contains historical traffic information collected at different road junctions along with external influencing factors.

### Key Features

| Feature | Description |
|------|-------------|
| Date | Timestamp of traffic observation |
| Junction | Road junction identifier |
| Traffic_Volume | Number of vehicles observed |
| Temperature | Temperature at the time of observation |
| Rain | Indicator of rain conditions |
| Humidity | Humidity level |
| Hour | Hour of the day |
| Day_of_Week | Day of the week |
| Month | Month of the year |
| Weekend | Indicator for weekend |
| Traffic_Lag1 | Previous traffic volume |
| Event Indicators | Festival, Holiday, Marathon, Public Event |

These features help capture **temporal patterns and environmental influences on traffic congestion.**

---

# 🔎 Project Workflow

The project follows a complete **data science pipeline**:

### 1️⃣ Data Collection & Integration
Traffic data was integrated with weather information and special event indicators.

### 2️⃣ Data Cleaning & Preprocessing
Data preprocessing included:
- Handling missing values
- Correcting data types
- Encoding categorical features
- Feature engineering

### 3️⃣ Exploratory Data Analysis (EDA)
EDA was performed to understand:

• Traffic distribution across junctions  
• Peak traffic hours  
• Impact of weather conditions  
• Impact of special events  

### 4️⃣ Feature Engineering
New time-based features were generated:

- Hour of day
- Day of week
- Month
- Weekend indicator
- Traffic lag features

These features help capture **temporal dependencies in traffic flow**.

### 5️⃣ Machine Learning Models

Two predictive models were implemented:

**Linear Regression**

A baseline model that captures linear relationships between features and traffic volume.

**Random Forest Regressor**

An ensemble learning algorithm capable of capturing complex nonlinear patterns in traffic data.

### 6️⃣ Model Evaluation

Models were evaluated using the following metrics:

• Mean Absolute Error (MAE)  
• Root Mean Square Error (RMSE)  
• R-squared (R²)

### 7️⃣ Cross Validation

TimeSeriesSplit cross-validation was applied to preserve the chronological order of the traffic data.

### 8️⃣ Model Refinement

Hyperparameter tuning using **GridSearchCV** was performed to improve model performance.

---

# 📈 Key Insights

The analysis revealed several important patterns:

• Peak traffic occurs during **8–10 AM and 5–7 PM rush hours**  
• **Junction J2** experiences the highest congestion levels  
• Traffic volume is generally higher on **weekdays than weekends**  
• Weather conditions such as rain contribute to congestion  
• Special events cause temporary spikes in traffic volume  

These insights can help city planners optimize traffic control systems and improve road efficiency.

---

# 🧠 Technologies Used

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Jupyter Notebook

---

# 📂 Repository Structure
Uber-Traffic-Prediction-ML

data:
processed_traffic_dataset.csv

notebooks:
data_preprocessing.ipynb
traffic_analysis.ipynb
traffic_modeling.ipynb

reports:
peak_hour_traffic_analysis.pdf
model_evaluation_report.pdf


---

# 🚀 Future Improvements

Possible improvements for this project include:

• Developing a real-time traffic prediction dashboard  
• Implementing deep learning models such as LSTM for time-series forecasting  
• Integrating real-time traffic APIs  
• Deploying the model using a web application framework such as Streamlit

---

# 👩‍💻 Author

**Tejavath Shalini**

Data Science & Machine Learning Enthusiast  
Passionate about solving real-world problems using data.

LinkedIn: www.linkedin.com/in/tejavathshalini
---

# ⭐ Project Outcome

This project demonstrates the application of machine learning techniques for traffic congestion prediction and highlights the potential of predictive analytics in improving urban mobility and transportation planning.
