# 🏡 EstateIQ – Bangalore House Price Prediction Web Application

A Flask-based machine learning web application that predicts residential property prices in Bangalore using **Ridge Regression**. 
The project demonstrates an end-to-end machine learning workflow, from data preprocessing and feature engineering to model deployment through an interactive web interface.

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

# 📝 Model Input Features

The prediction model estimates Bangalore house prices using the following property attributes:

| Feature | Description |
|----------|-------------|
| **Location** | Area or locality of the property |
| **Total Square Feet** | Total built-up area (sq. ft.) |
| **BHK** | Number of bedrooms |
| **Bathrooms** | Number of bathrooms |

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

Although Linear Regression achieved similar accuracy, **Ridge Regression** was selected because it achieved performance comparable to Linear Regression while reducing coefficient variance through L2 regularization. This improves stability in the presence of multicollinearity and helps reduce overfitting.

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

# ▶️ Installation & Running the Application

## Clone the Repository

```bash
git clone https://github.com/your-username/House_Price_Predictor.git
```

## Navigate to the Project

```bash
cd House_Price_Predictor
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Start the Flask Server

```bash
cd Server
python server.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

---

# 💡 Sample Prediction

### Input

| Property Feature | Value |
|------------------|-------|
| Location | Whitefield |
| Total Area | 1200 sq. ft. |
| BHK | 2 |
| Bathrooms | 2 |

### Predicted Output

```text
Estimated House Price:
₹84.5 Lakhs
```

> *Prediction shown above is for demonstration purposes.*

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

> **Note:** This repository is intended for educational and academic purposes. The application is designed to be run locally following the installation instructions provided above.

---
