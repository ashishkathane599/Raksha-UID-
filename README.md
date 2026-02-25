
🛡️ RakshaUID — Identity Defense System

> AI-Powered Aadhaar Fraud Detection & Identity Verification Platform



RakshaUID is an advanced AI-driven identity verification system designed to detect Aadhaar fraud using a strict multi-layered security workflow.
It integrates Deep Learning (CNN), OCR, Computer Vision, and Biometric Face Verification to ensure only authentic identities are approved.


---

🎯 Project Vision

To build a secure, automated, and intelligent identity verification system capable of detecting forged Aadhaar documents using AI-based fraud analysis.


---

🔐 GPRM Framework

G — Goal

Develop a robust identity authentication system that:

Detects fake Aadhaar documents

Verifies biometric identity

Cross-validates extracted data

Assigns fraud probability scores

Prevents duplicate identity verification



---

P — Problem

Aadhaar fraud and identity forgery are rising due to:

Tampered ID card images

Fake printed documents

QR code manipulation

Face mismatch attacks

Manual verification loopholes


Traditional verification systems lack:

Automated forensic analysis

Biometric matching

ML-based fraud probability scoring



---

R — Resolution (Solution Architecture)

RakshaUID solves the problem using a strict 3-Stage Verification Workflow:

🔍 Stage 1 — Document Authenticity Analysis

CNN model (TensorFlow/Keras)

Classifies image as:

Valid Aadhaar

Non-Aadhaar / Suspicious Document



👤 Stage 2 — Biometric Face Verification

OpenCV LBPH Face Recognizer

Compares:

Aadhaar card photo

Live webcam / uploaded user photo


Generates confidence score


📄 Stage 3 — Data & QR Cross Validation

Extracts text using PaddleOCR

Decodes Aadhaar QR code

Cross-checks:

Name

DOB

Aadhaar number


Flags inconsistencies



---

🧠 M — Mechanism (Fraud Detection Engine)

RakshaUID includes an AI-powered fraud engine that:

Detects image tampering traces

Checks metadata inconsistencies

Calculates ML-based fraud probability

Uses Random Forest (Scikit-Learn)

Assigns Risk Score (Low / Medium / High)



---

🚀 Key Features

✅ 3-Stage Secure Verification Pipeline

✅ CNN-Based Aadhaar Classification

✅ Biometric Face Match (LBPH)

✅ OCR + QR Data Cross Validation

✅ ML Fraud Probability Scoring

✅ SQLite Secure Storage

✅ Duplicate Identity Detection

✅ Real-time Verification Dashboard

✅ Dark / Light Mode Interface



---

🏗️ System Architecture

User Upload
     ↓
CNN Document Classifier
     ↓
Face Verification Engine
     ↓
OCR + QR Cross Validation
     ↓
Fraud Probability Model
     ↓
Secure Database Storage
     ↓
Dashboard Result Display


---

🛠️ Tech Stack

🔹 Backend

Python 3.10+

FastAPI

Uvicorn


🔹 Deep Learning

TensorFlow

Keras (CNN Classification)


🔹 Computer Vision

OpenCV (opencv-contrib-python)

LBPH Face Recognizer

PaddleOCR


🔹 Machine Learning

Scikit-Learn (Random Forest)


🔹 Database

SQLite


🔹 Frontend

HTML5

CSS3

JavaScript (Fetch API)



---

📂 Project Structure

rakshauid/
│
├── models/
│   ├── cnn_model.h5
│   ├── fraud_model.pkl
│
├── services/
│   ├── document_classifier.py
│   ├── face_verification.py
│   ├── ocr_engine.py
│   ├── fraud_detector.py
│
├── database/
│   ├── verification.db
│
├── static/
├── templates/
│
├── main.py
├── requirements.txt
└── README.md


---

📊 Output Example

Stage	Result	Confidence

Document Check	Valid Aadhaar	98%
Face Match	Matched	87%
Data Validation	Consistent	✓
Fraud Risk Score	Low Risk	12%



---

🔒 Security Highlights

Multi-layer verification

Cross-source validation

Biometric confirmation

AI-based fraud scoring

Secure local database storage

Duplicate identity detection



---

📈 Future Enhancements

Aadhaar API integration (Government Auth Layer)

Blockchain-based verification logs

Cloud deployment (AWS / Azure)

Mobile app integration

Advanced deepfake detection



---

⚡ Installation

git clone https://github.com/ashishkathane599/Raksha-UID-
cd rakshauid
pip install -r requirements.txt
uvicorn main:app --reload


---

🧑‍💻 Author

Ashish Kathane
AI Developer | Machine Learning Enthusiast
Focused on building secure AI-driven systems.


---