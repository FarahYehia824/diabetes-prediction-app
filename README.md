# 🩺 Diabetes Prediction App

A **Streamlit web application** that predicts the likelihood of diabetes using machine learning models. Built with Python, scikit-learn, XGBoost, and Streamlit.

## 🌐 Live Demo
Try the app here 👉 **[Live Demo](https://your-app-link.streamlit.app)**

## 📂 Project Structure
```
diabetes-prediction-app/
│
├── diabets_prediction.py    # Main Streamlit application
├── data.csv                 # Dataset used in the project
├── requirements.txt         # Python dependencies
├── .gitignore              # Files ignored by Git
└── README.md               # Project documentation
```

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/FarahYehia824/diabetes-prediction-app.git
cd diabetes-prediction-app
```

### 2. Create Virtual Environment
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate

# On Mac/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
streamlit run diabets_prediction.py
```

The app will open in your browser at `http://localhost:8501`

## 🛠️ Technologies Used

- **Python 3.13**
- **Streamlit** - Web app framework
- **scikit-learn** - Machine learning models
- **imbalanced-learn (SMOTE)** - Data balancing
- **pandas & numpy** - Data manipulation
- **matplotlib & seaborn** - Data visualization
- **XGBoost** - Gradient boosting algorithm

## 📊 Features

- **Multiple ML Models**: Compare different algorithms for diabetes prediction
- **Data Visualization**: Interactive charts and graphs
- **User-friendly Interface**: Easy-to-use Streamlit interface
- **Real-time Predictions**: Get instant results
- **Model Performance**: View accuracy metrics and comparisons

## 🌐 Deployment

The application is deployed on **Streamlit Community Cloud** for easy access and sharing.

## 📝 Usage

1. Open the application in your browser
2. Input patient data (glucose level, BMI, age, etc.)
3. Select the machine learning model
4. Click predict to get diabetes likelihood
5. View results and model performance metrics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

**Farah Yehia** - [GitHub Profile](https://github.com/FarahYehia824)

---
⭐ If you found this project helpful, please give it a star!
