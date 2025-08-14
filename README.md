# 🖥️ Mistral OCR App

![Image](https://github.com/user-attachments/assets/27fba62f-d39e-4480-b0af-f9fed43dab81)

This project is a **Streamlit-based OCR (Optical Character Recognition)** application powered by **Mistral's OCR API**.  
It can process **PDF** and **image** files (local or via URL) to extract text content, and download results in multiple formats.

---

## ✨ Features
- **📂 File Support** — Works with PDF, JPG, JPEG, PNG.
- **🌐 URL & Local Upload** — Process files directly from URLs or upload from your device.
- **⚡ Mistral OCR API** — Uses the latest `mistral-ocr-latest` model for high-accuracy text extraction.
- **📜 Output Formats** — Download OCR results in:
  - JSON
  - Plain Text
  - Markdown
- **📸 Preview** — Displays the original file (PDF viewer or image preview) alongside OCR results.
- **🖥 Multiple Files** — Supports batch processing.

---

## 🛠 Tech Stack
- **[Streamlit](https://streamlit.io/)** – Web app framework
- **[Mistral API](https://mistral.ai/)** – OCR processing
- **Python** – Backend logic
- **Base64** – Encoding for embedded documents
- **Pillow** – Image handling

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/bevivek12/mistral_ocr.git
cd mistral-ocr-app
