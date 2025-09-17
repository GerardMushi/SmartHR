SmartHR – AI-Powered HR Analytics Platform

SmartHR is an AI-powered HR analytics platform that integrates multiple machine learning modules into a single Streamlit dashboard.
It helps organizations analyze, predict, and make data-driven HR decisions in three key areas:

Attrition Prediction – Predict employee turnover using ML models

Absenteeism Analysis – Detect absenteeism patterns and classify risk levels

Resume Classification – Automatically classify resumes using NLP & deep learning


Features

1) Attrition Prediction

IBM HR Analytics dataset

Models: Logistic Regression, Random Forest, XGBoost

Explainability with SHAP


2) Absenteeism Analysis

UCI Absenteeism dataset

Classification of absenteeism levels (Low / Medium / High)

Clustering analysis with KMeans & PCA


3) Resume Classification

TF-IDF + Deep Learning (Keras/TensorFlow)

Multi-class resume categorization

Models stored via Git LFS (.h5 + .pkl)


4) Streamlit Dashboard

Modular tabs (attrition_tab.py, absenteeism_tab.py, resume_tab.py)

Interactive visualizations with Plotly & Seaborn

Upload your own dataset or resume for live predictions

Project Structure
SmartHR/
 ├── data/               # Datasets (CSV) – ignored in Git
 ├── models_tf/          # Trained ML models (stored via Git LFS)
 ├── modules/            # Core ML pipelines
 ├── tabs/               # Streamlit UI tabs
 ├── training/           # Model training scripts
 ├── main_app.py         # Streamlit app entry point
 ├── requirements.txt    # Dependencies
 └── README.md           # Project documentation



The project is accessible at the following link: https://smarthr-4btvoahgerwoxfokxwd6u9.streamlit.app/ .

USERNAME: admin
PASSWORD: 1234

In case you want to integrate other features or imporve the content of this one, you can access it by following the steps below:

Installation

Clone the repository:

git clone https://github.com/GerardMushi/SmartHR.git
cd SmartHR


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run main_app.py



Technologies Used

Python (pandas, numpy, scikit-learn, matplotlib, seaborn, shap)

Machine Learning (Random Forest, XGBoost, Logistic Regression, KMeans, PCA)

Deep Learning (Keras / TensorFlow for resume classification)

NLP (TF-IDF, embeddings, vectorization)

Streamlit (interactive dashboard)

License

This project is licensed under the MIT License – feel free to use and adapt.SmartHR – AI-Powered HR Analytics Platform
