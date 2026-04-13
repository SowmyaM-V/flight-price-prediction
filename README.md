
# ✈️ Flight Fare Prediction System using Machine Learning with Flask Deployment

This project predicts flight ticket prices based on user inputs such as airline, source, destination, and travel details. The trained machine learning model is deployed as a web application using Flask to provide real-time predictions.

## 🚀 Features
- Flight ticket price prediction using machine learning  
- Real-time prediction through web interface  
- Feature engineering (date, time, duration, stops)  
- User-friendly UI with HTML and CSS  
- End-to-end ML pipeline (data → model → deployment)  
- Handles multiple airlines, sources, and destinations  

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Flask  
- HTML, CSS  

## ⚙️ Getting Started

### 🔹 Prerequisites
- Python 3.x  
- pip  

### 🔹 Installation

Install required libraries:
```bash
pip install pandas numpy scikit-learn flask

Run the application:
```bash
python app.py

📁 Project Structure
flight-fare-prediction/
├── app.py                  # Flask backend application
├── home.html              # Frontend UI
├── style.css              # Styling
├── flight_rf.pkl          # Trained ML model
├── data_train.xlsx        # Training dataset
├── test_set.xlsx          # Testing dataset
├── prediction.ipynb       # Model training notebook
└── README.md

💡 Usage
Enter flight details (source, destination, airline, date, time, stops)
Click submit
Get predicted flight price instantly


📊 Workflow
Data preprocessing and feature engineering
Model training using Random Forest
Model saved using Pickle
Flask app for deployment
User input → Prediction → Output display

💾 Data Storage
Model stored as .pkl file
Dataset stored locally
