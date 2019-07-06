# Web-Development
Summary the general implement steps/methods of web development with tools Python Django
## Web Development Steps
### 1. Build a virtual enviroment for your project
**It is always a good idea that every project has its own virtual environment which will make the maintainance much easier in the future**
At the terminal side, type:
 1. Install virtual environment on your system `pip install virtualenv`
 2. a. Go to the file location that you want to have your project:`cd D:\Web_Dev`
    
    b. `python -m venv django_env` will have a `django_env` folder under  `D:\Web_Dev
 3. Active the virtual environment
    - Windows: `django_env\Scripts\activate`
    - Linux/Mac: `source django_env/bin/activate'
 4. Deactive your virtual environment: `deactivate`

### 2. Create an requirements.txt
 - When we deploy the project to the Linux Server, the requirments.txt will help the server download the used library/models(Django, pytz,etc.) or we will have to install these models maually on server which can be annoying and tedious.
 
### 3. 
