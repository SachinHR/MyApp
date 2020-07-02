# MyApp

## Install
```
sudo apt install python3-pip
pip3 install virtualenv
pip install --upgrade pip
```
## Clone this repository

git clone https://github.com/SachinHR/MyApp.git

## Create Environment
```
python3 -m virtualenv Env
source Env/bin/activate
```
# Install Django
```
pip3 install django
```
## Open terminal and Start server
```
python manage.py runserver
```
## Open another new terminal and create account
```
python manage.py createsuperuser
```
## Home Page
[BLOG](http://127.0.0.1:8000/admin/login/?next=/admin/)

## Python 
1. Create a simple blogging application using Python /Django        
2. Front end can be simple                                          
3. Backend should support all CRUD operations for Data with REST APIs
4. User should be able to post a blog after logging in                
5. Only the user who posted should be able to edit or delete the blog
6. Other users should be able to reply to the posts. 
7. Use your own DB and if possible, host it on a cloud                
