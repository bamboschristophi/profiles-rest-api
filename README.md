# Profiles REST API

**Project workspace**  
/Users/bambos/Code/courses/profiles-rest-api

## Git Repo

https://github.com/bamboschristophi/profiles-rest-api.git

## Vagrant

To Start Vagrant Server - navigate to project folder in Terminal  
**vagrant up**

You can ssh into the machine now.  
**vagrant ssh**

To halt the vagrant machine now.  
**vagrant halt**  

Other useful commands are **suspend, destroy** etc.

## Python Virtual Environment - On Server

create a virtual environment - this is done outside project folder to avoid the auto syncing  
**python -m venv ~/env**

activate/deactivate virtual environment - first navigate to vagrant folder on server
**source ~/env/bin/activate**  
**source ~/env/bin/deactivate**

## Django

Run Server (on server) in this location: (env) vagrant@ubuntu-bionic:/vagrant$  
**python manage.py runserver 0.0.0.0:8000**

view project on localhost  
**http://localhost:8000/**

## Atom   

| Info             | Command      |
|------------------|--------------|
| Command Palette  | CMD-SHIFT-P  |
| Markdown Preview | CTRL-SHIFT-M |

## To Do / Useful Stuff

* Get Markdown cheatsheet
* https://www.tablesgenerator.com/markdown_tables
