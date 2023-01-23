# djangoscraper
learn deploy webscraper with django

## Step by Step

### A. Rabbitmq installation on windows
1. Install Erlang
   * download erlang otp installer at https://erlang.org/download/otp_versions_tree.html
   * run otp_win64_25.2.1.exe
2. Install Rabbitmq
   * download rabbitmq-server-3.11.7.exe at https://github.com/rabbitmq/rabbitmq-server/releases/download/v3.11.7/rabbitmq-server-3.11.7.exe
   * run rabbitmq-server-3.11.7.exe

### B. Django Preparation
1. Install django framework package (in terminal)
2. Start django project (in terminal django-admin startproject project_name.)
3. Setup django project
   * migrate (in terminal manage.py migrate)
   * create superuser (in terminal manage.py createsuperuser)
   * create_app(in terminal manage.py startapp app_name)
   * install app (in project_name/settings.py INSTALLED APPS) into project 
   * create html file tamplate (in project_name/template_name.html)
   * setup template DIRS path (in project_name/settings.py TEMPLATES)
   * add static path (in project_name/settings.py STATIC_URL), static files(css, js, etc.)
   * add media path (in project_name/settings.py MEDIA_URL), media files
4. Setup django app
   * create urls.py (in app_name/)
   * include desired urls (app_name/urls) for the app (in project_name/urls.py urlpattern)
   * create views function or classes (in app_name/views.py)
   * open route from url to views function (in app_name/urls.py)
   * create models (in app_name/models.py)

### C. Web Scraper Preparation
  * Install Selenium (in terminal)
  * Create

make migration (in terminal manage.py makemigration)
