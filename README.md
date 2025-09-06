# 🛡️ Sensitive Information Redaction Tool  

This project is a *cybersecurity-focused tool* that automatically detects and redacts *sensitive information* from text and images. It leverages *OCR (Tesseract)* for text extraction and *BERT Named Entity Recognition (NER)* for AI-powered detection of personal data.  

The purpose of this tool is to *protect privacy and data confidentiality* when handling documents, IDs, or text data.  

---

## 📖 Project Explanation  

### 🔹 Problem Statement  
In today’s digital world, documents and text often contain *personal information* like names, emails, phone numbers, addresses, financial details, and organizational data.  
Sharing such files without protection may lead to *identity theft, fraud, or data misuse*.  

### 🔹 Solution  
This project provides an *automated redaction system* that:  
- Detects sensitive information using *AI (NER model)* and *regex rules*.  
- Masks/redacts such information in both *plain text* and *scanned images*.  
- Provides a *redaction log* explaining what was removed and why.  

### 🔹 How It Works  
1. *Text Mode* → User pastes text → The tool scans each word → Sensitive words are replaced with [REDACTED].  
2. *Image Mode* → User uploads an image → Tesseract OCR extracts text → Sensitive words are detected and blacked out in the image.  

---

## ⚙️ Tech Stack  
- *Python* – Main programming language  
- *OpenCV* – For image processing  
- *Pytesseract* – OCR for text extraction from images  
- *Transformers (BERT)* – For AI-based Named Entity Recognition  
- *Regex* – For detecting patterns (emails, dates, financial data)  
- *Gradio* – For creating a user-friendly web UI  

---

## 🚀 Features  
✅ AI-based detection of *names, organizations, locations*  
✅ Regex-based detection of *emails, dates, financial info*  
✅ Works with *text* and *image* inputs  
✅ Generates a *redaction log* for transparency  
✅ Simple *web interface*  

---

## 🖼️ Example  

### Input Text
