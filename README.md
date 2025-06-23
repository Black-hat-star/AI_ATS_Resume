# 🧠 Smart ATS - Resume Evaluator using Gemini AI

Smart ATS is a Streamlit-based web application that acts like a highly skilled ATS (Applicant Tracking System) to help job seekers evaluate and improve their resumes based on a given job description.

This app leverages **Gemini 1.5 Flash** via Google’s Generative AI API to analyze the content of a resume PDF, compare it to a job description, and provide insights like:

- ✅ Percentage JD Match  
- 🔍 Missing Keywords  
- 📝 Profile Summary Feedback

---

## 🚀 Features

- Upload a resume (PDF format)
- Paste a job description
- Get a structured AI-generated evaluation report
- See missing keywords and optimization tips
- Powered by Google's Gemini model

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Black-hat-star/AI_ATS_Resume.git
cd AI_ATS_Resume

```
2.Install requirements
```
pip install -r requirements.txt

```
3. Set Up Environment Variables
```Create a .env file in the root directory and add your Google API key:
GOOGLE_API_KEY="your_gemini_api_key"

```
📦 Running the App
```
streamlit run app.py


```
🧪 Example Output
```
{
  "JD Match": "82%",
  "MissingKeywords": ["ETL", "Docker", "Kubernetes"],
  "Profile Summary": "Your profile shows strong data analysis and Python skills. Adding experience with containerization tools would improve alignment."
}

```
📝 Notes
```
Model used: models/gemini-1.5-flash
Resume must be in .pdf format
Use responsibly — API usage is subject to limits and quotas


