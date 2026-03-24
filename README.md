📩 Spam Detection System
📌 Overview

This project is a Machine Learning-based SMS Spam Detection System that classifies messages as Spam or Ham (Not Spam). It uses Natural Language Processing (NLP) techniques and a Logistic Regression model to analyze and predict message content.

An interactive web interface is built using Streamlit for real-time predictions.

🚀 Features
● Classifies SMS messages as Spam or Ham
● Real-time prediction using a simple UI
● Text preprocessing (cleaning, tokenization, stopword removal, lemmatization)
● TF-IDF vectorization for feature extraction
● Lightweight and fast prediction using Logistic Regression

🛠️ Tech Stack
● Python
● Machine Learning (Logistic Regression)
● Natural Language Processing (NLTK)
● Streamlit (Web Interface)
● TF-IDF Vectorizer
● Joblib (Model Saving & Loading)

📂 Project Structure
├── app.py
├── logistic_regression_sms_spam_model.pkl
├── tfidf_vectorizer.pkl
├── label_encoder.pkl
├── requirements.txt
└── README.md

⚙️ Installation
1) Clone the repository
git clone https://github.com/your-username/spam-detection-system.git
cd spam-detection-system

2)Install dependencies
pip install -r requirements.txt

3)Run the application
streamlit run app.py

🧠 How It Works
1)Input: User enters an SMS message
2)Preprocessing:
● Removes special characters
● Tokenizes text
● Removes stopwords
● Applies lemmatization
3)Vectorization: Converts text into numerical form using TF-IDF
4)Prediction: Logistic Regression model predicts Spam or Ham
5)Output: Result displayed on the Streamlit UI

📊 Model Details
Algorithm: Logistic Regression
Feature Extraction: TF-IDF
Text Processing: NLTK
Output Classes: Spam / Ham

🔗 Future Improvements
Add deep learning models (LSTM/BERT)
Improve accuracy with larger datasets
Deploy using cloud platforms
Add multilingual support

👨‍💻 Author
Manoj R

GitHub: https://github.com/Manojr17
LinkedIn: https://www.linkedin.com/in/manoj0902
