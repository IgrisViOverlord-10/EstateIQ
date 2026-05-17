# 🏙️ Bangalore House Price Prediction using Machine Learning

A Flask-based machine learning web application that predicts house prices in Bangalore using property-related features such as location, total square feet, BHK, and bathrooms.  
The project demonstrates a complete end-to-end ML workflow including data preprocessing, feature engineering, regression model evaluation, and deployment through an interactive web interface.

**Ridge Regression** was selected as the final model for its stability, regularization capability, and reliable prediction performance.

---

# 🚀 Tech Stack

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

# 🏗 Workflow & Prediction Pipeline

```bash
👤 User Enters Property Details
          ↓
🌐 Flask Web Interface
          ↓
⚡ Backend Data Processing
          ↓
🧹 Data Preprocessing Pipeline
          ↓
🧠 Trained Ridge Regression Model
          ↓
📊 House Price Prediction
          ↓
✅ Predicted Price Displayed To User
```

---

# ✨ Core Features

## 🧠 Machine Learning Module
- Data preprocessing and cleaning  
- Feature engineering and transformation  
- Outlier detection and removal  
- Multi-model regression training  
- Model evaluation and comparison  
- Final model serialization using Pickle  

## 🌐 Web Application Module
- Flask-based interactive web interface  
- Real-time house price prediction  
- Backend integration with trained ML model  
- User-friendly property input workflow  
- Dynamic prediction result rendering  

## 📊 Data Analysis & Processing
- Location-wise feature analysis  
- Price per square foot calculation  
- BHK extraction and transformation  
- Categorical feature encoding  
- Outlier filtering based on domain logic  

---

# 🧪 Machine Learning Models & Results

| Model | R² Score |
|--------|----------|
| Linear Regression | 0.8234 |
| Lasso Regression | 0.8128 |
| Ridge Regression | 0.8234 |

### ✅ Final Model Selection

Although Linear Regression achieved similar performance, **Ridge Regression** was selected as the final model due to:

- Better handling of multicollinearity  
- Reduced overfitting risk  
- More stable prediction behavior  
- Improved generalization capability  

---

# ⚙️ Development Workflow

## 📌 Phase 1 – Data Processing & Model Development

- Dataset cleaning and preprocessing  
- Missing value handling  
- Feature engineering implementation  
- Outlier detection and removal  
- One-Hot Encoding for categorical variables  
- Training multiple regression models  
- Model evaluation and comparison  
- Final model selection  

## 📌 Phase 2 – Web Application Integration

- Model serialization using Pickle (`.pkl`)  
- Flask backend integration  
- Property input form development  
- Prediction endpoint creation  
- Real-time prediction handling  
- Frontend result rendering  

---

# ⚙️ Data Preprocessing Pipeline

- Missing value handling using domain-specific logic  
- Removal of irrelevant columns  
- One-Hot Encoding for categorical variables  
- Feature scaling and normalization  
- Outlier filtering based on:
  - Square feet per BHK
  - Price per square foot
  - Location-based constraints

---

# 📂 Repository Structure

```text
House_Price_Predictor/
│
├── Client/
│   ├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── index.html
│
├── Datasets/
│   └── Bengaluru_House_Data.csv
│
├── Scripts/
│   ├── banglore_home_prices_model.pickle
│   ├── columns.json
│   └── House_Price_Predictions.ipynb
│
├── Server/
│   ├── artifacts/
│   ├── static/
│   ├── templates/
│   ├── form.py
│   ├── server.py
│   └── util.py
│
├── Snapshots/
├── README.md
└── requirements.txt
```

---

# ▶️ Running the Application

```bash
cd Server
python server.py
```

Then open in your browser:

```text
http://127.0.0.1:5000/
```

---

# 📸 Project Snapshots

| Screenshot | Description |
|------------|-------------|
| ![Input Page](Snapshots/Snap-1.png) | Property details input interface |
| ![Prediction Output](Snapshots/Snap-2.png) | Predicted house price result |

---

# 🧠 Skills Demonstrated

- Machine Learning workflow implementation  
- Data preprocessing & cleaning  
- Feature engineering techniques  
- Regression model development  
- Model evaluation & comparison  
- Outlier detection and handling  
- Flask web application integration  
- Backend ML prediction systems  
- Real-time inference workflow  
- End-to-end ML deployment concepts  

---

# 🔮 Future Improvements

- Implement advanced models (XGBoost, Random Forest, Neural Networks)  
- Improve feature engineering techniques  
- Integrate live real-estate market data  
- Deploy application on cloud platforms (AWS / Azure / GCP)  
- Add interactive analytics dashboard  
- Enhance UI/UX responsiveness  

---

---
