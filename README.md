📄 AI Resume Analyzer
An interactive AI-powered tool that analyzes a candidate's resume and compares it with a job description to compute a match score, extract relevant skills, and highlight missing skills — helping both job seekers and recruiters.

🚀 Features
📤 Upload your resume (PDF)

📝 Paste or type the job description

⚙️ NLP-powered keyword extraction

🔍 Resume–JD similarity scoring using BERT embeddings

❌ Highlights missing or unmatched skills

✅ Real-time feedback via interactive Streamlit frontend

🧠 Tech Stack
Frontend: Streamlit

Backend: Python

NLP: spaCy, Sentence-Transformers (BERT)

PDF Parsing: pdfplumber

📦 Requirements
Install all dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Or manually:

bash
Copy
Edit
pip install streamlit pdfplumber spacy sentence-transformers tensorflow keras tf-keras
python -m spacy download en_core_web_sm
🏗️ Project Structure
bash
Copy
Edit
resume-analyzer/
├── app.py                   # Streamlit frontend app
├── requirements.txt         # All Python dependencies
├── README.md                # You're reading it!
└── sample_data/             # Optional sample resumes & JDs
🧪 How to Run Locally
bash
Copy
Edit
streamlit run app.py
The app will open in your default browser at:
👉 http://localhost:8501

💼 Sample Use Case
✅ Example Resume:
makefile
Copy
Edit
Skills: Python, Machine Learning, NLP, Deep Learning, Pandas
✅ Example Job Description:
csharp
Copy
Edit
Looking for a candidate with experience in NLP, Transformers, Deployment, and TensorFlow.
🔍 Output:
Match Score: 75%

Missing Skills: Deployment, TensorFlow

🎯 Who is it for?
🎓 Students preparing for placements

👨‍💼 Professionals switching roles

👩‍🏫 Career counselors

🧠 Resume screening tools (HR/ATS)

📈 Future Enhancements
🔢 Resume ranking for bulk uploads

🧠 Skill gap analysis and learning suggestions

🌐 JD parsing directly from job portals (LinkedIn, Indeed)

🧾 Resume builder with real-time recommendations

📊 Exportable match reports in PDF or CSV

👨‍💻 Author
Maheshwari Kalaskar
AI/ML Enthusiast | Final Year B.Tech (AI)
GitHub: github.com/maheshwarikalaskar
