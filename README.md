# Awwards App

##### By Brian Jomo.

### It is a description of the Awwards App.

## Table of Content

+ [Description](#description)
+ [Installation Requirement](#Installation)
+ [Technology Used](#technology-used)
+ [Reference](#reference)
+ [Licence](#licence)
+ [Authors Info](#author-Info)

## Description

<p>This project entails creating a website similar to Awwards. Web visitors of this website can create a secure account, post a project, view and rate other user projects. Users can also search for and view performance score of their projects.</p>

## Installation

To gain acess to this application click on this link: https://github.com/BrianJomo/Project-Host

### Requirements

* Either a computer,phone,tablet or an Ipad.

* An access to the Internet.

### Installation Process

To access this application, type the following command in your terminal to have a local copy of the application.
```
https://github.com/BrianJomo/Project-Host.git
```
and for SSH, use the following command;
```
git@github.com:BrianJomo/Project-Host.git
```

### Setting up environment variables

Create a `.env` file and paste paste the following and fill where appropriate:

```
SECRET_KEY='**'
DEBUG=True
DB_NAME='****'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```

Then run the following commands in the terminal then run the manage.py file in order to run the web application.

```
$ python3.8 -m venv --without-pip virtual

$ source virtual/bin/activate

$ curl https://bootstrap.pypa.io/get-pip.py | python

$ pip3 install -r requirements.txt 

$ python3.8 manage.py check

$ python3.8 manage.py makemigrations <installed app name>

$ python3.8 manage.py sqlmigrate <installed app name> 0001

$ python3.8 manage.py migrate

$ python3 manage.py runserver

```

To explore the features of this instagram clone website navigate to this link on your browser or just click on this link: 


## Technology Used

* Python - Which was used to structure and build the logic hence interactive with the client-side and server-side.

* HTML - which was used to build the structure of the web pages.

* CSS - which was used to style the web pages.

* Bootsrap - which was also used to style the web pages.

* Django - Which made creating web applications in Python easier.

* Postgresql - Which was used as a database for data storage.


## Reference

* PEP 8 – Style Guide for Python.

* Materialize CSS.

* Django documentation.


