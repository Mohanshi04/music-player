# Music Player App

A web-based music player built with **Django**, supporting image display and audio playback. This app demonstrates media file handling, pagination, and dynamic content rendering with templates.

---

## Features

- Upload songs with metadata (title, artist, audio, cover image, lyrics, duration).
- Paginated song list with album covers and song titles.
- Play audio files directly from the browser.
- Responsive HTML template integration.

---

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3 (custom)
- **Media Handling**: Pillow (for image fields)

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Contents of `requirements.txt`:
```
Django>=3.2,<5.0
Pillow>=8.0.0
```

---

## Project Structure

```
music_player/
│
├── .env
├── .gitignore
├── db.sqlite3
├── manage.py
├── README.md
├── requirements.txt
├── test.py                            
│
├── media/
│
├── music_env/
│
├── music_app/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
    ├── urls.py
│   ├── views.py
│   ├── templates/
│   │   ├── index.html
│   │   └── main.html
│   └── static/
│       ├── styles.css
│       └── script.js
│
├── music_player/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__/
```

---

## Setup Instructions

1. **Clone the repository**:
```bash
git clone <your-repo-url>
cd music_player
```

2. **Activate virtual environment** (optional but recommended):
```bash
python -m venv music_env
music_env\Scripts\activate  # Windows
```

3. **Install dependencies**:
```bash
pip install -r requirements.txt
```

4. **Run migrations**:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Run the server**:
```bash
python manage.py runserver
```

6. **Open in browser**:
```
http://127.0.0.1:8000/
```

---
```

---
