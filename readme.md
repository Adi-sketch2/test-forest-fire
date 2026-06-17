# 🔥 Forest Fire FWI Prediction | End-to-End Machine Learning Project

This project is an End-to-End Machine Learning application that predicts the **Fire Weather Index (FWI)** using weather and environmental parameters from the Algerian Forest Fires Dataset.

The project covers the complete Machine Learning pipeline, including:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Feature Selection
- Model Training
- Ridge Regression
- Model Serialization using Pickle
- Flask Web Application
- Model Deployment

---

# 📌 Problem Statement

Forest fires can cause significant environmental and economic damage. The goal of this project is to predict the **Fire Weather Index (FWI)** based on weather conditions and fire-related parameters.

The prediction helps estimate fire risk levels and can be used for fire prevention and monitoring systems.

---

# 📊 Dataset Information

Dataset: Algerian Forest Fires Dataset

The dataset contains meteorological and fire weather observations collected from two regions of Algeria:

- Bejaia Region
- Sidi-Bel Abbes Region

### Features Used

| Feature | Description |
|----------|-------------|
| Temperature | Temperature in °C |
| RH | Relative Humidity |
| Ws | Wind Speed |
| Rain | Rainfall |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| ISI | Initial Spread Index |
| Classes | Fire / Not Fire |
| Region | Region Identifier |

### Target Variable

```text
FWI (Fire Weather Index)
```

---

# 🧠 Machine Learning Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Feature Selection
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Ridge Regression
        ↓
Pickle Model Saving
        ↓
Flask Deployment
```

---

# 🔍 Exploratory Data Analysis

Performed:

- Missing Value Handling
- Data Cleaning
- Categorical Encoding
- Correlation Analysis
- Multicollinearity Detection
- Feature Selection

---

# ⚙️ Model Training

The following regression algorithms were explored:

### Linear Regression

Baseline regression model.

### Ridge Regression

Used to handle multicollinearity and improve generalization.

### Lasso Regression

Used for feature selection and regularization.

### Final Model

```text
Ridge Regression
```

---

# 📂 Project Structure

```text
forest-fire-prediction/
│
├── application.py
├── requirements.txt
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── notebook/
│   ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│   └── modeltaningrl.ipynb
│
└── README.md
```

---

# 🌐 Flask Application

The trained Ridge Regression model is deployed using Flask.

Users can enter:

- Temperature
- RH
- Wind Speed
- Rain
- FFMC
- DMC
- ISI
- Classes
- Region

The application returns:

```text
Predicted Fire Weather Index (FWI)
```

---

# 🖥️ Web Application Preview

### Input

```text
Temperature
RH
Ws
Rain
FFMC
DMC
ISI
Classes
Region
```

### Output

```text
FWI Prediction
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/forest-fire-prediction.git
```

Move into the project directory:

```bash
cd forest-fire-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Start the Flask application:

```bash
python application.py
```

Open your browser and visit:

```text
http://127.0.0.1:1000
```

---

# 📦 Requirements

```text
Flask
pandas
numpy
scikit-learn
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

# 📈 Sample Prediction Flow

```text
User Input
      ↓
StandardScaler
      ↓
Ridge Regression Model
      ↓
FWI Prediction
      ↓
Result Display
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Flask
- HTML
- Jupyter Notebook

---

# 📚 Machine Learning Concepts Used

- Data Cleaning
- Feature Engineering
- Correlation Analysis
- Multicollinearity
- Standardization
- Train-Test Split
- Linear Regression
- Ridge Regression
- Lasso Regression
- Model Serialization
- Flask Deployment

---

# 🔮 Future Improvements

- Better UI with Bootstrap
- REST API Support
- Docker Containerization
- AWS Deployment
- Render Deployment
- Real-Time Monitoring

---

# 👨‍💻 Author

### Aaditya Bhatt

BCA (Artificial Intelligence & Data Science)

Passionate about:

- Machine Learning
- Data Science
- Artificial Intelligence
- Python Development

---

## ⭐ If you found this project useful, please consider giving it a star on GitHub.