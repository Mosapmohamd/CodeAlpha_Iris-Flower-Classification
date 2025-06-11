# 🌸 Iris Flower Classification Dashboard

![Streamlit App](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An interactive Streamlit web application for exploring the Iris flower dataset, comparing machine learning models, and making live predictions.

![Dashboard Screenshot](assets/app-screenshot.png) <!-- Add your screenshot path here -->

## Features

- **Data Exploration**: Visualize feature distributions and relationships
- **Model Comparison**: Evaluate performance of multiple ML models
- **Live Predictions**: Get real-time species classification
- **Interactive Visualizations**: Dynamic charts and graphs
- **Responsive Design**: Works on desktop and mobile devices

## Technologies Used

- Python 3.8+
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iris-classification.git
   cd iris-classification
Create and activate a virtual environment:

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:

bash
pip install -r requirements.txt
Download the trained models and place them in the root directory:

Logistic_Regression_model.pkl

Random_Forest_model.pkl

SVM_model.pkl

XGBoost_model.pkl

Usage
Run the Streamlit application:

bash
streamlit run app.py
The application will open in your default browser at http://localhost:8501

Explore the different sections:

Data Exploration: View dataset statistics and visualizations

Model Performance: Compare model metrics and confusion matrices

Live Predictions: Input measurements to get species predictions

File Structure
text
iris-classification/
├── app.py                  # Main application file
├── data/
│   └── iris.csv            # Iris dataset
├── assets/                 # Images and screenshots
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── (model files)           # Pretrained model .pkl files
Dataset
The application uses the classic Iris flower dataset containing:

150 samples

4 features:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

3 target classes:

Iris-setosa

Iris-versicolor

Iris-virginica

Models Included
Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

XGBoost Classifier
