
# Fake Resume Detection System (Deep Learning + NLP)

# Overview

The **Fake Resume Detection System** is an intelligent application that uses **Deep Learning and Natural Language Processing (NLP)** to analyze resumes and classify them as:

* ✅ Real Resume
* ⚠️ Suspicious Resume
* 🚫 Fake Resume

Unlike basic classifiers, this system combines **machine learning with rule-based validation** to provide not only predictions but also **explanations and confidence scores**, making it more transparent and reliable.

---

## 🚀 Features

### 🔍 Core Features

* Deep Learning-based classification using LSTM
* Multi-class output: Real / Fake / Suspicious
* Confidence score for predictions
* Text preprocessing using NLP techniques

### 🧠 Intelligent Analysis

* Keyword exaggeration detection (e.g., "expert", "master")
* Skill vs experience mismatch detection
* Duplicate content analysis
* Experience validation (e.g., unrealistic claims)

### 📊 Advanced Capabilities

* Resume scoring system (0–100%)
* Section-wise analysis (skills, experience, projects)
* Explanation generation (why a resume is fake/suspicious)
* Visual confidence graph

### 📁 Input Support

* Text input (manual)
* PDF resume parsing (optional)

### 💻 User Interaction

* Interactive input system (Colab-based)
* Real-time testing mode
* Simple UI (optional Streamlit integration)

---

## 🏗️ System Architecture

```
Resume Input (Text / PDF)
        ↓
Text Preprocessing (Cleaning + Tokenization)
        ↓
Feature Extraction (Sequences / Embeddings)
        ↓
Deep Learning Model (LSTM)
        ↓
Rule-Based Analysis
        ↓
Final Output:
- Classification (Real / Fake / Suspicious)
- Confidence Score
- Explanation Report
```

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* NLTK
* PyPDF2 (for PDF parsing)
* Matplotlib (for visualization)
* Streamlit (optional UI)

---

## 📂 Project Structure

```
Fake-Resume-Detection/
│
├── dataset/
│   └── resume_dataset.csv
│
├── model/
│   └── resume_model.h5
│
├── notebook/
│   └── fake_resume_detection.ipynb
│
├── app/
│   └── streamlit_app.py (optional)
│
├── utils/
│   ├── preprocessing.py
│   ├── analysis.py
│   └── prediction.py
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/fake-resume-detection.git
cd fake-resume-detection
```

### 2️⃣ Install Dependencies

```bash
pip install numpy pandas scikit-learn tensorflow nltk matplotlib PyPDF2
```

### 3️⃣ Run Project (Google Colab Recommended)

* Open notebook in Google Colab
* Run all cells step-by-step

---

## ▶️ Usage

### 🔹 Test with Custom Input

```python
resume = "I am expert in AI with 10 years experience..."
print(predict_resume(resume))
```

### 🔹 Full Analysis

```python
full_analysis(resume)
```

---

## 📊 Example Output

```
🧾 Resume Analysis Report

📌 Result: 🚫 Fake Resume
📊 Confidence: 0.81 (81%)

🔍 Issues Detected:
- Excessive use of exaggerated keywords
- Unrealistic experience claims
- Skill mismatch

📈 Additional Metrics:
- Keyword Score: High
- Duplication Score: Medium
```

---

## 🧪 Dataset

The system can be trained on:

* Real resumes (verified data)
* Fake resumes (generated or manipulated)
* Suspicious resumes (borderline cases)

> Note: A larger dataset improves model accuracy significantly.

---

## 🎯 Project Objectives

* Detect fake or exaggerated resumes using AI
* Improve hiring reliability
* Provide explainable AI-based decisions
* Combine deep learning with logical validation

---

## 🧠 Future Improvements

* Integration with BERT / Transformers
* Real-time web deployment
* Company database validation
* Resume authenticity scoring system
* API integration for HR systems

---

## 🎓 Academic Use

This project is designed for:

* Final Year Projects (FYP)
* Machine Learning / AI coursework
* NLP-based research demonstrations

---

## 👨‍💻 Author

**Aamir Naseer**
BS Computer Science (3rd Year)
Mirpur University of Science and Technology

---

## 📜 License

This project is for educational purposes only.
