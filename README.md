# Survey app

A basic survey web app written in Django with no JavaScript.

This is a website where users can create surveys and get answers to their questions. A user can sign up, create a survey, add questions to the survey, and then send a link to other people. When the survey is complete, the user can see what percentage of people answered each question.


# Setup

Requires Python 3 and the pip package manager.

windows commands to setup and run project
# Optional - create virtualenv
virtualenv survey-env (or) python -m venv survey-env
survey-env\Scripts\activate 
# Install requirements
pip install -r requirements.txt
# Setup database
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

# User journeys

There are two main user journeys, one for the users creating the surveys and another for the users taking the surveys.

