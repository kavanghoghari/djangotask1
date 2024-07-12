touch README_Task1.md
touch README_Task2.md
# Django App with Two HTML Pages and HTTPS Requests

This README provides step-by-step instructions for creating a Django app with two HTML pages and HTTPS requests.

## Setup Instructions

1. Create a new Django project:
2. Create a new app within the project:
3.Add the app to the project's settings. Open `myproject/settings.py` and add 'myapp' to INSTALLED_APPS.
4. Create templates directory:
5. Create two HTML files:
6. Edit the HTML files with basic content.

7. Create views in `myapp/views.py`.

8. Create URL patterns:
9. Edit `myapp/urls.py` with URL patterns.

10. Include app URLs in the project's main URLs. Edit `myproject/urls.py`.

11. Install the requests library:
 ```
 pip install requests
 ```

12. Run migrations:
 ```
 python3 manage.py migrate
 ```

13. Start the development server:
 ```
 python3 manage.py runserver
 ```

access pages at:
- http://127.0.0.1:8000/page1/
- http://127.0.0.1:8000/page2/
