# Contact Analytics & Event Tracking Platform

A Django-based platform that syncs Google contacts and tracks user events to provide analytics insights.
The system allows users to manage contacts, record events, and analyze interaction patterns in a structured dashboard.

## 🚀 Features

* Google Contacts Integration using Google People API
* Contact management system
* Event tracking and analytics
* Secure authentication with Google OAuth
* Event logging using Django signals
* Clean UI built with Tailwind CSS
* Scalable backend using PostgreSQL

## 🛠 Tech Stack

Backend

* Python
* Django

Database

* PostgreSQL
* MySQL (optional)

Frontend

* HTML
* Tailwind CSS

APIs & Integrations

* Google OAuth
* Google People API
* PayPal API

Tools

* Git & GitHub
* Docker

## 📂 Project Structure

Contact-Analytics-Platform

```
contacts/        # Contact management module
events/          # Event tracking system
templates/       # HTML templates
static/          # CSS / JS / images
manage.py
requirements.txt
```

## ⚙️ Installation

Clone the repository

git clone https://github.com/adityamohancse/Contact-Analytics-Platform.git

Move into project folder

cd Contact-Analytics-Platform

Create virtual environment

python -m venv venv

Activate environment

Windows
venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run migrations

python manage.py migrate

Start server

python manage.py runserver

Open browser

http://127.0.0.1:8000

## 📊 Future Improvements

* Dashboard analytics visualization
* Contact interaction insights
* Export reports
* Real-time event processing

## 👨‍💻 Author

Aditya Mohan Jha
Computer Science Engineering Student
Don Bosco Institute of Technology, Bengaluru

GitHub
https://github.com/adityamohancse
