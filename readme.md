🌾 Crop Yield Prediction using Machine Learning
📌 Project Overview

This project predicts agricultural crop yield using Machine Learning techniques based on important environmental and soil parameters such as:

Nitrogen
Phosphorus
Potassium
Temperature
Humidity
pH Value
Rainfall
Crop Type

The system trains multiple machine learning models and selects the best-performing model for accurate crop yield prediction.

🚀 Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Joblib
Jupyter Notebook
📂 Dataset Features
Feature	Description
Nitrogen	Nitrogen content in soil
Phosphorus	Phosphorus content in soil
Potassium	Potassium content in soil
Temperature	Temperature in °C
Humidity	Humidity percentage
pH_Value	Soil pH value
Rainfall	Rainfall amount
Crop	Crop type
Yield	Crop yield (Target Variable)
🧠 Machine Learning Models Used
1️⃣ Linear Regression

A basic regression algorithm used for predicting continuous values.

2️⃣ Random Forest Regressor

An ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy.

⚙️ Project Workflow
Import required libraries
Load dataset
Handle missing values
Convert categorical data into numerical format
Split dataset into training and testing sets
Train multiple machine learning models
Evaluate models using:
Mean Squared Error (MSE)
R² Score
Select the best-performing model
Predict crop yield
Save trained model using Joblib
📊 Model Evaluation Metrics
Mean Squared Error (MSE)

Measures prediction error between actual and predicted values.

R² Score

Indicates how well the model fits the dataset.

Closer to 1 → Better model performance
Closer to 0 → Poor performance
📈 Output

The project outputs:

Predicted crop yield
Best-performing machine learning model
Actual vs Predicted graph
Saved trained model file (crop_price_model.pkl)
💾 Saved Model

The trained machine learning model is saved as:

crop_price_model.pkl

This model can later be loaded to make predictions without retraining.

▶️ How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/yourusername/Crop-Yield-Prediction.git
2️⃣ Install Dependencies
pip install pandas numpy matplotlib scikit-learn joblib
3️⃣ Run Jupyter Notebook
jupyter notebook

Open:

Crop_Yield_Prediction.ipynb
📌 Future Improvements
Add Deep Learning models
Create a web application using Flask/Streamlit
Deploy model online
Add real-time weather API integration
Improve prediction accuracy with larger datasets

👩‍💻 Author

Sanjana Netha

B.Tech Student | Machine Learning Enthusiast

⭐ GitHub Repository

If you found this project useful, consider giving it a ⭐ on GitHub!