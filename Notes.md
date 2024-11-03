### Creating virtual environment for python (To isolate different projects)
Installing virtual environment globally

    pip install virtualenv
Creating virtual environment

    virtualenv venv
Activate virtual environmentenv1

    env1/Scripts/activate

(if execution policy is restricted : 
    * Get-ExecutionPolicy Set-ExecutionPolicy-ExecutionPolicy

    * ExecutionPolicy RemoteSigned -Scope CurrentUser
)

### Django commands 
* pip install Django : Installing Django

* django-admin startproject ecommerce : starting a project by creating a repo

* python manage.py runserver : Run the manage.py file inside project repo to run Django server

