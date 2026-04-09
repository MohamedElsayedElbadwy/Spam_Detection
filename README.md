
📧 Spam Detection using Naive Bayes

📌 Overview

This project is a Spam Detection System that classifies emails/messages into:
	•	Spam
	•	Not Spam (Ham)

The model is built using the Naive Bayes Algorithm, a popular technique in Machine Learning for text classification tasks.

⸻

🚀 Features
	•	Classifies text messages into spam or not spam
	•	Uses Natural Language Processing (NLP) techniques
	•	Simple and fast model (Naive Bayes)
	•	Easy to train with new data
	•	High performance on text classification tasks

⸻

🧠 How It Works
	1.	Data Collection
Dataset contains labeled messages (spam / ham)
	2.	Text Preprocessing
	•	Lowercasing
	•	Removing punctuation
	•	Removing stopwords
	•	Tokenization
	3.	Feature Extraction
	•	Convert text into numerical form using:
	•	CountVectorizer or TF-IDF
	4.	Model Training
	•	Train model using Naive Bayes
	5.	Prediction
	•	Input new message → model predicts spam or not

⸻

🛠️ Technologies Used
	•	Python 🐍
  • seaborn
  • pickle
	•	Scikit-learn
	•	Pandas

⸻

📂 Project Structure

spam-detection/
│
├── data/
│   └── spam.csv
│
├── model/
│   └── model.pkl
│
├── notebook/
│   └── training.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── predict.py
│
├── requirements.txt
└── README.md


⸻

⚙️ Installation

# Clone the repository
git clone https://github.com/your-username/spam-detection.git

# Go to project folder
cd spam-detection

# Install dependencies
pip install -r requirements.txt


⸻

▶️ Usage

1. Train the model

python train.py

2. Predict a message

python predict.py

Example:

Input: "Congratulations! You won a free ticket"
Output: Spam


⸻

📊 Dataset

You can use a public dataset like:
	•	SMS Spam Collection Dataset (from Kaggle)

⸻

💾 Model Saving

The trained model is saved using pickle:

import pickle

pickle.dump(model, open("model.pkl", "wb"))


