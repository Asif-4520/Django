# 🚀 Django Starter Project

A clean and fast Django starter template with homepage, static files, and ready-to-code setup for local, Codespaces, and Replit.

---

## 📦 Features

-   Minimal, clean project structure
-   Ready homepage (`home/templates/home.html`)
-   Static folder included
-   Works on VS Code DevContainers
-   Works on Replit
-   Fast setup (clone → install → run)

---

## 📂 Project Structure

```
DjangoStarter/
├─ core/               # Django main project
├─ home/               # App (templates + static)
├─ manage.py
├─ requirements.txt
├─ runtime.txt
└─ .devcontainer/      # Ready for Codespaces
```

---

# ⚡ Quick Start (Local)

```bash
git clone https://github.com/Asif-4520/Django.git
cd Django

python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000
```

---

## ⚡ Run in GitHub Codespaces (DevContainer Ready)

This project is fully optimized for **GitHub Codespaces**.  
Just open it in Codespaces and everything is auto-setup.

---

### 🟢 1. Open in Codespaces

1. Click **“Use this template”** on GitHub
2. Create a **New Codespace**

Codespaces will automatically:

✔ Build the DevContainer  
✔ Install all dependencies  
✔ Forward ports  
✔ Open VS Code in the browser

No manual setup required.

---

### 🟢 2. Start the Server in Codespaces Terminal

### ▶️ Django:

```bash
python manage.py runserver
```

---

### 🟢 3. Open the Forwarded Port

Codespaces automatically forwards ports used by your server.

1. Look at the **PORTS** tab
2. Find `8000` (Django)
3. Click **“Open in Browser”**

That’s it — your app will open instantly.

---

### 💡 Tip

If the port doesn’t show automatically, re-run the server with `0.0.0.0` so Codespaces can expose it.

---

# ⚡ Replit Setup

You can directly run this project on Replit in **two ways**:

---

## ✅ 1. Remix (Recommended)

[Remix](https://replit.com/@asif4520hossain/Django)

## ✅ 2. Run Inside Replit

1. Go to **Replit → Create Repl**
2. Click **“Import from GitHub”**
3. Paste this repo URL:

```
https://github.com/Asif-4520/Django
```

4. Click **“Import”**
5. Replit will clone your repo and install files automatically.

---

After importing, open the Replit shell and run:

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 0.0.0.0:8000
```

Replit will detect port **8000** and auto-generate a preview link.

---

## 🚀 Ready to Code

✔ Full Django project  
✔ Auto web preview  
✔ No setup needed  
✔ Works immediately after import

# ⭐ Support

If you like this project, give it a star ⭐  
https://github.com/Asif-4520/Django
