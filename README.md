# Django File (and Image) Uploads

This repository contains my follow through the code from ['Django File (and Image) Uploads Tutorial'](https://learndjango.com/tutorials/django-file-and-image-uploads-tutorial) by W.S. Vincent

--
If you are searching for a Python / Django developer let's talk.  

You can reach me @

Linkedin: https://www.linkedin.com/in/guilherme-cavalcante-02417830/

Github: https://github.com/cavalcantegb

Email: cavalcante.guilherme91@gmail.com

# Running the project

This project was created using the packager and enviroment manager Pipenv, you can search more about its use [Pipenv Know The Basics](https://pipenv-fork.readthedocs.io/en/latest/basics.html).

Step 1.: Installing pipenv:

    pip install pipenv

Step 2.: Start the virtual environment and install the projects dependencies:

    pipenv install
    pipenv shell
   
Step 3.:  Running migrations:

    python manage.py makemigrations
    python manage.py migrate

Step 4.:  Create a superuser to access the admin area:

    python manage.py createsuperuser
Step5.: Run server:

    python manage.py runserver