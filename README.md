# Video Conference App using Django

## 📌 Project Overview
This is a **Video Conferencing Web App** built using **Django**. It allows users to create or join meetings, enabling real-time communication via video and audio.

## 🚀 Features
- User authentication (login/register)
- Create or join video conferences
- Real-time video and audio streamig
- Room management with unique meeting links
- Responsive UI for different devices

## 🛠️ Tech Stack
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **WebRTC**: Peer-to-Peer (P2P) video/audio streaming
- **Deployment**: Render 

## 📂 Project Structure
```
video-conference-django/
│── conference_app/    # Main Django app
│── templates/         # HTML templates
│── static/            # Static files (CSS, JS)
│── media/             # Uploaded files
│── db.sqlite3         # SQLite database (or configure PostgreSQL)
│── manage.py          # Django management script
│── requirements.txt   # Dependencies
│── README.md          # Project documentation
```

## 🏗️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/deepraj16/Video-conference-django.git
cd video-conference-django
```

### 2️⃣ Set Up Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Database
```bash
python manage.py migrate
python manage.py createsuperuser  # Create an admin user
```

### 5️⃣ Run the Server
```bash
python manage.py runserver
```

## 📜 License
This project is open-source under the **MIT License**.

## 💡 Contributing
Contributions are welcome! Feel free to fork, open issues, or submit PRs.

## 📞 Contact
For any issues, contact [deeprajautade1@gmail.com] or create an issue on GitHub.

---
**Happy Coding! 🚀**

