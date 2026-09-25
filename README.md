<<<<<<< HEAD
# AuraMed
=======
# AuraMed AI - Medical Document OCR & PHR Platform

An enterprise-grade Medical Document Processing (OCR) & Personal Health Records (PHR) web application powered by **Python FastAPI** and **EasyOCR (PyTorch)**.

![Medical OCR Dashboard](https://raw.githubusercontent.com/placeholder/ocr-demo.png)

## Features
- 📜 **Medical OCR Engine:** Scans doctor prescriptions, lab test reports, and billing receipts.
- 🎯 **Bounding Box Visualizer:** Real-time percentage-based bounding box overlays matching exact document coordinates.
- 📊 **Structured Entity Extraction:** Normalizes medical terms, patient IDs, provider names, and billing totals.
- 🔒 **HIPAA-Ready Architecture:** Designed for patient data isolation, RAG LLM integration, and cross-platform Flutter mobile app integration.

## Project Structure
```
d:/OCr/
├── index.html       # Interactive Web Frontend & Presentation Deck
├── style.css        # Sleek dark mode styling
├── app.js           # Dynamic UI interaction & API fetch logic
├── server.py        # Python FastAPI & EasyOCR Real Backend Engine
├── requirements.txt # Python dependencies
└── .gitignore       # Git ignore rules
```

## Quick Start Guide

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run Python OCR Server
```bash
python -m uvicorn server:app --host 0.0.0.0 --port 8000
```

### 3. Open Web Application
Open [http://localhost:8000](http://localhost:8000) in your web browser. Upload any medical document/receipt and click **"Run AI OCR Extraction"**.
>>>>>>> 5a74410 (Initial commit - Medical OCR & PHR Platform)
