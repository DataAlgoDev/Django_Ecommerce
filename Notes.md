### Creating virtual environment for python (To isolate different projects)
<span style="color: #dee053;">Installing virtual environment globally</span>
    pip install virtualenv
*Creating virtual environment*

    virtualenv venv
*Activate virtual environment 'env1'*

    env1/Scripts/activate

*If execution policy is restricted* 

    Get-ExecutionPolicy
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    Get-ExecutionPolicy
    

### Django commands 
*Installing Django*

    pip install Django

*Creating a project folder and initing Django inside* 

    django-admin startproject ecommerce

*Run the manage.py file inside project repo to run Django server*

    python manage.py runserver

