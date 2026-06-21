# 🔐 CyberGuard Elite - Phishing Detection System

CyberGuard Elite is a Machine Learning-based phishing URL detection system that identifies malicious websites using URL feature analysis and threat intelligence.

## 🚀 Features

* Machine Learning-based URL classification
* 20 handcrafted phishing detection features
* Google Safe Browsing API integration
* Risk level assessment (CRITICAL, HIGH, MEDIUM, LOW)
* Interactive dashboard with analytics
* Scan history tracking
* Responsive cyber-themed UI
* Flask REST API backend

## 🛠️ Tech Stack

**Frontend**

* HTML
* CSS
* JavaScript
* Chart.js

**Backend**

* Flask
* Flask-CORS

**Machine Learning**

* Scikit-Learn
* NumPy
* Pickle

## 📂 Project Structure

```text
CyberGuard-Elite/
│
├── app.py
├── index.html
├── final_model.pkl
└── README.md
```

## ⚙️ Installation

```bash
pip install flask flask-cors numpy requests scikit-learn
```

## ▶️ Run the Project

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## 📡 API Endpoint

### Predict URL

```http
POST /predict
```

Request:

```json
{
  "url": "https://example.com"
}
```

## 🔍 Detection Features

* URL Length Analysis
* HTTPS Verification
* URL Shortener Detection
* Suspicious Keywords Detection
* IP Address Detection
* TLD Analysis
* Subdomain Analysis
* Redirect Detection
* Digit Ratio Analysis
* Query Parameter Analysis

## 🎯 Future Enhancements

* WHOIS Domain Age Analysis
* Database Integration
* User Authentication Backend
* Browser Extension Support
* Deep Learning-Based Detection

## 👩‍💻 Author

**T. Sujitha Mary**
Artificial Intelligence and Data Science
St. Joseph College of Engineering

---


