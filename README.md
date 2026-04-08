# Heart Disease Prediction System (KNN + Streamlit)

This project is a Machine Learning-based web application that predicts the risk of heart disease using user health parameters. The model is built using the K-Nearest Neighbors (KNN) algorithm and deployed with Streamlit for an interactive user interface.

🚀 Features
Interactive web app using Streamlit
Predicts heart disease risk (High / Low)
Real-time user input via sliders & dropdowns
Preprocessing using scaling and encoding
Uses trained KNN model for prediction
🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
Streamlit
Joblib (for model saving/loading)
📂 Project Structure
app.py → Streamlit web application
KNN_heart.pkl → Trained KNN model
scaler.pkl → Feature scaling object
columns.pkl → Model input column structure
Heart.csv → Dataset
MLProject_2.ipynb → Model training notebook
⚙️ How It Works
User enters health details:
Age, Blood Pressure, Cholesterol, etc.
Input data is:
Converted into proper format (one-hot encoding)
Scaled using a pre-trained scaler
KNN model predicts:
1 → High Risk
0 → Low Risk
▶️ Run the Project
pip install streamlit pandas numpy scikit-learn joblib
streamlit run app.py
📊 Input Parameters
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Max Heart Rate
Exercise Angina
Oldpeak
ST Slope
📌 Conclusion

This project demonstrates how machine learning can assist in early detection of heart disease, helping in preventive healthcare. It combines data preprocessing, model training, and deployment into a complete pipeline.

🔥 Future Improvements
Add multiple ML models (Logistic Regression, Random Forest)
Improve UI/UX design
Deploy on cloud (Streamlit Cloud / AWS)
Add accuracy & model evaluation metrics
