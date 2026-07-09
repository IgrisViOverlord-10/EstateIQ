# 🏡 EstateIQ – Bangalore House Price Prediction Web Application

EstateIQ is an end-to-end machine learning application that predicts residential property prices in Bangalore based on key property attributes such as location, total square feet, number of bedrooms (BHK), and bathrooms. The project demonstrates the complete ML lifecycle, from data preprocessing and feature engineering to regression model training, evaluation, and deployment through an interactive Flask web application.

---

# ✨ Project Highlights

- Bangalore House Price Prediction
- End-to-End Machine Learning Pipeline
- Data Cleaning & Feature Engineering
- Regression Model Comparison
- Flask Web Application
- Real-Time Price Prediction

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

- **Source (Kaggle):** [Bengaluru House Price Dataset](https://www.kaggle.com/code/viveksingh0510/house-price-prediction-bangalore)

Dataset Characteristics:

- Bangalore residential properties
- Multiple locations across the city
- Property size (sq. ft.)
- BHK
- Bathrooms
- Property prices

---

# 🏠 Prediction Inputs

The prediction model estimates house prices using the following property features:

- Total Square Feet
- Number of Bedrooms (BHK)
- Number of Bathrooms
- Location

These features are processed by the trained regression model to estimate the property's market value.

---

# 🧹 Data Preprocessing

The raw housing dataset underwent several preprocessing steps before model training:

- Missing value handling
- Location normalization
- Outlier removal
- Feature engineering
- One-hot encoding of categorical features
- Train-test split

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

- Location-aware house price prediction
- Real-time prediction through a Flask web application
- Data preprocessing and feature engineering
- Regression model comparison and evaluation
- Ridge Regression model integration
- Responsive user interface

---

# 🧪 Machine Learning Models & Results

| Model | R² Score |
|--------|----------|
| Linear Regression | **0.8234** |
| Lasso Regression | 0.8128 |
| Ridge Regression | **0.8234** |

**Evaluation Metric:** R² (Coefficient of Determination), where values closer to **1.0** indicate better predictive performance.

### Final Model

Although Linear Regression and Ridge Regression achieved the same R² score, **Ridge Regression** was selected as the final model due to its L2 regularization, which improves generalization and reduces the impact of multicollinearity.

---

# ⚙️ Development Workflow

## Model Development

- Data cleaning and preprocessing
- Feature engineering & outlier removal
- Regression model training and evaluation
- Final Ridge Regression model selection

## Deployment & Integration

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
│   ├── Snap-11.png
│   ├── Snap-22.png
│
├── README.md
└── requirements.txt
```

---

# ▶️ Getting Started

## 1) Clone the Repository

```bash
git clone https://github.com/Sai-2410/EstateIQ.git
```

Move into the project directory:

```bash
cd House_Price_Predictor
```

---

## 2) Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3) Run the Flask Application

Navigate to the server directory:

```bash
cd Server
```

Start the Flask server:

```bash
python server.py
```

---

## 4) Open the Application

Open the application in your browser at:

```text
http://127.0.0.1:5000/
```

The EstateIQ web application will launch in your browser, allowing users to enter property details and receive real-time house price predictions.

---

# 📸 Project Snapshots

| Screenshot | Description |
|------------|-------------|
| ![Input Page](Snapshots/Snap-11.png) | Property details input interface |
| ![Prediction Output](Snapshots/Snap-22.png) | Predicted house price result |

---

# 💡 Skills Demonstrated

### Machine Learning

- Regression Modeling
- Feature Engineering
- Model Evaluation
- Data Preprocessing

### Frameworks & Libraries

- Scikit-Learn
- Pandas
- NumPy
- Flask

### Software Development

- Backend & Frontend Integration
- REST-Based Prediction Workflow
- Real-Time Inference

### Tools & Deployment

- Git & GitHub
- Jupyter Notebook
- Pickle Model Serialization
- Flask Development Server

---

# 🔮 Future Improvements

- Improve feature engineering techniques
- Implement advanced models (XGBoost, Random Forest, Neural Networks)
- Integrate live real-estate market data
- Add interactive analytics dashboard
- Enhance UI/UX responsiveness
- Deploy application on cloud platforms (AWS / Azure / GCP)

---

# ⚠️ Current Limitations

- Limited to Bangalore housing data
- Predictions depend on dataset quality
- Does not account for current market fluctuations
- Does not include amenities such as parking, age of property, or nearby facilities

---

# 👥 Contributors

This project was developed collaboratively by:

| Contributor | Contributions |
|-------------|---------------|
| **Sai R** | Developed the frontend and Flask backend, integrated the trained machine learning model, implemented the application logic, and contributed to end-to-end web application development. |
| **Sirisha V Ramana** | Performed data preprocessing, exploratory data analysis (EDA), feature engineering, trained and evaluated machine learning models, and contributed to model selection and optimization. |
| **Sneha Saphala R** | Contributed to data preparation, model testing and validation, prepared project reports and documentation, and supported the overall implementation and evaluation of the project. |

---

# 📝 Project Note

> **EstateIQ** demonstrates how a machine learning model can be transformed into a production-style web application by combining data preprocessing, feature engineering, regression modeling, and Flask-based deployment.

The project highlights the complete workflow from preparing housing data and training predictive models to delivering real-time house price predictions through an interactive web interface.

---
