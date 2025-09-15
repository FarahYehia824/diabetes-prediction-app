# 🩺 Diabetes Prediction App

This is a **Streamlit web application** that predicts the likelihood of diabetes using different machine learning models.  
The app is built with **Python, scikit-learn, XGBoost, and Streamlit**.

---

## 📂 Project Structure
- `diabets_prediction.py` → main Streamlit app code  
- `diabetes.csv` → dataset used in the app  
- `requirements.txt` → dependencies required to run the app  
- `.gitignore` → ignored files/folders  

---

## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/FarahYehia824/diabetes-prediction-app.git
   cd diabetes-prediction-app
2. Create a virtual environment and activate it:
  python -m venv venv
  venv\Scripts\activate   # On Windows
  source venv/bin/activate   # On Mac/Linux

3. Install requirements:

  pip install -r requirements.txt

4. Run the app:

 streamlit run diabets_prediction.py

📂 Project Structure
diabetes-prediction-app/
│
├── diabets_prediction.py    # Main Streamlit app
├── data.csv                 # Dataset used in the project
├── requirements.txt         # Python dependencies
└── .gitignore               # Files ignored by Git

🌐 Deployment

The app is deployed on Streamlit Community Cloud.
You can try it here 👉 Live Demo

🛠️ Technologies Used

Python 3.13
Streamlit
scikit-learn
imbalanced-learn (SMOTE)
pandas, numpy
matplotlib, seaborn
xgboost
