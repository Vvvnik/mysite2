# mysite2
 
 $ which python 
 /usr/bin/python

 $ python3 -m venv venv   # устанавливаем venv
 $ source venv/bin/activate  # активируем
 
 $ which python
 /home/vvv/PycharmProjects/pythonProject/mysite2/venv/bin/python   # OK
$ python -m pip install requests
$ export PATH=$PATH:/home/vvv/PycharmProjects/pythonProject/mysite2/venv/ # ???
$ echo $PATH
/home/vvv/PycharmProjects/pythonProject/mysite2/venv/bin:/home/vvv/anaconda3/bin:/home/vvv/.local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin
$ python -m pip install Django
$ python manage.py runserver

Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
March 20, 2021 - 14:55:36
Django version 3.1.7, using settings 'mysite2.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.        #YES!!!!!!!
