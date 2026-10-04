# Coetzee & Co Attorneys Inc. - FastAPI Web Application

This project provides a modern, responsive corporate landing page for **Coetzee & Co Attorneys Inc.** built using **FastAPI**, **Jinja2**, and **Uvicorn**.

## Project Structure

```
.
├── main.py
├── requirements.txt
├── README.md
├── static/
│   └── css/
│       └── style.css
└── templates/
    ├── base.html
    ├── index.html
    └── success.html
```

## Setup & Execution

1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server:
   ```bash
   python main.py
   ```
   Or run directly with Uvicorn:
   ```bash
   uvicorn main:app --reload --port 8000
   ```

4. Open `http://127.0.0.1:8000` in your web browser.
