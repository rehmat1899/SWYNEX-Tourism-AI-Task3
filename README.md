# AI-Based Smart Tourism Question Classification System

## Project Overview
This project is an AI-based Smart Tourism Question Classification System that automatically classifies tourism-related questions into five categories.

## Categories
- Attractions
- Routes
- Accommodation
- Weather
- Safety

## Intelligent Features
- Predicts the category of a tourism question.
- Displays a confidence score in percentage.
- Shows High, Medium, or Low confidence levels.
- Handles empty input with an error message.
- Includes model evaluation and failure-case examples.
- Provides an interactive notebook demo.

## Technologies Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes

## Dataset
The dataset contains 100 sample tourism questions, with 20 questions in each category.

## Model Evaluation
- Training Questions: 80
- Testing Questions: 20
- Test Accuracy: 90%
- Correct Predictions: 18
- Incorrect Predictions: 2

The evaluation is based on the current test split. It does not guarantee the same accuracy on real-world tourism questions.

## Failure Cases
Two incorrect predictions were identified:
1. "Can I book a room in Gilgit?" — Actual: Accommodation; Predicted: Attractions.
2. "Where are the best resorts in Kashmir?" — Actual: Accommodation; Predicted: Attractions.

## Project Files
- `SWYNEX_Tourism_AI_Task3.ipynb` — Main notebook.
- `tourism_model.pkl` — Trained machine learning model.
- `tfidf_vectorizer.pkl` — Saved TF-IDF vectorizer.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Enter a tourism question.
4. View the predicted category and confidence score.

## Conclusion
This project demonstrates an intelligent tourism question classifier with confidence scoring, input validation, and model evaluation.
# SWYNEX-Tourism-AI-Task3
AI-Based Smart Tourism Question Classification System with Confidence Score and Evaluation
