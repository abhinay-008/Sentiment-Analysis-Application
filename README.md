# Sentiment Analysis Application using Python

A simple Machine Learning based web application that predicts whether a given text is Positive, Negative, or Neutral.

The project was developed using Python, Scikit-learn, and Streamlit.

---

# Features

- Real-time sentiment prediction.
- Positive, Negative, and Neutral classification
- Color-coded output interface
- Interactive Streamlit web application

---

# Technologies Used

- Python
- Natural Language Processing (NLP)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Streamlit
- Google Colab
- Jupyter Notebook

---

# Dataset Used

Twitter Sentiment Dataset from Kaggle containing 50,000+ labelled tweets.

Dataset contains:
- Positive tweets
- Negative tweets
- Neutral tweets

---

# Machine Learning Workflow

1. Import dataset
2. Perform text preprocessing
3. Convert text into numerical vectors using TF-IDF
4. Split dataset into training and testing data
5. Train Logistic Regression model
6. Evaluate model accuracy
7. Save trained model using Pickle
8. Build frontend using Streamlit
9. Predict sentiment from user input

---

# Project Structure

```text
project/
│
├── app.py
├── sentiment_model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

# How to Run

Run these commands from the project folder.

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
streamlit run app.py
```


