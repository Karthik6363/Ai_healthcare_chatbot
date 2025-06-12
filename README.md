# Ai_healthcare_chatbot

#  AI Healthcare Chatbot – Powered by BERT

A full-stack AI Healthcare Chatbot built with **Python, Flask**, and a **BERT-based NLP model**. The application assists users in getting health-related information, answering symptom-based questions, and managing user interactions securely with database and email integration.

---

##  Features

- 🧾 **BERT-powered chatbot** trained in Google Colab
- 🧠 Symptom-based question answering
- 🔐 User authentication with **bcrypt** hashing
- 📬 Email sending via SMTP
- 📦 Image/file serving support
- 📄 Database integration with **Flask SQLAlchemy + Migrate**
- 🧠 NLP with `run_chatbot.py` response logic

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **AI Model**: BERT (fine-tuned)
- **Database**: MySQL (via SQLAlchemy)
- **Others**: Flask-CORS, Flask-Bcrypt, Flask-Migrate, SMTP (mail), PIL (images), pickle


---

## 📝 Project Description

This AI Healthcare Chatbot system is a full-stack healthcare assistant platform designed for patients and doctors. The application combines AI-based symptom checking with real-time doctor appointments, offering a full medical assistance experience.

### 🧑‍⚕️ Patient Flow:
1. **User Registration/Login**  
   - Patients can sign up and log in to their personal dashboard.

2. **Chat with AI Chatbot**  
   - After login, patients are greeted with an AI chatbot (powered by BERT).
   - They can describe symptoms and receive instant suggestions or health info.

3. **Book Appointment with a Real Doctor**  
   - After the chatbot interaction, users can book an appointment with a real-time doctor.
   - Booking form includes details like time, date, and department.

4. **Email Confirmation**  
   - Once the appointment is booked, the system sends a confirmation email using SMTP.

5. **Live Location Support** *(Optional Feature)*  
   - Patients can view the live location or details of the hospital/doctor (if provided).

---

### 👨‍⚕️ Doctor Dashboard:

1. **Doctor Login**  
   - Doctors have a separate login and dashboard view.

2. **View All Appointments**  
   - Doctors can see the list of all booked appointments.

3. **Accept or Cancel Appointments**  
   - Doctors can choose to **confirm** or **cancel** each patient appointment from their dashboard.

---

This system offers a seamless experience by combining AI triage with human medical expertise, creating a smart assistant + human follow-up model.

##  How to Run Locally
- python app.py

### 1️ Clone the Repository
```bash
git clone https://github.com/Karthik6363/ai-healthcare-chatbot.git
cd ai-healthcare-chatbot
