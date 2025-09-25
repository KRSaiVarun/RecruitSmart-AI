# 🤖 RecruitSmart-AI

RecruitSmart-AI is an **AI-powered recruitment assistant** that helps recruiters and HR professionals analyze resumes against job descriptions.  
It provides **match scores, skills insights, and recommendations**, making hiring smarter and faster.

---

## 🚀 Features
- 📂 **Upload Resumes (PDF)** → Extracts candidate details automatically  
- 📝 **Paste Job Description** → Compare resumes against specific roles  
- 📊 **AI-Powered Analysis** → Get match percentage and insights  
- 🎯 **Highlight Skills** → Shows strengths, missing skills, and suggestions  
- 🌐 **Streamlit Interface** → Simple, interactive, and easy to use  

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **Streamlit** (frontend interface)
- **Google Generative AI (Gemini API)** via `google-generativeai`
- **LangChain** (for LLM orchestration)
- **PyPDF2** (resume parsing)
- **dotenv** (for API key management)

---

## 📂 Project Structure
RecruitSmart-AI/
│── main.py # Streamlit app
│── requirements.txt # Python dependencies
│── .env # API key (not pushed to GitHub)
│── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/KRSaiVarun/RecruitSmart-AI.git
   cd RecruitSmart-AI
Install dependencies

bash
Copy code
pip install -r requirements.txt
Set up API Key
Create a .env file in the project root and add:

ini
Copy code
GOOGLE_API_KEY=your_api_key_here
Run the app

bash
Copy code
streamlit run main.py
📊 Usage Workflow
Upload one or more resume PDFs

Paste or type the job description

Click Analyze

View:

✅ Resume match score

📌 Strengths & missing skills

💡 Smart recommendations

🎯 Example Use Case
A recruiter uploads multiple resumes for a Data Scientist position.

RecruitSmart-AI analyzes them against the job description.

Output shows:

Candidate A → 92% match

Candidate B → 76% match

Candidate C → 63% match

This way, recruiters can instantly shortlist the best-fit candidates.

🔮 Future Enhancements
📎 Support for multiple file formats (DOCX, TXT)

📊 Analytics dashboard for bulk resume screening

🌍 Multi-language support

🔐 ATS (Applicant Tracking System) integration

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

📜 License
This project is licensed under the MIT License – feel free to use and modify.
