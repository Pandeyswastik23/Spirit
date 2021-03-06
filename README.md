# Spirit
Spirit is a Python based forum built using the Django framework.
# Spirit

[![Build Status](https://img.shields.io/travis/nitely/Spirit.svg?style=flat-square)](https://travis-ci.org/nitely/Spirit)
[![Coverage Status](https://img.shields.io/coveralls/nitely/Spirit.svg?style=flat-square)](https://coveralls.io/r/nitely/Spirit)
[![pypi](https://img.shields.io/pypi/v/django-spirit.svg?style=flat-square)](https://pypi.python.org/pypi/django-spirit)

Spirit is a Python based forum built using the Django framework.


## Compatibility

* Python 2.7, 3.4, 3.5, 3.6 (recommended) and 3.7
* Django 1.11 LTS (recommended), 2.0, 2.1
* PostgreSQL (recommended), MySQL, Oracle Database and SQLite

Constrained by "[What Python version can I use with Django?](https://docs.djangoproject.com/en/2.1/faq/install/#what-python-version-can-i-use-with-django)"

## Usage

> New in Spirit 0.5

```
pip install django-spirit
spirit startproject mysite
cd mysite
python manage.py spiritinstall
python manage.py createsuperuser
python manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000)


```
python runtests.py
```



