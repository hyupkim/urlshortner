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
