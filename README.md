# project-awwards

>[Martin Mylles](https://github.com/coder-mylles/Awwards)  
  
# Description  
This project allows users to post their projects for other users to rate according to design, usability and content 
##  Live Link  
 Click [View Site](https://still-eyrie-12823.herokuapp.com/)  to visit the site

## Screenshots 
###### Home page

<img src="https://github.com/coder-mylles/Awwards/blob/main/static/images/Screenshot%20from%202021-07-21%2013-31-51.png">


## User Story  

* A user can view posted projects and their details.  
* A user can post a project to be rated/reviewed. 
* A user can rate/ review other users' projects.  
* Search for projects.  
* View projects overall score.
* A user can view their profile page.  



## Setup and Installation  
To get the project .......  

##### Cloning the repository:  
 ```bash 
 https://github.com/coder-mylles/Awwards
```
##### Navigate into the folder and install requirements  
 ```bash 
cd project-awwards pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  


## Technology used  

* [Python3.6](https://www.python.org/)  
* [Django 1.11](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  


## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  

## Contact Information   
If you have any question or contributions, please email me at [martin.mylles@student.moringaschool.com]  

## License 

* [![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](https://github.com/coder-mylles/Awwards/blob/master/LICENSE)  
* Copyright (c) 2021 **Martin Mylles**