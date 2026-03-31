# 🩸 Diabetes Prediction App: Clinical ML Dashboard

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![PyCaret](https://img.shields.io/badge/PyCaret-000000?style=flat&logo=python&logoColor=white)](https://pycaret.org/)
[![Live App](https://img.shields.io/badge/Live_App-View_Here-2e7d32?style=flat)](https://diabetes-bixsfuhcrftpume5tuhs7j.streamlit.app/)

## 🚀 Live Application
**Experience the interactive clinical dashboard here:** [Diabetes Prediction Web App](https://diabetes-bixsfuhcrftpume5tuhs7j.streamlit.app/)

## 📖 Overview
This repository contains a data-driven web application that integrates a pre-trained machine learning model into an interactive clinical dashboard. Built with **Streamlit** and **PyCaret**, the application utilizes a tuned Random Forest classifier to predict the likelihood of diabetes based on standard diagnostic measurements.

This project demonstrates the deployment phase of the CRISP-DM lifecycle, showcasing how to transition a trained model (`.pkl`) into an accessible, user-friendly tool for real-time inference.

## ✨ Key Features
* **Interactive Clinical Inputs:** A clean user interface allowing the input of 8 critical health metrics, including Glucose, BMI, Insulin levels, and Blood Pressure.
* **Integrated PyCaret Pipeline:** Utilizes PyCaret's `predict_model` functionality, ensuring that data transformations and model inference are handled seamlessly under the hood.
* **Automated Data Structuring:** The app automatically captures user inputs and converts them into a structured Pandas DataFrame format required by the machine learning model.
* **Real-Time Inference:** Instantaneous prediction generation with robust error handling to prevent app crashes if the model file is missing or inputs are invalid.

## 🛠️ Technology Stack
* **Language:** Python 3.10+
* **Web Framework:** Streamlit
* **Machine Learning:** PyCaret (Classification)
* **Data Manipulation:** Pandas

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/diabetes-prediction-app.git](https://github.com/yourusername/diabetes-prediction-app.git)
   cd diabetes-prediction-app

2. **Ensure Model is Present:**
Verify that the pre-trained model file tuned_rf_diabetes.pkl is located in the root directory of the project.

3. **Install the required dependencies:**
   ```bash
   pip install streamlit pandas pycaret
(Note: PyCaret is a heavy library. It is recommended to run this in an isolated virtual environment).

4. **Run the Streamlit App:**
   ```bash
   streamlit run app.py

5. **Access the Dashboard:**
Open your browser and navigate to the local URL provided in your terminal (usually http://localhost:8501).

⚠️ Disclaimer
For Educational Purposes Only. This application and its underlying machine learning model are designed for portfolio demonstration and educational purposes. It is not intended to be a substitute for professional medical advice, diagnosis, or treatment.

## ✍️ Author
Femi James Data & Business Analyst | Integrated AI Specialist

*(Don't forget to update the `yourusername` placeholder in the clone link before you commit it!)*
