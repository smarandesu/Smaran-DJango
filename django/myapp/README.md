

# Django HelloWorld 


## Installation
 
We need virtual environment so run command:

```bash
  pip install virtualenv
```
Run below command (You can give any name in place of venv):
```bash
  virtualenv venv
```
Run command:
```bash
  .\venv\Scripts\activate.ps1
```
To install Django framework run command:
```bash
  python -m pip install django
```

Run below command to change directory:
```bash
  cd .\helloworld_project\
```

## Run Django Application
Run command:
```bash
  python manage.py runserver
```
Now open http://127.0.0.1:8000/ in your browser and you can see like below:
```bash
  {"Message": "Hello World!"}
```