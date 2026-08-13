# ✈️ Flight Fare Prediction

An end-to-end machine learning application that predicts flight fares based on flight-related features such as airline, source and destination cities, travel class, departure and arrival information, number of stops, journey duration, and days remaining before departure.

The project demonstrates a complete machine learning workflow, from data ingestion and preprocessing to model training, evaluation, and deployment through a Flask web application.

## 🎯 Project Objective

Flight ticket prices vary depending on several factors such as airline, route, travel class, timing, duration, number of stops, and how early the ticket is booked.

The objective of this project is to build a machine learning solution that learns patterns from historical flight data and provides an estimated fare based on user-provided flight details.

## 🚀 Key Features

* Historical flight data processing and preprocessing
* Exploratory data analysis and visualization
* Feature transformation for machine learning
* Machine learning model training and evaluation
* Modular training and prediction pipelines
* Flight fare prediction through a Flask web application
* Experiment and model tracking using MLflow
* Dataset and pipeline versioning using DVC
* Reproducible project structure for machine learning workflows

## 🏗️ Project Workflow

```text
Historical Flight Dataset
          │
          ▼
    Data Ingestion
          │
          ▼
  Data Transformation
          │
          ▼
   Feature Engineering
          │
          ▼
    Model Training
          │
          ▼
   Model Evaluation
          │
          ▼
    Trained Model
          │
          ▼
 Prediction Pipeline
          │
          ▼
    Flask Application
          │
          ▼
   Predicted Flight Fare
```

## 🧠 Machine Learning Workflow

### 1. Data Ingestion

The project loads the historical flight dataset and prepares it for the subsequent processing stages.

### 2. Data Transformation

The raw data is processed and transformed into a format suitable for machine learning.

This stage includes handling the input features and preparing the data for model training.

### 3. Model Training

Machine learning models are trained using the transformed dataset.

The training pipeline is organized separately from the application layer to keep the machine learning workflow modular.

### 4. Model Evaluation

The trained models are evaluated using appropriate regression evaluation metrics to determine their performance.

### 5. Prediction Pipeline

The prediction pipeline loads the trained model and transformation components and processes new flight information to generate a fare prediction.

## 🌐 Flask Application

A Flask-based web application provides a user interface for entering flight details and obtaining a predicted fare.

Users can provide information such as:

* Airline
* Source city
* Destination city
* Travel class
* Departure time
* Arrival time
* Number of stops
* Journey duration
* Days remaining before departure

The application passes the input through the prediction pipeline and displays the estimated flight fare.

## 🛠️ Technology Stack

### Programming

* Python

### Data Processing & Analysis

* Pandas
* NumPy

### Machine Learning

* Scikit-learn

### Data Visualization

* Matplotlib
* Seaborn

### Web Application

* Flask
* HTML
* CSS

### MLOps & Reproducibility

* MLflow
* DVC

### Development Tools

* Git
* GitHub
* Virtual Environment

## 📁 Project Structure

```text
Flight-Fare-Prediction/
│
├── Artifacts/
│
├── Notebook_Experiments/
│
├── src/
│   └── FlightPricePrediction/
│       ├── components/
│       ├── pipeline/
│       ├── exception.py
│       ├── logger.py
│       └── utils.py
│
├── static/
│
├── templates/
│
├── mlruns/
│
├── app.py
├── dvc.yaml
├── dvc.lock
├── requirements.txt
├── setup.py
├── Dockerfile
├── template.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/THOSIF986/-Flight-Fare-Prediction.git
cd -Flight-Fare-Prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python app.py
```

Open the application in your browser using the local Flask URL displayed in the terminal.

## 📊 Machine Learning Pipeline

The project separates the machine learning workflow into independent stages:

```text
Data Ingestion
       ↓
Data Transformation
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Prediction Pipeline
```

This modular structure makes the project easier to maintain, test, and extend.

## 📈 MLOps

### MLflow

MLflow is used to support experiment tracking and machine learning workflow management.

### DVC

DVC is used to support versioning and reproducibility of data and machine learning pipeline stages.

These tools help make the machine learning workflow more reproducible and organized.

## 🔮 Future Improvements

* Add a REST API endpoint for programmatic predictions
* Improve model performance through hyperparameter tuning
* Add additional regression models for comparison
* Add automated model evaluation
* Improve input validation
* Deploy the application to a cloud platform
* Add automated CI/CD for the application
* Add monitoring for model predictions

## 👨‍💻 Author

**Thosif Pasha**

GitHub: https://github.com/THOSIF986

LinkedIn: Add your LinkedIn profile here

Email: [thosifpasha.2004@gmail.com](mailto:thosifpasha.2004@gmail.com)
