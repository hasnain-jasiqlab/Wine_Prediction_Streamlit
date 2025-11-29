🍷 Wine Quality Prediction Using KNN

This project uses the K-Nearest Neighbors (KNN) algorithm to predict the quality of red wine based on various physicochemical attributes. It includes an interactive Streamlit web application where users can enter wine characteristics and instantly get a quality prediction.

📸 Application Preview
<p align="center"> <img src="https://github.com/user-attachments/assets/455b4694-4ebc-4959-be99-cd94eef27770" alt="Wine Quality Prediction App" width="800"> </p>
🧪 Dataset

This project uses the Red Wine Quality Dataset from the UCI Machine Learning Repository, containing 1,599 samples with features like:

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Quality (target)

✨ Features

✅ Upload or input wine characteristics
✅ KNN Classifier with n_neighbors=3
✅ StandardScaler used during preprocessing
✅ Built with Streamlit for fast UI
✅ Real-time wine quality prediction
✅ Clean and responsive interface

🌐 Live Demo

Explore the deployed web app here:
👉 https://wine-qul-app.streamlit.app/

📊 Methodology
1. Data Preprocessing

No missing values detected

Features standardized using StandardScaler

2. Exploratory Data Analysis (EDA)

Count plots for class distribution

Correlation heatmap between features

3. Model Training

Train-test split: 80% training | 20% testing

Trained using KNN (n_neighbors=3)

4. Evaluation

Accuracy and classification report

Moderate handling of class imbalance

5. Model Saving

Exported using pickle

model.pkl

scaler.pkl

🔍 Results

📌 Test Accuracy: ~60%
✔ Could be improved using:

Hyperparameter tuning

Sampling techniques

Ensemble learning

📉 Limitations:

Dataset is imbalanced (ratings 3, 4, 7, 8 are rare)

KNN is sensitive to scaling and feature distribution

🧠 Challenges Faced

Class imbalance

Selecting the best value of k

Ensuring proper feature scaling (critical for KNN)

📁 Project Structure
📂 Wine-Quality-KNN
│── data/
│   └── winequality-red.csv
│── model/
│   ├── model.pkl
│   └── scaler.pkl
│── app.py
│── knn_train.ipynb
│── requirements.txt
│── README.md

📩 Contact

👤 Md Hasnain Raza
📧 mdhasnainraza463@gmail.com

🔗 GitHub: @mdhasnainrazaa

⭐ If you found this project useful, please consider giving it a star! ⭐
