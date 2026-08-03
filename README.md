# 🎓 Smart AI Attendance System

> **An AI-powered attendance management system that automates student attendance using face recognition technology.**

The Smart AI Attendance System is designed to simplify classroom attendance by recognizing registered students in real time. It provides a faculty-centric dashboard for managing students, training recognition models, tracking attendance, and exporting attendance records efficiently.

---

## ✨ Key Features

- 👨‍🏫 Faculty authentication and dashboard
- 📷 Face capture for student registration
- 🧠 AI-powered face recognition attendance
- 📊 Class-wise attendance tracking and statistics
- 📁 Export attendance records as CSV
- 🔁 Duplicate attendance prevention
- 💾 Automatic attendance backup
- 🌐 Backend deployment on Render
- ⚡ Fast and user-friendly interface

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Programming Language** | Python, JavaScript |
| **Backend** | Flask |
| **Frontend** | HTML, CSS, JavaScript |
| **AI / Computer Vision** | OpenCV, Face Recognition |
| **Database** | CSV / File Storage |
| **Deployment** | Render |
| **Version Control** | Git & GitHub |

---

## 📂 Project Structure

```text
Smart-AI-Attendance-System/
│
├── backend/
│   ├── app.py
│   ├── face_capture.py
│   ├── recognize_attendance.py
│   ├── train_model.py
│   ├── bulk_capture.py
│   ├── csv_import.py
│   ├── manage_students.py
│   └── config.py
│
├── frontend/
│   ├── index.html
│   └── pages/
│       └── faculty_dashboard.html
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/JyothiSriLakshmi-1305/Smart-AI-Attendance-System.git
cd Smart-AI-Attendance-System
```

### 2️⃣ Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
python backend/app.py
```

---

## 🚀 Usage

1. Register students by capturing face images.
2. Train the face recognition model.
3. Faculty logs into the dashboard.
4. Start attendance recognition.
5. Attendance is marked automatically.
6. Export attendance reports as CSV.

---

## 📊 System Workflow

```text
Student Registration
        │
        ▼
 Face Image Capture
        │
        ▼
 Model Training
        │
        ▼
 Faculty Login
        │
        ▼
 Face Recognition
        │
        ▼
 Attendance Marked
        │
        ▼
 Attendance Reports & CSV Export
```

---

## 🌟 Future Enhancements

- 📱 Mobile application
- ☁️ Cloud database integration
- 📧 Email notifications
- 📈 Analytics dashboard
- 🎥 Multi-camera support
- 🔐 Role-based authentication
- 🧑‍🎓 Student portal

---

## 📚 Skills Demonstrated

- Artificial Intelligence
- Machine Learning
- Face Recognition
- Computer Vision
- Flask Development
- Frontend Development
- Backend Development
- Git & GitHub

---

## 👩‍💻 Author

**Jyothi Sri Lakshmi Kuna**

- GitHub: https://github.com/JyothiSriLakshmi-1305
- LinkedIn: https://www.linkedin.com/in/jyothi-sri-lakshmi/

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and supports my work.
