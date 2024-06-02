# BS_MART

## 1. Introduction

BS_MART is a Django-based e-commerce web application designed to provide a smooth shopping experience. This system performs some basic operations like:

    1. User Authentication
    2. Product Listings
    3. Product Detail View
    4. Shopping Cart Management
    5. Checkout Process
    6. Order Management

The application also has key features like **authentication** and **authorization**.

## 2. Technology

The technology used in this project:
#### 2.1 Frontend   
- HTML
- CSS
- JavaScript

#### 2.2 Backend
- Python
- Django
- MySQL 

## 3. Prerequisites

Before the installation of the application, you must have the following dependencies installed on your system:

- Python (3.12+)
- Git
- pip (Python package installer)

## 4. Installation 

Clone the git repository to your desired location by the below command.

    git clone https://github.com/harshyadav02/bs_mart.git 

Now navigate to the **bs_mart** directory by

    cd bs_mart 

Run the following command to create a virtual environment and activate it:

    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`

Install all the packages and libraries required for the project:

    pip install -r requirements.txt  

## 5. Applying Migrations

Apply the migrations to set up your database:

    python manage.py migrate

## 6. Creating a Superuser

Create a superuser to access the Django admin interface:

    python manage.py createsuperuser

Follow the prompts to set up your superuser account.

## 7. Running the Application 

To run the application, use the command:

    python manage.py runserver

This will start the Django development server, and you can access the BS_MART application in your web browser at `http://127.0.0.1:8000/`.

## 8. Project Structure 

Here's an overview of the application directory structure:
```
BS_MART/
├── manage.py                      # The main management script for the Django project.
├── BS_MART/
│   ├── __init__.py                # Package initializer.
│   ├── settings.py                # The settings/configuration file for the project.
│   ├── urls.py                    # The URL configuration file for the project.
│   ├── asgi.py                    # ASGI configuration file.
│   └── wsgi.py                    # WSGI configuration file.
├── media/                         # Directory to hold user-uploaded media files.
│   └── product/                   # Directory for product images.
├── requirements.txt               # File listing all dependencies required for the project.
├── shop/                          # The main app directory.
│   ├── __init__.py                # Package initializer.
│   ├── admin.py                   # File to register models with the Django admin site.
│   ├── apps.py                    # File for the app configuration.
│   ├── forms.py                   # File containing form definitions.
│   ├── models.py                  # File containing model definitions.
│   ├── static/                    # Directory containing static files (CSS, JS, images).
│   │   ├── css/                   # Directory for CSS files.
│   │   ├── images/                # Directory for image files.
│   │   └── js/                    # Directory for JavaScript files.
│   ├── templates/                 # Directory containing HTML template files.
│   │   └── app/                   # Directory for app-specific templates.
│   ├── urls.py                    # URL configuration file for the shop app.
│   └── views.py                   # File containing view definitions.
```

---

Feel free to reach out if you have any questions or need further assistance. Happy coding!
