Movie API

An API interface to search and find movies by names, directors and genres.

It uses data from imdb.json

## Setting up project and initializing data
```
# create a virtualenv 
C:\Users\sray\Desktop\fynd\movie-master\movie-master>python -m venv myvenv
C:\Users\sray\Desktop\fynd\movie-master\movie-master>myvenv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 
```
Admin url : https://demo-moviedatabase.herokuapp.com/admin/

API request examples
base API url :
https://demo-moviedatabase.herokuapp.com/api/movies
filter by name (full text search)
https://demo-moviedatabase.herokuapp.com/api/movies?name=Cabiria
filter by movie name and director name
https://demo-moviedatabase.herokuapp.com/api/movies?name=Wizard&director=Victor
filter by genre name
https://demo-moviedatabase.herokuapp.com/api/movies?genre=family
