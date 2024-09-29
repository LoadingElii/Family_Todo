# Family_Todo
## General Overview:
For familes who want to add a little organization to their lives.
In today's world it's easy to get overwhelmed with task and errands.
All to often we forget to do something.

That is the problem thst this App fixes!
Every member has there own personal list of things they need to do.
Members part of a family have access to the family's todos as well.

I have made a video tutorial building showing
how to build this application step by step.

link to video:******

An Flask API used to perform 
CRUD(Create, Read, Update, Delete) on:
- Family Objects
- Member Objects
- TodoItem Objects

## Tech Used:

1. Flask
2. SQLAlchemy
3. Pyjwt
4. Python-dotenv
5. PostgreSQL

## Key Features:

### Family objects

1. Contains a list of Members
2. Contains a list of TodoItems

### Member objects 

3. Contains a list of TodoItems
4. May be a Member of a Family
 
### TodoItem objects 

5. Contains a Description field
6. Contains a Urgency field
7. Contains a Completed field

## Setup

First step is install *virtualenv*:

'''bash
pip install virtualenv

'''

Next is to create a virutal enviroment:

'''bash
python -m venv venv-name

'''

Then activate the virtual enviroment:

-For *Windows*

'''bash
path\to\venv-name\Scripts\activate.bat

'''

-For *Linux*

'''bash
source path/to/venv-name/bin/activate

'''

In the the main directory there is a *requirements.txt file.
Which is used to install the required dependencies 

How to use *requirements.txt*:

'''bash
pip install -r requirements.txt

'''

Add your own *.env* file to your project.
Put your environment properties in there.


To start the Flask Application on a development server 
run command in your application main folder:

'''bash
flask --app app run

'''

## Usage

### Admin endpoints:

### Family endpoints:

### Member endpoints:

### TodoItem endpoints:

## Project Status

- In progress

## Room for Improvement

-Implement feature to allow a family member to add todo 
from family's todo list to member todo list.

##Acknowledgements
















