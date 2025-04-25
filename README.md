# 🧠 OCR API with FastAPI

This is a simple FastAPI application that provides an OCR (Optical Character Recognition) endpoint. It uses `pytesseract` to extract text from uploaded image files.

## 🚀 Features

- Accepts image uploads via a POST request.
- Processes the image and returns the extracted text using Tesseract OCR.
- Written in Python 3.11.

## 📦 Requirements

Make sure you have **Python 3.11** installed.

First, install the required Python dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run the App
Run the FastAPI server with:

```bash
uvicorn main:app --reload
```
Replace main with your filename if it's different.