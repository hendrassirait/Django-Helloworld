# Django-Helloworld

to use it,

- open Terminal,
- change directory to folder
- start virtual environment
  pipenv shell
- start server
  python manage.py runserver
- go to url given by terminal and add /Hello/
  ie. http://127.0.0.1:8000/Hello/

update #1
I found alert after I upload this folder, it says pipfile and pipfile.lock is High Severity,
i still try to figure it out what is happening,
but in case if you get the error for pipfile and pipfile.lock maybe you should install those file on your folder first.

- open terminal
- change directory to folder
- install pipnenv on django
  pipenv install django==2.1
  you can use any django version, but i use 2.1 on my project so far
  
update #2
  i found the issue, 
  it seems that GitHub told me to upgrade my django version to 2.1.2 instead of 2.1
  if you use django 2.1.2 version or the newest,
  you should delete pipfile and pipfile.lock and then install django to get those file again
  
thanks
