# Django API Starter

## Installation

Clone repo:
```
git clone https://github.com/smashingmouse/mark-it-api
cd mark-it-api
```

Create and activate local python environment:

```
python -m venv env
. ./env/bin/activate
```

Install requirements:

```
pip install -r requirements.txt
```

Create database:
```
createdb markit
```

Django setup:
```
python manage.py migrate
python manage.py createsuperuser
python manage.py collectstatic
```