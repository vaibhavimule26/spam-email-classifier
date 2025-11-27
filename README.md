📂 Project Files
Spam_Email_Classifier.ipynb     → Complete notebook with code & output
spam_classifier_model.pkl       → Saved trained ML model
tfidf_vectorizer.pkl            → Saved TF-IDF vectorizer
README.md                       → Project explanation

🚀 Project Overview
This model analyzes text messages and predicts whether they are spam or ham (not spam).

It uses:
TF-IDF Vectorization for converting text into numerical features
Multinomial Naive Bayes for classification
The dataset used is the SMS Spam Collection Dataset from UCI ML Repository.

📊 Model Accuracy
Accuracy: 97.8%
The model performs excellently in detecting spam messages with high precision.

🔧 Technologies Used
Python
Scikit-learn
Pandas & NumPy
TF-IDF Vectorizer
Multinomial Naive Bayes
Google Colab

🧪 Sample Prediction Code
Use this to test any message:

sample = ["You won $1000 cash prize! Click to claim"]
sample_tfidf = vectorizer.transform(sample)
prediction = model.predict(sample_tfidf)[0]

if prediction == 1:
    print("Message is SPAM")
else:
    print("Message is NOT SPAM")

📘 How to Use This Project
Upload the notebook to Google Colab
Run all cells
Use the prediction section to test your own messages
Use the saved .pkl files for deployment or reuse

👩‍💻 Author
Vaibhavi Mule
AI/ML Intern
