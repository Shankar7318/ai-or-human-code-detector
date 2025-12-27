# 🤖 Human vs AI Code Detection App

![Streamlit](https://img.shields.io/badge/Streamlit-1.28.0-FF4B4B)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A **machine learning–powered web application** that identifies whether a Python code snippet is **human-written or AI-generated**.  
Built using **Streamlit**, trained on **1,500 labeled samples**, and designed for interpretability and ease of use.

---

## ✨ Features

### 🤖 Dual Model Support
- Random Forest Classifier  
- Logistic Regression  

### 📝 Multiple Input Methods
- Paste code directly  
- Upload `.py` files  
- Use preloaded sample examples  

### 📊 Detailed Analysis
- Probability scores with visual indicators  
- Feature-level breakdown  
- AI reasoning insights  

### 🎯 Sample Testing
- Quickly test with curated examples  

### 🎨 User-Friendly Interface
- Clean, interactive UI  
- Visual confidence indicators  

---

## 🚀 Quick Start

### ✅ Prerequisites
- Python **3.8+**
- `pip`

---

## 🔧 Installation

### 1️⃣ Clone the repository
```bash
git clone <repository-url>
cd human-ai-code-detection
```
### 2️⃣ Create a virtual environment
```
python -m venv venv
source venv/bin/activate     #Windows: venv\Scripts\activate
```
### 3️⃣ Install dependencies
```
pip install -r requirements.txt
```

### ▶️ Run the Application
```
streamlit run app.py
```
### 📁 Project Structure
```
human-ai-code-detection/
├── app.py
├── requirements.txt
├── README.md
├── human or ai code detection.ipynb
├── ai_vs_human_code_dataset.csv
├── rf_model.pkl
├── lr_model.pkl
└── scaler.pkl
```


### 📈 Future Enhancements
```
Multi-language code detection

AST-based analysis

Real-time model retraining

REST API deployment

Browser extension support

Historical trend analytics
```
