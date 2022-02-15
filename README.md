# 2022_Scouting_App
# Prerequisite

install Python from [Download Python | Python.org](https://www.python.org/downloads/)

# Setting up Django environment

`cd 2022_app\2022_app\`

`.\Scripts\activate` 

`cd .\2022_scouting_app\`

`pip install -r .\requirements.txt`



# Generating the SQLite database

`python .\manage.py makemigrations matchscout`

`python .\manage.py makemigrations pitscout`

`python .\manage.py migrate`



# Running the APP

`python .\manage.py runserver`

## Finally, open up browser and navigate to http://127.0.0.1:8000/
