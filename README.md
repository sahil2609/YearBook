# [SAIL YearBook Portal](https://www.iitg.ac.in/yearbook)

The clean, fast and right way to start a new Django powered website.

## Getting Started

Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r https://raw.githubusercontent.com/juanifioren/django-project-template/master/requirements.txt

# You may want to change the name `projectname`.
$ django-admin startproject --template https://github.com/juanifioren/django-project-template/archive/master.zip projectname

$ cd projectname/
$ cp settings_custom.py.edit settings_custom.py
$ python manage.py migrate
$ python manage.py runserver
```

## Features

* Basic Django scaffolding (commands, templatetags, statics, media files, etc).
* Split settings for specific environment settings (localhost, production, etc) in `yearbook/settings.py`.
* Simple logging setup ready for production envs.

## Contributing

Send a pull request with clear details including the brief documnetation and a picture ( in case of any frontend changes ).
