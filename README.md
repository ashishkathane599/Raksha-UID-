
🛡️ RakshaUID

AI-Powered Identity Defense & Aadhaar Fraud Detection System

> A multi-layered AI verification engine combining Deep Learning, Biometric Authentication, OCR Intelligence, and Fraud Risk Modeling.




---

🌍 Overview

RakshaUID is an advanced AI-driven identity verification platform designed to detect forged or tampered Aadhaar documents through a strict multi-stage authentication pipeline.

The system integrates:

📄 Deep Learning-based Document Classification

👤 Biometric Face Verification

🔍 OCR + QR Code Cross Validation

🧠 Machine Learning Fraud Probability Scoring


This project demonstrates a complete AI system architecture — from computer vision and model training to backend API integration and interactive dashboard deployment.


---

🚀 Core Capabilities

🔐 Multi-Layer Security Architecture

RakshaUID uses a 3-Stage Verification Pipeline to eliminate identity fraud risks.


---

🧾 1️⃣ Document Authenticity Classification

CNN model trained using TensorFlow/Keras

Classifies uploaded image as:

✅ Valid Aadhaar

❌ Suspicious / Non-Aadhaar


Learns structural patterns of authentic documents


Model Type: Convolutional Neural Network
Output: Authenticity Confidence Score


---

👤 2️⃣ Biometric Face Verification

OpenCV (LBPH Face Recognizer)

Extracts ID photo

Compares against:

Live webcam capture

Uploaded user image


Generates similarity confidence %


Prevents:

Impersonation attacks

Photo replacement fraud



---

📄 3️⃣ OCR & QR Code Cross-Validation

Text extraction using PaddleOCR

QR code decoding

Field-level consistency check:

Name

Date of Birth

Aadhaar Number



Flags mismatched or tampered data.


---

🧠 AI-Based Fraud Detection Engine

Beyond rule-based checks, RakshaUID includes a Machine Learning Fraud Risk Model.

Features Analyzed:

Image tampering indicators

Face similarity confidence

OCR vs QR mismatch ratio

Document authenticity score

Metadata inconsistencies


Model Used:

Random Forest (Scikit-Learn)


Output:

Fraud Probability Score (%)

Risk Level Classification:

🟢 Low Risk

🟡 Medium Risk

🔴 High Risk




---

🏗️ System Architecture

User Upload
      ↓
CNN Document Classifier
      ↓
Face Verification Engine
      ↓
OCR Extraction
      ↓
QR Decoding
      ↓
Data Cross Validation
      ↓
Fraud Risk Model
      ↓
SQLite Secure Storage
      ↓
Dashboard Result Display


---

💻 Interactive Dashboard

Built using FastAPI + JavaScript

Real-time verification updates

Clean UI

Dark / Light Mode Support

Fraud risk visualization

Verification history tracking



---

🛠️ Technology Stack

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

📊 Sample Verification Output

Stage	Result	Confidence

Document Authenticity	Valid Aadhaar	97.8%
Face Match	Matched	88.4%
Data Cross Check	Consistent	✓
Fraud Probability	11%	Low Risk



---

🔒 Security Design Principles

Multi-factor identity verification

AI + Rule-based hybrid validation

Biometric authentication layer

Cross-source data consistency check

Secure local database storage

Duplicate identity prevention



---

📁 Project Structure

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

🧪 Engineering Highlights

Modular micro-service style design

Separated ML inference services

Clean API architecture (FastAPI)

Efficient model loading strategy

Secure record persistence

Real-time response pipeline



---

📈 Future Enhancements

Deepfake detection module

Blockchain-based verification logs

Cloud deployment (AWS / Azure)

Docker containerization

Aadhaar API integration (official verification layer)

REST API exposure for enterprise integration



---

⚡ Installation & Setup

git clone https://github.com/your-username/rakshauid.git
cd rakshauid
pip install -r requirements.txt
uvicorn main:app --reload


---

📌 What This Project Demonstrates

Applied Deep Learning

Computer Vision Engineering

OCR + QR Processing

Fraud Modeling

Full-stack Integration

Production-style API Design

Secure AI System Architecture



---

👨‍💻 Author

Ashish Kathane
AI Developer | Machine Learning Engineer

Focused on building intelligent, secure, real-world AI systems.


---

 do you want this to look like a hackathon winner, a startup MVP, or a job-landing portfolio project?

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