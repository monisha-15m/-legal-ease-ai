# LegalEase AI

## Technologies
- HTML, CSS, JavaScript
- Python
- Flask REST API
- Google GenAI Python SDK
- Gemini LLM

## Folder structure
10_LegalEase_AI/
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── templates/
    └── index.html

## Important
Do NOT put your Gemini API key directly inside app.py. Copy `.env.example` to `.env` and add your key.

## Run
1. Open this folder in VS Code.
2. Open Terminal.
3. Create virtual environment:
   `python -m venv venv`
4. Activate it on Windows:
   `venv\Scripts\activate`
5. Install packages:
   `pip install -r requirements.txt`
6. Create `.env` from `.env.example`.
7. Put your Gemini API key in `.env`.
8. Run:
   `python app.py`
9. Open the local address shown by Flask, normally http://127.0.0.1:5000
