
🏠 AI Powered House Price Prediction System

Transforming Real Estate Insights using Machine Learning

🌟 Project Overview

This project is a Machine Learning based House Price Prediction Web App that predicts the selling price of a house based on input features.

The model is trained using structured housing data and deployed using Streamlit for real-time interactive predictions.

This project demonstrates:

✔ Data preprocessing
✔ Regression modeling
✔ Model serialization
✔ Web app deployment
✔ End-to-end ML pipeline

🧠 How It Works

1️⃣ Model is trained using train.csv
2️⃣ Data is cleaned and preprocessed
3️⃣ Regression model is built using Scikit-Learn
4️⃣ Model is saved as house_model.pkl
5️⃣ Streamlit loads the model
6️⃣ User inputs house features
7️⃣ App predicts price instantly 💰

📂 Project Structure
SCT_ML_1/
│
├── app.py                 # Streamlit Web Application
├── model.py               # Model training script
├── house_model.pkl        # Saved trained model
├── train.csv              # Training dataset
├── test.csv               # Testing dataset
├── sample_submission.csv  # Sample output format
├── requirements.txt       # Required libraries
└── README.md              # Project documentation

🚀 Technologies Used

🐍 Python

📊 Pandas

🤖 Scikit-Learn

🌐 Streamlit

💾 Pickle

⚙️ Installation Guide

Step 1: Clone Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Step 2: Install Dependencies
pip install -r requirements.txt

If requirements.txt is empty, add this:

streamlit
pandas
scikit-learn
numpy

Step 3: Run the Application
python -m streamlit run app.py  ##important

Then open:

http://localhost:8501

🎯 Key Features

✨ Clean and Interactive UI
✨ Real-Time Price Prediction
✨ Pre-trained ML Model
✨ Simple and Easy to Use
✨ Beginner-Friendly ML Deployment

📈 Model Details

Type: Supervised Learning

Problem: Regression

Algorithm: Linear Regression / Random Forest (based on implementation)

Evaluation Metrics: MAE / RMSE

🔮 Future Enhancements

🚀 Deploy on Streamlit Cloud
📊 Add Visualizations
📈 Show Model Accuracy
💡 Add Advanced Feature Engineering