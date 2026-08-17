<div align="center">

# 🎓 NovaLore

**A full-featured e-Learning Management System (LMS) built with Django — attendance, quizzes, discussions, and course management in one platform.**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Contributors](https://img.shields.io/github/contributors/Kerim-Myratlyev/NovaLore)
![Commits](https://img.shields.io/github/commit-activity/t/Kerim-Myratlyev/NovaLore)

</div>

---

## ✨ Overview

NovaLore is a web-based Learning Management System that brings the core of an online school into a single Django application. Students and instructors get course content, live discussions, quizzes, and attendance tracking in one place — no juggling separate tools. It was built collaboratively (6 contributors, 100+ commits) as a real, working platform rather than a toy demo.

## 🚀 Features

- **📚 Course & content management** — organize learning material by course and module
- **📝 Quizzes** — create and take quizzes with automatic handling of questions and answers
- **💬 Discussions** — a built-in discussion space so students and instructors can talk through material
- **✅ Attendance tracking** — record and review attendance per session
- **👤 User profiles** — profile pictures and per-user accounts
- **🎨 Responsive UI** — HTML/CSS/JS front end served through Django templates

## 🛠️ Tech stack

**Backend:** Python · Django
**Frontend:** HTML · CSS · JavaScript
**Database:** SQLite (default Django) — swap for PostgreSQL in production

## 📂 Project structure

```
NovaLore/
├── attendance/     # Attendance tracking app
├── discussion/     # Discussion / forum app
├── quiz/           # Quiz creation and grading app
├── eLMS/           # Core LMS app (courses, content)
├── main/           # Main app (home, routing)
├── templates/      # HTML templates
├── static/         # CSS, JS, images
├── media/          # User uploads (e.g. profile pics)
├── manage.py       # Django management entry point
└── requirements.txt
```

## 🏁 Getting started

```bash
# 1. Clone the repository
git clone https://github.com/Kerim-Myratlyev/NovaLore.git
cd NovaLore

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply database migrations
python manage.py migrate

# 5. Create an admin account
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver
```

Then open **http://127.0.0.1:8000/** in your browser.

## 🗺️ Roadmap

- [ ] REST API for a mobile client
- [ ] Grade book / progress dashboard
- [ ] Email notifications for deadlines
- [ ] Deploy a public live demo

## 🤝 Contributing

This was a team project and contributions are still welcome. Fork the repo, create a feature branch, and open a pull request. For big changes, open an issue first to discuss what you'd like to change.

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.

## 👤 Author

**Kerim Myratlyev** — [@Kerim-Myratlyev](https://github.com/Kerim-Myratlyev) · [Dev.to](https://dev.to/kerimmyratlyyev)

---

<div align="center">
⭐ If NovaLore is useful or interesting to you, a star helps others find it too!
</div>
