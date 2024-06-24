# Django Boilerplate
A minimalistic and comprehensive Django boilerplate to kickstart your web development projects efficiently. This template includes essential configurations and best practices to save you time and streamline your development process.

## Directory Structure
```
server/
├── .env
├── apps/
├── config/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings/
│   │   ├── __init__.py
│   │   ├── base.py
│   │   ├── development.py
│   │   ├── production.py
│   │   ├── testing.py
│   ├── urls.py
│   └── wsgi.py
├── logs/
│   └── django.log
├── manage.py
├── requirements/
│   └── requirements.txt
├── scripts/
├── static/
├── templates/
├── tree_structure.txt
├── utility/
```
## Setup Instructions
### 1. Clone the Repository:

```
git clone https://github.com/rohanphulkar/django-boilerplate.git
cd django-quickstart-boilerplate/server
```
### 2. Create a Virtual Environment:

```
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```
### 3. Install Dependencies:

```
pip install -r requirements/requirements.txt
```

### 4. Set Up Environment Variables:

 - Create a `.env` file in the server directory.
 - Add your environment-specific variables in the `.env` file.
### 5. Apply Migrations:

```
python manage.py migrate
```
### 6. Run the Development Server:

```
python manage.py runserver
```
## Configuration
#### 1. Settings:
 - The settings are divided into `base.py`, `development.py`, `production.py`, and `testing.py` for better management of different environments.
#### 2. Static Files:
 - Place your static files in the static/ directory.
#### 3. Templates:
 - Place your HTML templates in the templates/ directory.
#### 4. Logs:
 - Logs are configured to be stored in the logs/django.log file.
#### 5. Scripts
 - Place your custom management scripts in the scripts/ directory.

#### 6. Utilities
- The utility/ directory is reserved for utility functions and helpers that you might need across your project.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.