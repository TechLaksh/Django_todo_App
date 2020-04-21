"# Django_todo_App" 

**The Django python web framework used to create the TODO App using MYSQL as Database.**

```sh
#1.] Collect the static files
 >> $ python manage.py collectstatic
 
#2.] Make migration
 >> $ python manage.py makemigrations
 
#3.] Migrate
 >> $ python manage.py migrate
 
 #4.] Runserver
  >> $ python manage.py runserver
  ```


**Make sure update the [setting.py](https://github.com/yash2231/Django_todo_App/blob/master/TodoApp/settings.py)**

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'YOUR DB NAME',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': '127.0.0.1',
        'PORT': '3306',
        'init_command': "SET sql_mode='STRICT_TRANS_TABLES'",
    }
}

```


**#Landing page**

![home_page](https://github.com/yash2231/Django_todo_App/blob/master/screenshot/screeen_1.PNG)



**#Delete confirm**


![delete_msg](https://github.com/yash2231/Django_todo_App/blob/master/screenshot/screen_2.PNG)



**#Update**


![update](https://github.com/yash2231/Django_todo_App/blob/master/screenshot/screen_3.PNG)
