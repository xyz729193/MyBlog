[Django 学习教程](https://simpleisbetterthancomplex.com/series/2017/09/25/a-complete-beginners-guide-to-django-part-4.html#introduction)


**download python**

**for manage different version of python. I advice you use Virtualenv. For each Django project, you first create a Virtual Environment for it. So you can play around, install packages, uninstall packages without breaking anything.**

```
firstly : sudo pip3 install virtualenv
1、mkdir myproject 
2、cd myproject
3、virtualenv venv -p python3
4、source venv/bin/activate
if you see(venv) in front of the command line, it worked.
if you want to exit if, you can write "deactivate"


pip install django. (Install django.)

```
# start a new project 

**django-admin startproject myproject**

```
run the django project 
```

**python manage.py runserver**

Now open the "http://localhost:8000" and you can see the worked page.
