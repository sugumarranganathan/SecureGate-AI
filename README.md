#SecureGate-AI

https://colab.research.google.com/drive/1545N8sagcHlyCOp4pSPddM11Ed2oiX2w#scrollTo=TYEfILB0bF5e
(upload image option only)

https://colab.research.google.com/drive/1K_Mu2gcfGgWDn93grAnWx5e3u-nHZR5r#scrollTo=aYJysi1Xb2J2
(upload image and direct live webcam option)


# SecureGate AI

### AI-Powered Apartment Security & Visitor Verification System

SecureGate AI is an Artificial Intelligence-based security solution that uses Face Recognition technology to identify residents and verify visitors in apartment communities. The system automatically grants or denies access based on facial matching, helping improve security and reduce manual verification efforts.

---

##  Project Overview

Traditional visitor verification in apartments is often manual, time-consuming, and prone to human error. SecureGate AI automates this process using AI-powered facial recognition to identify authorized residents and detect unauthorized visitors in real time.

---

##  Problem Statement

Manual visitor verification can lead to delays, mistakes, and security risks. Security personnel may find it difficult to accurately identify every resident and visitor, especially during busy hours.

---

##  Solution

SecureGate AI uses the FaceNet deep learning model to recognize faces and verify identities automatically. The system compares uploaded visitor images with registered resident data and instantly determines whether access should be granted or denied.

---

##  How It Works

### Step 1: Upload Visitor Photo
The user uploads a visitor or resident image through the application.

### Step 2: Face Detection
The system detects and extracts the face from the uploaded image.

### Step 3: Face Recognition
FaceNet generates a unique facial embedding for the detected face.

### Step 4: Resident Identification
The embedding is compared against registered resident embeddings stored in the database.

### Step 5: Access Decision
- ✅ Authorized Resident → Access Granted
- ❌ Unauthorized Visitor → Access Denied

### Step 6: Result Display
The system displays:
- Resident Name
- Apartment Number
- Authorization Status
- Confidence Score

---

##  Features

- 🔍 Face Recognition using FaceNet
- 👤 Resident Identification
- 🚪 Visitor Verification
- 🏢 Apartment Mapping
- ✅ Access Control Decision
- ⚡ Real-Time Processing
- 🤖 AI-Powered Security

---

## 🧠 AI Model Used

### FaceNet

FaceNet is a deep learning-based face recognition model that converts facial images into numerical embeddings. These embeddings are compared with registered resident embeddings to determine identity and authorization status.

**Model Details**
- Model: FaceNet
- Task: Face Recognition
- Technique: Deep Metric Learning
- Output: Face Embeddings
- Application: Resident Identification & Visitor Verification

---

## 🛠️ Technologies Used

| Component | Technology |
|------------|------------|
| Programming Language | Python |
| AI Model | FaceNet |
| User Interface | Gradio |
| Image Processing | OpenCV, Pillow |
| Numerical Computing | NumPy |
| Face Detection | MTCNN |
| Development Environment | Google Colab |

---

## 📂 Project Structure

```text
SecureGate-AI/
│
├── securegate_ai.py
├── SecureGate_AI.ipynb
├── README.md
└── requirements.txt
```

---

## 📷 Sample Results

### Authorized Resident
- Access Granted
- Resident Name Displayed
- Apartment Number Displayed
- Confidence Score Displayed

### Unauthorized Visitor
- Access Denied
- Visitor Flagged as Unauthorized
- Similar Match Information Displayed

---

## 🎯 Benefits

- Improved Apartment Security
- Faster Visitor Verification
- Reduced Manual Effort
- Accurate Resident Identification
- Real-Time Access Control
- Prevention of Unauthorized Entry

---

## ▶️ Running the Project

```bash
pip install -r requirements.txt
python securegate_ai.py
```

---

### ⭐ SecureGate AI – AI-Powered Apartment Security & Visitor Verification System
