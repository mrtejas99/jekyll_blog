---
layout: post
title: "Deploy Python Flask App on Heroku"
date: 2022-11-10T11:24:26+05:30
categories: tutorial
---

Flask is a web application framework written in Python. Flask is based on the Werkzeug WSGI toolkit and Jinja2 template engine. Both are Pocco projects. This article revolves around how to deploy a flask app on Heroku. To demonstrate this, we are first going to create a sample application for a better understanding of the process. 

### Prerequisites 
- Python
- pip
- Heroku CLI
- Git
 

### Deploying Flask App on Heroku
Let’s create a simple flask application first and then it can be deployed to heroku. Create a folder named `eflask` and open the command line and cd inside the `eflask` directory. Follow the following steps to create the sample application for this tutorial.

**STEP 1 :** Create a virtual environment with pipenv and install Flask and Gunicorn .

    $ pipenv install flask gunicorn 

**STEP 2 :** Create a `Procfile` and write the following code. 

    web:gunicorn wsgi:app

**STEP 3** : Create `runtime.txt` and write the following code.

    python-3.7.5

**STEP 4 :** Create a folder named “app” and enter the folder. 

**STEP 5 :** Create a python file, `main.py` and enter the sample code.
```python
from flask import Flask
 
app = Flask(__name__)
 
@app.route("/")
def home_view():
        return "<h1>Hello world</h1>"
```
**STEP 6 :** Get back to the previous directory `eflask`.Create a file `wsgi.py` and insert the following code.
```python
from app.main import app
 
if __name__ == "__main__":
        app.run()
```

**STEP 7 :** Run the virtual environment.
 
    $ pipenv shell 
    
**STEP 8 :** Initialize an empty repo, add the files in the repo and commit all the changes.
 
```bash
$ git init 
$ git add .
$ git commit -m "Initial Commit"
```

**STEP 9 :** Login to heroku CLI using 

    heroku login

Now, Create a unique name for your Web app.
 
    $ heroku create eflask-app
 
**STEP 10 :** Push your code from local to the heroku remote. 

    $ git push heroku master
 
Finally, web app will be deployed on http://eflask-app.herokuapp.com. 
 

