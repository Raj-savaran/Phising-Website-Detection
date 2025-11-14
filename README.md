# 🛡️ Phishing Website Detection System

A machine learning-powered web application to detect phishing websites using Python, Flask, and Jupyter Notebook.

## 🔍 Project Overview

This project helps users identify whether a given URL is **safe or phishing** using a trained ML model. It extracts features from the URL and predicts its legitimacy in real-time via a simple Flask web interface.

---

## 🇮🇳 Hindi Overview

Ye system user se URL leta hai aur Machine Learning model ke through batata hai ki wo **safe hai ya phishing**. Python, Flask aur Jupyter Notebook ka use karke banaya gaya hai.

---

## 🧠 Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Flask  
- Jupyter Notebook  
- HTML/CSS (optional for frontend)

---

## 📊 Machine Learning Model

- **Algorithm Used:** Random Forest / Decision Tree / Logistic Regression  
- **Features Extracted:**  
  - URL length  
  - Presence of '@' symbol  
  - Use of 'https'  
  - Domain age  
  - Number of subdomains  
- **Accuracy Achieved:** XX% (replace with your actual score)

---

## 🌐 Web App Functionality

- User inputs a URL  
- Backend extracts features  
- ML model predicts: **Safe** or **Phishing**  
- Result displayed on webpage

---

## 📁 Folder Structure

---

## 🚀 How to Run Locally

```bash
# Step 1: Create virtual environment
python -m venv env

# Step 2: Activate it
.\env\Scripts\activate

# Step 3: Install dependencies
pip install -r requirements.txt
pip install pandas numpy flask
pip install scikit-learn

# Step 4: Run the Flask app
python app.py
