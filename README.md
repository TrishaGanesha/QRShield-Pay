# 🔐 QRShield Pay

## 📌 Overview
QRShield Pay is a secure QR-based payment simulation system with encryption, digital signature verification, and rule-based fraud detection.

---

## 🚀 Features
- QR code-based transaction generation
- Fernet encryption for data security
- RSA digital signature verification
- Multi-factor fraud detection system
- Risk classification (Low / Medium / High)
- Clean Gradio UI

---

## 🧠 Fraud Detection Logic
The system evaluates:
- Transaction amount
- Time of transaction
- Location risk
- Device type
- Transaction frequency

Final output:
- LOW RISK → Approved
- MEDIUM RISK → Suspicious
- HIGH RISK → Blocked

---

## 🛠 Tech Stack
- Python
- Gradio
- Cryptography
- QRCode
- PIL

