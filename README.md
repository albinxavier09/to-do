# 🚀 Quick Start – Django To-Do App

## 1. Clone the repository
```bash
git clone https://github.com/albinxavier09/to-do.git
cd to-do
```

## 2. Create & activate virtual environment
```bash
python3 -m venv venv
source venv/bin/activate       # Mac/Linux
venv\Scripts\activate          # Windows
```

## 3. Install dependencies
```bash
pip install -r requirements.txt
```

## 4. Run database migrations
```bash
python manage.py migrate
```

## 5. (Optional) Create a superuser for admin access
```bash
python manage.py createsuperuser
```

## 6. Start development server
```bash
python manage.py runserver
```

## 7. Access the app
- 🌐 **Main App** → [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
- 🔑 **Admin Panel** → [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)  

## 8. Run Tests
```bash
python manage.py test
```

---

## 📌 Quick Links
- 🏠 **Home** → [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
- ✍️ **Sign Up** → [http://127.0.0.1:8000/signup/](http://127.0.0.1:8000/signup/)  
- 🔐 **Login** → [http://127.0.0.1:8000/login/](http://127.0.0.1:8000/login/)  
- ✅ **Tasks** → [http://127.0.0.1:8000/tasks/](http://127.0.0.1:8000/tasks/) (after login)  

---

👉 The server runs on **port 8000** by default.  
Stop it anytime with **`Ctrl + C`**.  
