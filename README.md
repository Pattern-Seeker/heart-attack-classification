# Heart Attack Prediction Classification

A machine learning project that predicts the likelihood of a heart attack based on medical and health parameters using classification algorithms.

## Deployed Application

The Heart Attack Risk Prediction model has been deployed and can be accessed online.

**Live Demo:**  
https://heartalert.up.railway.app/

This web application allows users to input health-related information such as age, cholesterol level, blood pressure, lifestyle habits, and other factors to predict the potential risk of a heart attack using a machine learning model.

## Project Overview

This project leverages machine learning techniques to build a predictive model for identifying individuals at risk of heart attack. The model is trained on a comprehensive dataset containing various health indicators and demographic information, then deployed as a web application using Streamlit for easy accessibility and user interaction.

## Deployment Screenshots
![App Screenshot](screenshots/Landing%20Page.png)
![App Screenshot](screenshots/Prediction%20Page.png)

## Dataset

The dataset used in this project is sourced from **Kaggle**: [Heart Attack Prediction Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data)

### Dataset Features

- Contains multiple health indicators (age, blood pressure, cholesterol, etc.)
- Binary classification target (heart attack risk: yes=1/no=0)
- Pre-processed and cleaned data ready for analysis

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Statistical analysis of features
- Data distribution visualization
- Correlation analysis between variables
- Identification of patterns and outliers

### 2. Data Preprocessing

- Handling missing values
- Feature scaling and normalization
- Encoding categorical variables
- Train-test data splitting

### 3. Model Selection & Training

- Evaluation of multiple classification algorithms
- Hyperparameter tuning
- Cross-validation for model robustness
- Selection of the best performing model

## Technologies & Libraries

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib & Seaborn** - Data visualization
- **Streamlit** - Web framework for deployment
- **Jupyter Notebook** - Interactive development environment

## Project Structure

```
heart-attack-classification/
├── Heart_Attack_Classification.ipynb              # Main analysis and Model creation with unsupervised learning
├── Old_Heart_Attack_Classification.ipynb          # Main analysis and Older Model creation without unsupervised unsupervised learning
├── deployment                                     # model deployment with streamlit
├── heart_attack_prediction_dataset.csv            # Dataset file
└── README.md                                      # Project documentation
```

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. Clone or download this project
2. Install required dependencies:

### Usage

1. **Notebook Analysis**: Open the Jupyter notebook to explore the data, preprocessing steps, and model selection:

```bash
jupyter notebook "Heart Attack Classification.ipynb"
```

1. **Streamlit Deployment** Deploy the trained model as a web service for real-time predictions.

## Results & Output

The notebook outputs:

- Statistical summaries and visualizations
- Model performance metrics (accuracy, precision, recall)
- Best model selection for deployment

## License

This project uses publicly available data from Kaggle for educational purposes.

## Teams

- Dhimas Primajaya
- Jackson
- Reynold Kunarto
- Rijki Hardiyanti
- Zufar Bagas P.
