# django-starter

**django-starter** is a boilerplate Django project based on Andrea Jud’s course. It provides a solid foundation for building Django web applications by incorporating best practices and useful third-party packages.

## Features

- ✅ Django setup with sensible defaults
- 🖼 Image support via [Pillow](https://pillow.readthedocs.io/)
- 🧹 Automatic media file cleanup using [django-cleanup](https://github.com/un1t/django-cleanup)
- 🔐 Built-in authentication system powered by [django-allauth](https://django-allauth.readthedocs.io/)
- ⚡️ Dynamic front-end interactions with [django-htmx](https://github.com/adamchainz/django-htmx)

## Getting Started

### Prerequisites

Make sure you have Python 3.8+ and [pip](https://pip.pypa.io/) installed. It’s recommended to use a virtual environment.

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Installation
Clone the repository:
git clone https://github.com/your-username/django-starter.git
cd django-starter
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
Start the development server:
python manage.py runserver
