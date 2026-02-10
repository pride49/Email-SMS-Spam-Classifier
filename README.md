# 📩 Email / SMS Spam Classifier

A modern **Machine Learning + NLP powered web app** that detects whether a message is **Spam or Not Spam** in real-time.

Built with **Streamlit**, this project combines intelligent text processing with a clean, animated, and professional UI for an interactive user experience.

---

## 🚀 Demo Features

✨ Animated gradient background
✨ Glassmorphism modern UI
✨ Real-time spam detection
✨ NLP text preprocessing
✨ TF-IDF vectorization
✨ Machine Learning classification
✨ Instant prediction with clean visuals
✨ Beginner-friendly + deployable

---

## 🧠 How it Works

1. User enters an Email/SMS message
2. Text is preprocessed using NLP:

   * Lowercasing
   * Tokenization
   * Stopword removal
   * Stemming
3. Converted to numerical features using **TF-IDF**
4. Trained ML model predicts:

   * 🚨 Spam
   * ✅ Not Spam

---

## 🛠 Tech Stack

* Python
* Streamlit
* Scikit-learn
* NLTK
* TF-IDF Vectorizer
* Machine Learning Models
* Pickle (model serialization)

---

## 📂 Project Structure

```
sms-spam-classifier/
│── app.py
│── model.pkl
│── vectorizer.pkl
│── requirements.txt
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

or manually:

```bash
pip install streamlit scikit-learn nltk
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

## 📸 Preview

Modern animated interface with clean design and instant predictions.

---

## 🎯 Use Cases

* Email spam filtering
* SMS scam detection
* NLP learning project
* ML beginner portfolio project
* Streamlit deployment demo

---

## 🌟 Future Improvements

* Probability score display
* Upload CSV messages
* Model comparison
* Dark/Light theme toggle
* Cloud deployment

---

## 👨‍💻 Author

Made with ❤️ using Python & Machine Learning
