# 🐍 django_app

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  <img src="https://img.shields.io/badge/Python-Django-blue" alt="Main Language" />
  <img src="https://img.shields.io/badge/status-active-brightgreen" alt="Status" />
</p>

---

## ✨ Overview

**django_app** is a project containing exercises and practical examples developed with Python and Django. The goal is to facilitate learning and experimentation with the Django framework, showcasing best practices and key features for web development.

---

## 🎨 Tech Stack

<div align="center">

| Language / Tool                                        | Usage                                     |
|--------------------------------------------------------|-------------------------------------------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="24"/> Python | Main logic and scripting                  |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="24"/> Django | Web development framework                 |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="24"/> SQLite | Default lightweight database              |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="24"/> GitHub Actions | CI/CD automation                          |

</div>

---

## 🗂️ Project Structure

```text
.
├── django_app/           # Main source code for the Django project
├── manage.py             # Project management script
├── requirements.txt      # Python dependencies
├── db.sqlite3            # Local database (default)
├── .github/workflows/    # CI/CD pipelines (GitHub Actions)
└── README.md             # Project documentation
```

---

## ⚡ Features

- Practical exercises and examples with Django
- Modular and easy-to-understand structure
- Ready-to-use CI/CD integration with GitHub Actions
- Ideal for learning and experimentation
- Clean and documented code

---

## 🛠️ Getting Started

> **Install and run the project in minutes.**

```bash
# Clone the repository
git clone https://github.com/MarSegu/django_app.git
cd django_app

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
```

---

## ⚙️ Main Configuration

| File / Variable          | Description                            | Example               |
|-------------------------|----------------------------------------|-----------------------|
| `settings.py`           | Global Django configuration            | Database, apps        |
| `requirements.txt`      | Required packages and versions         | `Django==4.2.0`       |
| `manage.py`             | Django management command               | `runserver`, `migrate`|

---

## 🧪 Testing

> Run the project's automated tests.

```bash
python manage.py test
```

---

## 🚀 Deployment

- **CI/CD:** Automated via workflows in `.github/workflows/`.
- **Containers:** You can add a Dockerfile for container deployment.

---

## 📤 Outputs

| Output             | Description                    |
|--------------------|-------------------------------|
| `localhost:8000`   | App URL in development         |
| `test results`     | Test results                   |

---

## 🤝 Contributing

Contributions are welcome!  
Open an issue or pull request for suggestions and improvements.

---

## 📃 License

Distributed under the MIT License. See [LICENSE](LICENSE) for more details.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=footer"/>
</p>

