Anonymizing sensitive data like names, phone numbers, and emails is essential for protecting privacy during data sharing and machine learning. This tool automatically anonymizes such details in files — without replacing them with asterisks — and keeps the original format intact.

✅ Features
**Accepts: .csv, .xlsx, .txt, .docx, and PDF (text-based) files**

Randomizes:

📛 Names → random letters

📞 Phone numbers → changes a few digits

📧 Emails → local part randomized, domain preserved

Maintains original format (e.g., .xlsx in → .xlsx out)

Easy to use with just one function call

⚙️ Usage
Install dependencies

**bash
Copy
Edit
pip install pandas python-docx PyMuPDF pdfplumber openpyxl
Run the script**
use **python app.py** in terminal
it will direct you to a webpage
Saved in the same folder as:
anonymized_<original_filename>.<ext>

📌 Notes
**PDF support is read-only: output is saved as .txt or .docx**

**Data stays structurally valid — ideal for ML or safe sharing**

**No masking — values are realistically randomized**
