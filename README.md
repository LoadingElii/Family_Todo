# Family_Todo

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

'''code
pip install virtualenv
'''

Next is to create a virutal enviroment:

'''code
python -m venv venv-name
'''

Then activate the virtual enviroment:

-For *Windows*

'''code
path\to\venv-name\Scripts\activate.bat
'''

-For *Linux*

'''code
source path/to/venv-name/bin/activate
'''












