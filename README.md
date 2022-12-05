# Django_setup

**Pre-requesite**
  - Python

 **How to install Django**
 
  - Install using following command
  
    ``` pip install django```
    
**How to create virtual environment**
  - Install virtual environment using following command
  
    ``` pip install virtulenvwrapper-win ```
    
  - make environment using one of the following command 
  
    ``` virtualenv <env_name> ```
  
    ``` mkvirtualenv <env_name> ```
    
    ``` python3 -m venv <env_name>```
  
  - If there is issue during the making environment run following command
  
     ```Set-ExecutionPolicy RemoteSigned```
     
     Run above command of make virtual env in Python 
  - Activate the environment 
  
    ```.\<env_name>\Scripts\activate```
    
  - Install Django
  
    ``` pip install Django ```
    
  - Start Prject
   
    ``` django-admin startproject <project-name> ```
    
    ``` cd <project-name>```
    
  -  Create Django app
    
     ```python manage.py startapp myapp```
