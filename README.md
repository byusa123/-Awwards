

#### a project he/she has created and get it reviewed by his/

## Description

aWWWards is a web app where users submit their projects and other users get to review and rate them.The inspiration behind this project is from the [awwwards](https://www.awwwards.com/) app.



## Author

 [byusa uwase giselle](https://github.com/byusa123)

## Set up instructions and installations

### Prerequisites

- python3.6 

- python virtual environment ~ to create one run the following command `python3.6 -m venv --without-pip virtual`

- python pip ~ to install pip activate virtual environment `source virtual/bin/activate` then run `curl https://bootstrap.pypa.io/get-pip.py | python`

- Postgres ~ to install follow the following commands in your home directory:
    - `sudo apt-get update`
    - `sudo apt-get install postgresql postgresql-contrib libpq-dev`
    - `sudo service postgresql start`
    - `sudo -u postgres createuser --superuser $USER`
    - `sudo -u postgres createdb $USER`
    - `touch .psql_history`

### Installation instructions

- Clone the repo

- Activate virtual environment: 
   `python3.6 -m venv --without-pip virtual` then `source virtual/bin/activate`

- Install all the dependancies in the requirements.txt file to get a development env running
   `pip3 install -r requirements.txt`

- Create a database 
  ```bash
  psql
  CREATE DATABASE awwards;
  ```





- Run the app

   - `python3.6 manage.py runserver`

- Open the `localhost:8000` to check if the app is running successfully.

### Dependancies

All the project's dependancies are found in the requirements.txt file.Open it for reference.

## Known bugs

Some functionality not fully implemented

## Technologies used

    - python3.6
    - Django1.11
    - HTML
    - CSS
    - Bootstrap
    - Postgresql



## Contacts

For help and support feel free to contact me : byusagisele@gmail.com

## License

> MIT License

> Copyright (c) 2021