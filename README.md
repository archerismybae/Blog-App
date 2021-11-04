# Blog-App

## Introduction

A blogging web app created in Django that allows users to sign up and make blog posts that can be seen by everyone. Users also have the option of personalizing their account by adding Profile pictures and can also comment on posts.
(This was my final project for CS50x 2020, Harvard University's introductory class on Computer Science)

## Prerequisites

1. Must have Python (preferably version 3.9 or above) installed
2. Must have Django installed

## Steps to Run

1. Clone the repository

```
git clone https://github.com/archerismybae/Blog-App.git
```

2. Change into the directory

```
cd Blog-App
```

3.  Activate the virtualenv:

```
. django_project/env/scripts/activate
```

4. Change into the following directory:

```
cd django_project
```

and run the server:

```
python manage.py runserver
```

## Further Help

Import errors may be thrown in case a certain module in not installed. In such a scenario, please install the required modules.
Some of the modules that may be missing are:

1. The admin_interface module. Use the following command to install the module:

```
pip install django-admin-interface
```

2. The Crispy Forms module. Run the following command:

```
pip install django-crispy-forms
```

3. The PIL module. Use:

```
pip install Pillow
```
