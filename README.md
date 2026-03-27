# AI/ML Internship Tasks

This repository contains AI/ML tasks completed as part of my AI/ML Internship.

## Task 1: Iris Dataset Exploration
Objective:
How to load, inspect, and visualize a dataset to understand data trends and distributions..

Dataset:
Iris Dataset used.

Model Used:
Not applicable, this task focuses on data exploration and visualization.

Results:
Successfully visualized feature relationships using scatter plots, histograms, and box plots. Gained insights into feature distributions and potential outliers in the dataset.


## Task 2: House Price Prediction

Objective:
Predict house prices based on features like area, bedrooms, bathrooms, etc.

Dataset:
House Price Prediction Dataset

Model Used:
Linear Regression

Results:
Model was trained and evaluated using R² score.


## Task 3: Heart Disease Prediction

Objective:
Predict whether a patient has heart disease.

Dataset:
HeartDiseaseTrain-Test Dataset

Model Used:
Logistic Regression

Results:
Model achieved good accuracy and ROC performance.


## Task 4: End-to-End ML Pipeline for Customer Churn

Objective:
Build a reusable machine learning pipeline to predict customer churn using Scikit-learn.

Dataset:
Telco Churn Dataset

Model Used:

Logistic Regression  
Random Forest  
GridSearchCV for hyperparameter tuning  

Approach:  
Data preprocessing using Pipeline (encoding + scaling). 
Handled categorical and numerical features.
Trained multiple models.
Performed hyperparameter tuning using GridSearchCV.
Saved final pipeline using joblib.

Results: 
The trained pipeline achieved good prediction performance. Random Forest performed better compared to Logistic Regression in terms of accuracy.

Model File:
churn_model.pkl (saved pipeline)  


## Task 5: Context-Aware Chatbot using RAG

Objective:
Develop a chatbot that retrieves relevant information from documents and answers user queries using LangChain and Retrieval-Augmented Generation (RAG).

Dataset:
Custom text documents used as a knowledge base.

Model/Tools Used:
LangChain, FAISS Vector Store, OpenAI or LLM, Streamlit

Approach:
Documents were loaded and split into smaller chunks. Embeddings were generated for each chunk and stored in a FAISS vector database. When a user asks a question, the system retrieves relevant chunks based on similarity search. The retrieved context is then passed to the LLM to generate a final response. The chatbot interface was deployed using Streamlit.

Results:
The chatbot successfully answers user queries based on the provided knowledge base and maintains contextual understanding during conversation.


## Task 6: Auto Tagging Support Tickets using LLM

Objective:
Automatically classify support tickets into relevant categories using Large Language Models.

Dataset:
Free-text support ticket dataset

Model/Technique Used:
OpenAI or LLM, prompt engineering, zero-shot and few-shot learning

Approach:
Prompts were designed to classify support tickets into relevant categories. Zero-shot prompting was used initially without examples. Few-shot prompting was then applied by including example inputs and outputs to improve accuracy. The model generated the top 3 most relevant tags for each ticket.

Results:
Few-shot prompting improved the accuracy of tag predictions compared to zero-shot prompting. The model successfully identified multiple relevant categories for each ticket.
