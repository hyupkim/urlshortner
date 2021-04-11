---------- Command Line ----------

> > django-admin startproject {PROJECT NAME}

> > django-admin startapp {APP NAME}

> > python3 manage.py runserver

> > python3 manage.py makemigrations

> > python3 manage.py migrate

> > python3 manage.py createsuperuser

> > pip3 install gunicorn

> > curl https://cli-assets.heroku.com/install.sh | sh

> > pip3 freeze > requirements.txt

> > heroku login

> > heroku create {APP NAME}

> > git init
> > git remote -v
> > git remote add {REMOTE NAME} {GIT URL}
> > heroku addons:create heroku-postgresql:hobby-dev
> > git add .
> > git commit -m"{COMMIT MESSAGE}"
> > git push {REMOTE NAME} master
> > heroku run python manage.py makemigrations
> > heroku run python manage.py migrate

Comment
The command "pip3 freeze > requirements.txt" does not properly generate a
requirments.txt file. Heroku fails to detect the language of the project.
Manually copy and paste the requirements to build successfully.

Hide Django Secret Key with .gitignore

If you already uploaded your secret file and trying to add on .gitignore,

> > git rm -rf --cahced .
> > Then add, commit, and push again.
