# 🔐 QRShield Pay

## 📌 Overview
QRShield Pay is a secure QR-based payment simulation system that integrates encryption, digital signatures, and rule-based fraud detection.

---

## 🚀 Features
- QR code generation for transactions
- AES-style encryption (Fernet)
- RSA digital signature verification
- Rule-based fraud detection system
- Risk classification (Low / Medium / High)
- Clean Gradio UI for simulation

---

## 🧠 Fraud Detection Logic
The system evaluates transactions using multiple factors:

- Transaction amount
- Time of transaction
- Location (simulated)
- Device type
- Transaction frequency

Based on these, it assigns a risk score and classifies:
- LOW RISK → Approved
- MEDIUM RISK → Warning / OTP simulation
- HIGH RISK → Blocked

---

## 🛠 Tech Stack
- Python
- Gradio
- Cryptography (Fernet + RSA)
- QRCode library
- OpenCV (QR handling)

---

## ▶ How to Run

```bash
pip install -r requirements.txt
python app.py
