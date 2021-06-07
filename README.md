# python-node

#############################################################

# virtualenv:
 
# Clear Windows Terminal:

	cls

# Create Virtual environment:
	
	pip install virtualenv

Then Goto Project Folder & Run
	
	virtualenv nameOfVirtualenv

Then Inter nameOfVirtualenv
	
	cd nameOfVirtualenv

Then Enter Scripts For Windows:
	
	cd Scripts

Then Active/Deactive virtualenv:
	
	activate/d+Tab



##########################################################################
# install all packege django project
    
    pip install -r requirements.txt

# package list:
    
    pip list

# install Django:
    
    pip install django

# Django Version check
    
    python -m django --version


# Create Django Project on windows:
    
    python -m django startproject crud
    
    django-admin startproject mysite

# run Server:
    
    python manage.py runserver

# create App:
    
    python manage.py startapp users

# migrate DB:
    
    python manage.py migrate        

# install postgres package:
    
    pip install psycopg2

after create model:
    
    python manage.py makemigrations   

Form Package:
    
    pip install django-crispy-forms     

# Create Environment Variable:
    
    pip install python-decouple
    then import it settings.py file
    from decouple import config

For Image:
    
    pip install Pillow

for filter Data:
    
    pip install django-filter 

#########################################################################

Push an Existing Project to GitHub

    git init
    git add -A
    git commit -m 'Added my project'
    git remote add origin git@github.com:sammy/my-new-project.git
    git push -u -f origin master


##########################################################################

# Docker Command:

# Config;
	docker build .   

# create Django  Project: 
	docker-compose run app sh -c "python -m django startproject app ."

# test command:
	docker-compose run app sh -c "python manage.py test"
