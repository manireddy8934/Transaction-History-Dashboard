
# 📁 notebooks/

This folder includes the code used to extract transaction data from the PDF.

## Files Included:
- **pdf_to_dataset.ipynb / extract_pdf_to_csv.py**  
  Python notebook/script that:
  - Reads the PDF using `pdfplumber`
  - Extracts and cleans text using `re` (regex)
  - Converts it into structured tabular data
  - Exports it as a `.csv` file

## Purpose:
This notebook automates the PDF-to-CSV process and prepares data for Power BI visualization.
