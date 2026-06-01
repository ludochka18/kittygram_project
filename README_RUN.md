# Kittygram combined project

Структура:
- backend/ — Django API
- frontend/ — React frontend

## Backend
```bash
cd backend
python -m venv venv
# PowerShell:
.\venv\Scripts\Activate.ps1
# Git Bash:
source venv/Scripts/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Backend: http://127.0.0.1:8000/

## Frontend
Открой второе окно PowerShell:
```powershell
cd frontend
npm install
npm start
```
Frontend: http://localhost:3000/
