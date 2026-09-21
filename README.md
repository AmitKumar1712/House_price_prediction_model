# 🏠 House Price Prediction using Machine Learning

A **Machine Learning-based House Price Prediction Web Application** developed using **Python and Django**. The application uses a trained Machine Learning model to predict house prices based on user-provided property details.

This project demonstrates the complete workflow from **data preprocessing and model training to Django web integration and real-time prediction**.

---

## 📌 Project Overview

House Price Prediction is a web-based Machine Learning project that predicts the estimated price of a house based on different property-related features.

The Machine Learning model is trained using a housing dataset. After training, the model is saved as a `.pkl` file and integrated into a Django web application.

Users can enter the required property information through the web interface, and the application generates the predicted house price.

---

## ✨ Key Features

* 🏠 House price prediction using Machine Learning
* 🤖 Trained and saved ML model
* 🌐 Django web application
* 📊 Housing dataset for model training
* 🧹 Data preprocessing and analysis
* 🔢 Feature-based price prediction
* 💾 Saved model using Pickle
* 🖥️ Simple and user-friendly interface
* ⚡ Fast prediction through Django backend

---

## 🧠 Machine Learning Workflow

```text
Dataset
   ↓
Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Saving (.pkl)
   ↓
Django Integration
   ↓
User Input
   ↓
House Price Prediction
```

---

## 📊 Dataset

The project uses a housing dataset containing property-related information required for training the Machine Learning model.

| Dataset       | Description                                       |
| ------------- | ------------------------------------------------- |
| `housing.csv` | Housing dataset used for ML training and analysis |
| `house.pkl`   | Saved trained Machine Learning model              |

The dataset is available in the `DataSet` and `Training Files` directories.

---

## 📁 Project Structure

```text
House_price_prediction_model/
│
├── DataSet/
│   └── housing.csv
│
├── House_price/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── Training Files/
│   ├── House_Price_Prediction-checkpoint-checkpoint.ipynb
│   ├── housing.csv
│   └── house.pkl
│
├── myapp/
│   ├── migrations/
│   │   └── __init__.py
│   ├── templates/
│   │   └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   └── house.pkl
│
├── manage.py
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AmitKumar1712/House_price_prediction_model.git
```

### 2. Navigate to the Project

```bash
cd House_price_prediction_model
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Required Packages

```bash
pip install django pandas numpy scikit-learn
```

---

## ▶️ Run the Application

Start the Django development server:

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

---

## 🌐 How It Works

1. User opens the Django web application.
2. User enters the required house/property details.
3. Django receives the input through the backend.
4. The trained Machine Learning model is loaded.
5. Input data is processed according to the model requirements.
6. The model generates the predicted house price.
7. The predicted result is displayed on the web page.

---


## 🤖 Machine Learning Model

The trained Machine Learning model is stored using Python's Pickle library.

```text
house.pkl
```

The saved model allows the Django application to make predictions without retraining the model every time the application runs.

---

## 📷 Application Preview

You can add screenshots of your application below.

### Home Page

```markdown
![Home Page](screenshots/home.png)
```

### Prediction Result

```markdown
![Prediction Result](screenshots/result.png)
```

> Create a `screenshots` folder in the project and place your screenshots inside it.

---

## 🎯 Project Objectives

* Build a Machine Learning model for house price prediction.
* Perform data analysis and preprocessing.
* Train and save a Machine Learning model.
* Integrate the trained model with Django.
* Create a web interface for user input.
* Generate house price predictions through the web application.

---

## 📌 Learning Outcomes

Through this project, I gained practical experience in:

* Python programming
* Machine Learning
* Data preprocessing
* Dataset analysis
* Model training
* Model saving and loading
* Django development
* ML model integration with web applications
* Git and GitHub

---

## 👨‍💻 Author

### Amit Kumar

**Computer Science & Engineering**

🔗 **GitHub:**
https://github.com/AmitKumar1712

---

## ⭐ Repository

If you find this project useful, feel free to explore the repository and give it a ⭐.

**GitHub Repository:**
https://github.com/AmitKumar1712/House_price_prediction_model

---

## 📄 License

This project is developed for **educational and learning purposes**.
