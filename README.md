# 🛡️ Phishing URL Detection System

A simple yet powerful web app that detects whether a given URL is **legitimate** or a **phishing attempt** using a combination of **rule-based heuristics** and an optional **machine learning model**.

---

## 🚀 Try the App

👉 **[Click here to Launch the Web App](https://phishing-url-detection-system-byparvez.streamlit.app/)**  
_(No installation needed – runs entirely in the browser!)_

---

## 📌 Features

- ✅ Detect phishing URLs using:
  - Rule-based checks (domain structure, SSL, special characters, etc.)
  - Optional Machine Learning model (`RandomForestClassifier`)
- 🔍 Detailed breakdown of suspicious patterns
- 📈 Confidence score with reasons
- ⚡ Fast and interactive web interface using Streamlit

---

## 🧪 Sample URLs to Test

### 🔴 Phishing-like Examples
** http://paypal.account.verify-login.com **
** http://secure-appleid.apple.com.verify-login.tk **
** http://bankofamerica.verify-security-alert.cf ** 
** http://linkedin-connect-update.ml **


### 🟢 Legitimate Examples
** https://www.google.com **
** https://www.amazon.com **
** https://www.linkedin.com **


---

## 🛠️ Tech Stack

- **Python 3**
- **Streamlit** for the web app
- **scikit-learn** for ML
- **tldextract** for domain parsing
- **joblib** for model serialization

---

## 📁 How to Run Locally

bash
** git clone https://github.com/Jawaharparvez/Phishing-URL-Detection-System.git **
** cd Phishing-URL-Detection-System **
** pip install -r requirements.txt **
** streamlit run app.py **

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share!

---

## ✨ Author

Made with ❤️ by **Jawahar Parvez**
