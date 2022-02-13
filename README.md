# Flask_Movies
Web app using Flask
# FlaskWebApp
Web app using python's flask

## First clone current repository
``` $ git clone https://github.com/al1998petridis/Flask_Movies.git ```

Go to cloned directory with ``` $ cd Flask_Movies/ ```

## Create virtual enviroment using python virtualenv
``` $ virtualenv flaskapp ```

## Open virual enviroment
``` $ source flaskapp/bin/activate ```

## Install dependencies
``` (flaskapp) $ pip install -r requirements.txt ```

## Create database
### First go to /src folder
``` (flaskapp) $ cd /src ```
### Open python
``` (flaskapp) $ python ```
### Create database
``` (flaskapp) >>> from FlaskMoviesApp import db ```

``` (flaskapp) >>> db.create_all() ```

``` (flaskapp) >>> exit() ```

## Start server 
### Start Server
``` (flaskapp) $ python run.py ```
## Enjoy from your browser
Running on http://127.0.0.1:5000/
