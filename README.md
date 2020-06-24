# Django Local Library

This web application creates an online catalog for a small local library, where users can browse available books and manage their accounts.

The main features that have currently been implemented are:

* There are models for books, book copies, genre, language and authors.
* Users can view list and detail information for books and authors.
* Admin users can create and manage models.
* Librarians can renew reserved books

## Get started
Python version: 3.7.0
   ```
   pip install -r requirements.txt
   python manage.py makemigrations
   python manage.py migrate
   python manage.py test # Run the standard tests. These should all pass.
   python manage.py createsuperuser # Create a superuser
   python manage.py runserver
   ```
* Open `http://127.0.0.1:8000` to see the main site.

# Website Link
https://django-local-lib.herokuapp.com