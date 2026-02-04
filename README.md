# 🖼 Photo Reader (Image to Speech)

Photo Reader is a Python desktop application built using Tkinter that allows users to open an image file, extract text from it using Optical Character Recognition (OCR), and listen to the extracted text using text-to-speech (TTS).

The application is useful for reading text from images such as scanned documents, photos, or screenshots.

---

## ✨ Features

- 📂 Open image files (`.png`, `.jpg`, `.jpeg`)
- 🔍 Extract text from images using OCR (Tesseract)
- 🔊 Convert extracted text to speech
- 📝 Manual text input with speech output
- 🖥 Simple and lightweight Tkinter GUI
- 📊 Status bar for user feedback

---

## 🛠 Tech Stack

- **Python 3**
- **Tkinter** – GUI
- **Pillow (PIL)** – Image processing
- **pytesseract** – OCR (image to text)
- **Tesseract OCR Engine** – Backend OCR engine
- **pyttsx3** – Text-to-Speech (offline)

---

## 📁 Project Structure

photo-reader/
│
├── main.py # Main application file
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/photo-reader.git
cd photo-reader
```

### 2️⃣ Install Python Dependencies

```bash
pip install -r requirements.txt
```

## 🔧 Install Tesseract OCR (Required)

### Windows

1. Download from: https://github.com/UB-Mannheim/tesseract/wiki

2. Install it

3. Update the path in code if needed:```pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"```

### Linux (Ubuntu/Debian)

```bash
sudo apt install tesseract-ocr
```

## ▶️ How to Use

1. Run the application:```python main.py```
2. Click File → Open
3. Select an image containing text
4. The app extracts text and reads it aloud
5. Use More → Speaker to manually type text and listen
