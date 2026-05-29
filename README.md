# ניהול לוגיסטיקה

## Railway Deployment

### Required Environment Variables on Railway:
- `SECRET_KEY` — any random string (e.g. openssl rand -hex 32)
- `ADMIN_PASSWORD` — סיסמת אדמין שלך
- `USER_PASSWORD` — סיסמה למשתמשים רגילים

### Add Persistent Volume:
In Railway: Add Volume → Mount Path: `/data`

### Local Dev:
```bash
pip install -r requirements.txt
python app.py
```
Default passwords: admin=`admin2026`, users=`logistics2026`
