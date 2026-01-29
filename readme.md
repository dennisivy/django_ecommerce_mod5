# Django eCommerce Website

Basic Django eCommerce website with guest checkout and PayPal integration.

## Tutorial Reference

This project is part of the tutorial video: https://youtu.be/_ELCMngbM0E?si=H7fSY5JRmwoR-V21

## Setup

1. Clone this repo:
   ```bash
   git clone <repo_url>
   cd django_ecommerce_mod5
   ```
2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
   On Windows:
   ```powershell
   .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
5. (Optional) Create an admin user:
   ```bash
   python manage.py createsuperuser
   ```
6. Run the server:
   ```bash
   python manage.py runserver
   ```
7. Visit the app at http://127.0.0.1:8000/

## Screenshot

<img src="./static/images/demo.png" alt="Django eCommerce demo screenshot"/>
