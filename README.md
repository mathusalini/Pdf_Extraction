# Pdf_Extraction

This script is designed for **universal text extraction** from documents.  
It supports both **PDF files** and **image files (JPG/PNG)**.  

- For **PDFs**, it first tries to extract text directly using `pdfplumber`.  
- If no text is found (like in scanned or photo-based PDFs), it automatically switches to **OCR** using `pytesseract` and `pdf2image`.  
- For **image files**, it directly applies **OCR** with `pytesseract`.  

This makes the script flexible to handle **typed PDFs, scanned photo-PDFs, and standalone images** — ensuring text can always be extracted regardless of the format.
