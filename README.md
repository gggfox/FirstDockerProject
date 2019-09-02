Create a virtual environment in python named env
$ python -m venv env

Activate virtual environment
$ source env/bin/activate

install modules in our virtual environment
$ pip install flask uwsgi

#command to see files in virtual environment
$ pip list

$ pip freeze > requirements.txt

#Tutorial
https://pythonise.com/feed/flask/building-a-flask-app-with-docker-compose