# Explainable Machine Learning for Fake Job Advertisement Detection

## Project Overview
This project uses machine learning to classify job advertisements as **genuine** or **potentially fraudulent**. It also uses LIME (Local Interpretable Model-Agnostic Explanations) to explain which words influence the model's prediction.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF
- Logistic Regression
- Multinomial Naive Bayes
- LIME
- Gradio
- Google Colab

## Key Features
- Job advertisement text analysis
- Genuine or potentially fraudulent prediction
- Prediction probability estimates
- Machine learning model evaluation
- Comparison of Logistic Regression and Naive Bayes
- LIME-based explanation of influential words
- Interactive web application using Gradio

## Dataset
**Real or Fake? Fake Job Posting Prediction**

Source: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

## Model Evaluation
The models are evaluated using accuracy, precision, recall, and F1-score. Because fraudulent advertisements are less common than genuine advertisements in the dataset, fraud detection recall and F1-score are important evaluation measures.

## How to Run
1. Open `Fake_Job_Detection_Project (2).ipynb` in Google Colab.
2. Download the dataset from Kaggle.
3. Upload the dataset to Google Colab or update the notebook's dataset path.
4. Run the notebook cells in order.
5. Launch the Gradio application to test job advertisements.

## Disclaimer
Predictions are model estimates, not proof that a job advertisement is genuine or fraudulent. Always verify job offers through trusted sources.
