📱 SMS Spam Classifier

This is a simple machine learning web application that classifies SMS text messages as **spam** or **not spam**. The app is built with Python using `scikit-learn` for model training and `Gradio` for an interactive interface.

---

## 🚀 Features

- Classifies SMS messages into `spam` or `ham` (not spam)
- Pre-trained model using TF-IDF + Multinomial Naive Bayes
- Interactive web UI with Gradio

---

## 🧠 Model Details

- **Algorithm:** Multinomial Naive Bayes
- **Text Vectorization:** TF-IDF with English stopword removal
- **Training/Test Split:** 67% training, 33% testing (stratified)
- **Dataset:** `SMSSpamCollection.csv` with labeled messages

---

## 📂 Dataset Format

Make sure your CSV file `SMSSpamCollection.csv` has the following structure:

| label | text |
|-------|------|
| ham   | Hey, how are you? |
| spam  | WINNER! You have won a free cruise... |

---

