# 🚀 Django Starter Project

A clean and ready-to-use Django starter project with home page.

---

## 📂 Project Structure

```DjangoStarter/
├─ core/               # Django project folder (settings, URLs etc.)
├─ home/               # Main app (home page & templates)
│  ├─ templates/
│  │  └─ home.html     # Starter homepage template
│  └─ static/          # CSS, JS, images for branding
├─ manage.py           # Django management script
├─ requirements.txt    # Python dependencies
├─ Procfile            # For Render deployment
├─ runtime.txt         # Python version for Render
└─ db.sqlite3          # SQLite database (development)
```

---

## ⚡ Features

-   Ready-to-run templates & static files
-   Easy to clone and extend

---

# `🛠 Local Setup`

## 1. Clone the repo:

```bash
git clone https://github.com/YourUsername/DjangoStarter.git
cd DjangoStarter
```

## 1. Create virtual environment:

```bash
python -m venv venv
```

# Windows

```bash
./.venv/Scripts/activate
```

# Linux/macOS

```bash
source venv/bin/activate
```

# 3.Install dependencies:

```bash
pip install -r requirements.txt
```

# 4. Run migrations:

```bash
python manage.py migrate
```

# 5. Start the development server:

```bash
python manage.py runserver
```

## Access at

```js
http://127.0.0.1:8000
```

##

# `🛜Replit Setup:`

You can directly remix the live starter project on Replit: [Remix Django Starter Project](https://replit.com/@asif4520hossain/Django)

## 1️⃣ Go to & Create Account

[https://replit.com](https://replit.com/refer/asif4520hossain)

## 2️⃣ Import Your GitHub Repo

Replit automatically detects Python projects. To import:

1. Log in to Replit.
2. Click **Create** → **Import from GitHub**.
3. Paste your repo URL: https://github.com/Asif-4520/Django.git

4. Click **Import from GitHub**.
5. Replit will clone your repo and set up the environment automatically.

## 3️⃣ Install Dependencies (if not auto-installed)

```shell
pip install -r requirements.txt
```

## 4️⃣ Update settings.py for Replit if needed

```py
DEBUG = True
ALLOWED_HOSTS = ['*']
```

## 5️⃣ Run Migrations

```shell
python manage.py migrate
```

## 6️⃣ Run Server

```shell
python manage.py runserver
```

## **🎉 You're All Set!**

### _Congratulations! 🥳 Your Django Starter Project is ready ._

## _Thanks for using this starter project. If you enjoy it, ⭐ star the [GitHub Repo](https://github.com/Asif-4520/Django.git) and share it with others!_
