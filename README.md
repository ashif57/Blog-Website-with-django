# Blog-Website-with-django
a sample website

step 1:
INSTALLATION AND SETUP:
-> visit the official django website https://www.djangoproject.com/start/
-> install python https://www.python.org/downloads/release/python-3123/
-> create a virtual environment steps will be available in this link https://docs.python.org/3/tutorial/venv.html
-> after creating a virtual environ ment activate it with command  || your_virtual_machine_name\scripts\activate ||
-> look dor the django version by command ||django-admin --version||
-> then start project by || django-admin startproject project_name||
-> then run server || python manage.py runserver||
-> then your server will run at ||http://127.0.0.1:8000/||
"error i face i can't find ctrl -BREAK key in my laptop"
step2:
Files in it
->   ||init.py|| to specify it as a package
->  ||asgi.py wsgi.py|| used in deplyment
->  ||settings .py|| contain details about static files,database etc
-> ||urls.py || contain the urls that we going to use in our website or app
-> ||sqlie|| defaultly contained in  django since it is an serverless,light weight database
-> ||manage.py|| is the server 
-> if we want to create a small app we use command
