
# Intelligent Resume Screening using AI 🤖




## Team Members 👥 

- Bhumit Tanwar (2401201029)
- Pratyush jha  (2401201017)
- Sohail Khan  (2401201040)
- Tarun (2401201077)


## Project Description 📄
- Intelligent Resume Screening using AI automatically evaluates resumes, assigns a score out of 10, highlights areas for improvement, and recommends trusted resources to enhance resume quality.


## Video Link 🔗
https://github.com----video_link_paste_here.

# Technologies
Main Technologies 🛠️
- Python
- Streamlit (for building the web app)
- MySQL (via `pymysql`)

Pyton Liabraries

- `streamlit`

- `pandas`

- `pyresparser` (for parsing resumes)

- `pdfminer3` (for reading PDF files)

- `PIL` (Pillow) (for image processing)

- `pymysql` (for MySQL database operations)

- `nltk` (Natural Language Toolkit - for stopwords)


# Steps to Run/Execute the Project 🚀

1. Install Required Libraries

```bash
pip install -r requirements.txt
```

This will install all necessary Python libraries like` pdfminer3`, `pyresparser`, `streamlit`, `pandas`, etc.

2. Prepare the Backend (If Using FastAPI - Optional)
If you're also running a FastAPI backend for parsing and matching.

```bash
pip install fastapi uvicorn
```
Then run
```bash
uvicorn main:app --reload
```
Access it at:`http://127.0.0.1:8000/docs`

3. Run the Streamlit App
Inside the project folder, run:
```bash
streamlit run app.py

```
Streamlit will start a local server and automatically open a browser window.
Example URL:
`http://localhost:8501/`

4. Upload Resume

- Click on the upload section.

- Upload a PDF or DOCX resume.

- The system will extract resume information automatically.

