# Netflix_clone
<a href="https://netflixclone-production-18e5.up.railway.app/watch/569d1312-063b-49c0-81f2-c040310cd13b/"> clickhere1<a/>

This is a clone of the popular video streaming site Netflix. Built using Django and uses the requests library.

![](https://github.com/steve-njuguna-k/Django-Netflix-Clone/blob/master/Screenshot.PNG)

## Requirements
The user can perform the following functions:

- A user can view the different movies and Tv shows that are available.
- A user can view a description Of the movie and its current rating.
- A user watch a trailer for a movie or a Tv Show.

## Installation / Setup instruction
The application requires the following installations to operate:
- pip
- gunicorn
- django
- postgresql
- requests

## Technologies Used
- python 3.10.7

## Project Setup Instructions
1) git clone the repository 
```
https://github.com/vcr11/Netflix_clone.git
```
2. cd into Netflix_clone
```
cd Netflix_Clone
```
3. create a virtual env
```
py -m venv env
```
4. activate env
```
env\scripts\activate
```
5. Open CMD & Install Dependancies
```
pip install -r requirements.txt
```
6. Make Migrations
```
py manage.py makemigrations
```
7. Migrate DB
```
py manage.py migrate
```
8. Run Application
```
py manage.py runserver
```
