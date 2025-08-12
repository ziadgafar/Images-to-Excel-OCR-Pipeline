# 📂 ZIP-to-Excel OCR Pipeline  

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)  
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv)  
![Tesseract OCR](https://img.shields.io/badge/Tesseract-OCR-orange?logo=google)  
![License](https://img.shields.io/badge/License-MIT-lightgrey)  

---

## 📜 Overview  
The **ZIP-to-Excel OCR Pipeline** is an automation tool that:  
1. Extracts images from ZIP files.  
2. Preprocesses them with **OpenCV** for improved OCR accuracy.  
3. Uses **Tesseract OCR** to extract text.  
4. Outputs everything into a **clean Excel sheet**.  

**Why it matters:** Cuts manual transcription from **hours to minutes** for large datasets.  

---

## 🎯 Features  
✅ **ZIP Extraction** – Bulk unpacking of image files.  
✅ **Smart Preprocessing** – Grayscale, thresholding, noise removal.  
✅ **Accurate OCR** – Tesseract-based multilingual recognition.  
✅ **Excel Export** – Structured data ready for analysis.  
✅ **Scalable** – Works for dozens or thousands of images.  

---

## 🛠️ Tech Stack  
- **Python 3.x**  
- **OpenCV** – Image preprocessing  
- **Tesseract OCR** – Text recognition  
- **Pandas** – Excel export  
- **Jupyter Notebook** – Development & reproducibility  

---

## 📦 Installation  

```bash
# Clone repository
git clone https://github.com/yourusername/zip-to-excel-ocr.git
cd zip-to-excel-ocr

# Install dependencies
pip install -r requirements.txt

# Install Tesseract (Ubuntu/Debian example)
sudo apt install tesseract-ocr
