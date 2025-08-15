# HireME – AI Resume Self Screening System

## 📌 Overview
In the modern recruitment landscape, employers face a massive influx of job applications for each open position, making manual resume screening inefficient, time-consuming, and prone to human error.  

**HireME** is an intelligent job board platform integrated with an **AI-powered ATS tracker**.  
It allows job seekers to upload their resumes, which are then automatically parsed, analyzed, and matched against job descriptions using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.

Candidates receive:
- A **real-time match score**
- Feedback on how well their resume aligns with the selected job
- Suggestions to improve their chances

This empowers job seekers to **optimize resumes** and apply more strategically.

---

## 🚀 Features
- AI-powered Applicant Tracking System
- Real-time resume parsing and scoring
- NLP-based contextual keyword analysis
- Match percentage visualization
- Job listing and application management
- Interactive dashboard for candidates
- Built using **Python (Flask)**, **React**, and **JavaScript**

---

## 🛠️ Tech Stack
**Frontend:** React, JavaScript  
**Backend:** Flask (Python)  
**Machine Learning:** scikit-learn, spaCy, NLTK  
**Data Handling:** Pandas, NumPy  
**Document Processing:** python-docx, python-magic  

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/HireME.git
   cd HireME
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install backend dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run backend (Flask API)**
   ```bash
   python server.py
   ```

5. **Run frontend (React)**
   ```bash
   cd frontend
   npm install
   npm start
   ```

---

## 📂 Project Structure
```
Hire_ME-main/
├── HireMe-backend/
│   ├── requirements.txt
│   ├── server.py
│   ├── .env/
│   └── ...
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
├── README.md
└── requirements.txt
```

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](screenshots/home.png)

### 📋 Job Listings
![Job Listings](screenshots/job-listings.png)

### 📊 Job Details & ATS Match Result
![Job Details](screenshots/job-details.png)

---

## 🎨 Figma UI Design
You can view the complete UI design here:  
[**HireME Figma Design**](https://www.figma.com/design/ifNGx8qD1mkaJV6cNilewN/Ats?node-id=8442-89&t=p3M5a0cYrveY0gA8-1)

---

## 📜 License
This project is licensed under the MIT License.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit pull requests.
