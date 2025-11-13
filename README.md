SMS Scam / Spam Detection

This project focuses on building a Machine Learning-based SMS Scam & Spam Detection system that classifies text messages as Spam or Ham (Not Spam).
It uses Natural Language Processing (NLP) techniques and supervised learning models to accurately analyze message content and identify potential fraud or scam messages.

📊 Dataset

The dataset used in this project is the SMS Spam Collection Dataset from the UCI Machine Learning Repository.
It contains 5,574 SMS messages, each labeled as spam or ham.

🔗 Dataset Link:
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

The dataset file (sms_spam_dataset.csv) includes:

label → 1 for spam, 0 for ham

text → SMS message content

📦 Requirements

To run this project, install the following dependencies:

Python 3.x

pandas

numpy

scikit-learn

nltk

matplotlib

streamlit (if running the web app version)

Install all requirements using:

pip install pandas numpy scikit-learn nltk matplotlib streamlit

▶️ Usage

Clone the repository or download the project files:

git clone https://github.com/your-username/sms-spam-detection.git


Add the dataset (sms_spam_dataset.csv) to the project directory.

Run the main ML script to train and evaluate the model:

python sms_spam_detection.py


The script performs:

Data loading

Text preprocessing

TF-IDF vectorization

Model training

Performance evaluation

To test new SMS messages, modify the predict() function in the script or run the Streamlit app:

streamlit run app.py

📈 Results

The trained model achieved strong performance on the test dataset:

Metric	Score
Accuracy	97.10 %
Precision	100 %
Recall	76.19 %
F1-score	86.49 %

This indicates that the model is highly precise and effective at identifying scam/spam messages while keeping false positives low.

🤝 Contributing

Contributions are always welcome!
Feel free to:

Submit issues

Create pull requests

Suggest improvements

Extend the dataset or model
