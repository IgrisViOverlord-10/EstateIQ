# 🏡 EstateIQ – Bangalore House Price Prediction Web Application

A Flask-based machine learning web application that predicts house prices in Bangalore using property-related features such as location, total square feet, BHK, and bathrooms.

The project demonstrates a complete end-to-end ML workflow including data preprocessing, feature engineering, regression model evaluation, and deployment through an interactive web interface.

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

# 📊 Dataset

This project uses the **Bengaluru House Price Dataset** for model training and evaluation.

- **Source:** [Bengaluru House Price Dataset (Kaggle)](https://www.kaggle.com/code/viveksingh0510/house-price-prediction-bangalore)

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

- Real-time Bangalore house price prediction
- End-to-end machine learning workflow
- Feature engineering and outlier handling
- Multiple regression model evaluation
- Flask-based interactive web application
- Trained ML model integration for predictions

---

# 🧪 Machine Learning Models & Results

| Model | R² Score |
|--------|----------|
| Linear Regression | 0.8234 |
| Lasso Regression | 0.8128 |
| Ridge Regression | 0.8234 |

### ✅ Final Model Selection

Although Linear Regression achieved similar accuracy, **Ridge Regression** was selected for its better generalization capability, stability against overfitting, and improved handling of multicollinearity.

---

# ⚙️ Development Workflow

## 📌 Model Development

- Data cleaning and preprocessing
- Feature engineering & outlier removal
- Regression model training and evaluation
- Final Ridge Regression model selection

## 📌 Web Application Integration

- Model serialization using Pickle (`.pkl`)
- Flask backend integration
- Property input form handling
- Real-time prediction rendering

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
- Data preprocessing & feature engineering
- Regression model evaluation
- Flask web application development
- Backend ML integration
- Real-time prediction systems

---

# 🔮 Future Improvements

- Implement advanced models (XGBoost, Random Forest, Neural Networks)
- Improve feature engineering techniques
- Integrate live real-estate market data
- Deploy application on cloud platforms (AWS / Azure / GCP)
- Add interactive analytics dashboard
- Enhance UI/UX responsiveness

---

# 👥 Contributors

This project was developed collaboratively by:

| Contributor | Primary Contributions |
|-------------|-----------------------|
| **Sai Ravi Chandran** | Designed and developed the frontend, implemented the Flask backend, integrated the trained machine learning model, handled application logic, and built the end-to-end web application. |
| **Sirisha V Ramana** | Performed data preprocessing, exploratory data analysis (EDA), feature engineering, trained and evaluated multiple machine learning models, and selected the final prediction model. |
| **Sneha Saphala R** | Assisted with data preparation, model development, testing, validation, and overall project implementation. |

---

# 🏁 Project Note

> **EstateIQ** was developed as a **mid-year academic project** to demonstrate the practical application of machine learning and web development. The project showcases data preprocessing, feature engineering, regression modeling, model evaluation, and deployment through a Flask-based web application.

---
