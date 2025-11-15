AI Health Chatbot – Premium Edition (Glass Dashboard UI)
An Intelligent Medical Assistant with Doctor Booking, Chat, Dashboard & Image Upload

Developer: Abhishek Arjun (Reg. No. 12316809)
University: Lovely Professional University
Guide: Souhardya Bose

🚀 Overview

AI Health Chatbot is a smart healthcare assistant that helps users interact with AI for medical guidance, book appointments, chat with doctors, upload images, and manage their profile — all inside a modern Glassmorphism Dashboard UI.

It is built using:
✔ Flask (Python)
✔ SQLite Database
✔ HTML + CSS + JS (Glass UI)
✔ OpenAI API (optional or offline mode)

🌟 Features
🧠 AI-Powered Health Chat

Gives symptom-based health suggestions

Supports offline fallback responses

Stores full chat history

👨‍⚕️ Doctor Management System

10+ demo doctors auto-created

Doctor profile shows specialization, experience, availability

Patients can book appointments

Doctors get their own dashboard

📅 Appointments Module

Book appointments with date/time

Status tracking

Doctor & Patient views

🧩 User System

Login / Signup

Doctor or Patient mode

Profile editing

Profile image upload

🖼️ Image Upload for Health Reports

Upload prescription / scan / health files

Images saved in /static/uploads/

🎨 UI Highlights

Modern glassmorphism dashboard

Responsive layout

Smooth animations

Dark + Frosted Glass look

📂 Folder Structure
ai_health_chatbot/
│── app.py
│── requirements.txt
│── /database/app.db
│── /static/
│   ├── /css/
│   ├── /js/
│   ├── /avatars/
│   └── /uploads/
│── /templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard_patient.html
│   ├── dashboard_doctor.html
│   ├── doctors.html
│   ├── appointment.html
│   ├── profile.html
│   └── chat.html
└── README.md

🔧 Installation
1️⃣ Install Python

Make sure you have Python 3.10 – 3.12 installed
(Recommended: Python 3.10 or 3.11)

2️⃣ Create Virtual Environment
python -m venv venv

3️⃣ Activate Environment (Windows)
venv\Scripts\activate

4️⃣ Install Packages
pip install -r requirements.txt

5️⃣ Run App
python app.py


The app will start at:
👉 http://127.0.0.1:5000

🔑 Environment Variables (Optional for AI Mode)

Create a .env file:

OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
FLASK_SECRET=yourRandomSecret


If no key is added → offline medical reply mode will be used.

👤 Demo Accounts
Role	Username	Password
👨‍⚕️ Doctor	dr_aditya	1234
👤 Patient	patient1	1234
🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Flask (Python)
Database: SQLite
AI Integration: OpenAI API
UI Theme: Glassmorphism

📸 Screenshots

Add your UI screenshots here

![Dashboard](screenshots/dashboard.png)
![Chat](screenshots/chat.png)
![Doctors](screenshots/doctors.png)

📌 Future Enhancements

Full doctor chat system

E-prescription generator

Medical history log

Voice-based health assistant

Admin panel

📝 License

Released under the MIT License.

⭐ Support

If you like this project, please ⭐ star the repository on GitHub.

If you want, I can also:
✅ Add badges, icons, shields
✅ Add screenshots section
✅ Add demo video link
✅ Generate GitHub tags / description
