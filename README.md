# Local Library Django Project

Welcome to the Local Library Django Project! This project is a web application designed to manage the catalog of a local library, allowing users to browse books, authors, genres, and more.

## Overview

This web application creates an online catalog for a small local library, where users can browse available books and manage their accounts.

The main features that have currently been implemented are:

* There are models for books, book copies, genre, language and authors.
* Users can view list and detail information for books and authors.
* Admin users can create and manage models. The admin has been optimised (the basic registration is present in admin.py, but commented out).
* Librarians can renew reserved books

### Features

- **Catalog Management:** Browse books, authors, genres, and book instances.
- **User Authentication:** Register, login, and manage user accounts.
- **Admin Interface:** Manage library data via Django's built-in admin interface.
- **Search Functionality:** Search books, authors, and genres with ease.
- **User-friendly UI:** Intuitive design for seamless user experience.
  

## Quick Start

To get this project up and running locally on your computer:
1. Set up the [Python development environment]. Recommend using a Python virtual environment.
   
1. Assuming you have Python setup, run the following commands (if you're on Windows you may use `py` or `py -3` instead of `python` to start Python):
   ```
   pip3 install -r requirements.txt
   python3 manage.py makemigrations
   python3 manage.py migrate
   python3 manage.py collectstatic
   python3 manage.py test # Run the standard tests. These should all pass.
   python3 manage.py createsuperuser # Create a superuser
   python3 manage.py runserver
   ```
1. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site
1. Create a few test objects of each type.
1. Open tab to `http://127.0.0.1:8000` to see the main site, with your new objects.

