Cyberbullying Detection Using NLP

This project is a machine learning–based system designed to detect cyberbullying in text using Natural Language Processing (NLP). It analyzes user-generated content such as comments, messages, and posts to determine whether the text contains harmful or abusive language. The project also includes a Flask web application for real-time predictions.


🚀 Features
Detects cyberbullying text using ML classification
Real-time prediction through Flask web app
Clean and simple user interface
Text preprocessing pipeline (tokenization, stopwords, lemmatization)
Feature extraction using TF-IDF
Trained ML models like Logistic Regression / SVM / Naive Bayes


🧠 Technologies Used
Python
NLP (NLTK / spaCy)
Scikit-learn
Flask
HTML, CSS
Pickle (model saving)


Cyberbullying-Detection-NLP/
│
├── app.py                 # Flask backend
├── model.pkl              # Trained ML model
├── vectorizer.pkl         # TF-IDF vectorizer
├── requirements.txt       # Project dependencies
│
├── templates/
│     └── index.html       # Frontend UI
│
├── static/
│     └── style.css        # Styling
│
├── dataset/
│     └── cyberbullying.csv
│
└── README.md              # Project documentation

⚙️ How to Run Locally

1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the Flask app
python app.py

4️⃣ Open in browser
http://127.0.0.1:5000/


🧐 How It Works
User inputs text into the web interface.
The text is cleaned and preprocessed using NLP methods.
The TF-IDF vectorizer converts text into numerical features.
The ML model predicts bullying or not bullying.
The result is shown on the webpage.


🎯 Project Purpose
To build an intelligent system that helps identify abusive behavior online, promote awareness, and provide a tool for safer digital communication.

📌 Future Enhancements
Deep learning model (LSTM / BERT)
Multi-class bullying detection
API for integration with mobile/website
Improved UI with React/Next.js

🧑‍💻 Developed By
Mayur Desale
Full Stack Developer | Machine Learning Enthusiast

