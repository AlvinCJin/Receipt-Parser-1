# Storing Receipt Data
Web development course project

Webapp for storing receipts with automated text parsing.


## Architecture
- JS+ Bootstrap frontend
  - Pretty minimal animated UI
- Rest api backend with Python using Django Framework
  - Scrapers for the Receipts
  - Tesseract for OCR
- Sqlite database

Module seperation is pretty good in both backend and frontend.

# How to Build and Run

- Clone or download this repo.
- Install tesseract and Django
- Run python3 manage.py runserver
- Open the page in a browser:<br />
  http://localhost:8000/

## Accuracy Issue
- Since the OCR doesn't have 100% accuracy, an edit button can be used to correct the information that is extracted by the OCR.