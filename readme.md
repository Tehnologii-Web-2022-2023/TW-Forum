# Discussion Forum - TW Project

## Table of contents

- Summary
- Requirements
- Installation
- Usage
- Credits


## Summary

This app is a forum meant to be used by university students and professors. Users may open a new discussion on any existing tag (tag representing universities or any other fields of interest) or create a new tag by creating a new discussion on the front page.
It is not necessary to log in to read any existing discussion, however, it is needed if one intends to contribute or open a new discussion. 
Currently, anyone may sign up. 
Additionally, users may get notifications related to the platform (Ex. Maintenance on 19th of July)

Under the hood, Angular, Flask and MySQL was used. An ERD diagram is included below

#
![ERD diagram](https://user-images.githubusercontent.com/92172532/212942788-c998e778-8c2e-475b-9412-fbeaaee7b136.png)

## Requirements

Backend:
- Python 3.x & pip
- PyJWT ~= 2.6.0
- DateTime ~= 4.7
- Flask ~= 2.2.2
- Werkzeug ~= 2.2.2
- SQLAlchemy ~= 1.4.45
- requests ~= 2.28.1

DB:
- MySQL 8.0



## Installation

Backend:
For backend it is enough if you install a Python 3.x interpreter that has also pip. After installing pip, you can install the rest of the dependencies using requirements.txt (`pip install -r requirements.txt`)

DB: (Optional)
If you want a local DB or don't have a hosted MySQL server, you can install it from the official MySQL website. (https://www.mysql.com/downloads/)


## Usage

Runing the app:

- Backend
  At the parent directory of the backend part, run the following commands:
  Windows:
  `set FLASK_ENV=development`
  `set FLASK_APP=app`
  `flask run`
  Unix:
  `export FLASK_ENV=development`
  `export FLASK_APP=app`
  `flask run`
  
Using the app:
 
The WebApp is very user-friendly, intuitive, thus there's no reason to go into details. After running the frontend and backend, accessing http://localhost:4200/ you may use it freely.
  

## Credits

Frontend - Vaduva Vlad-Andrei
Backend + DB - Nevezi-Strango David

Some source code were inspired from laboratory materials (https://en.wikiversity.org/wiki/Tehnologii_Web%2F2022-2023)
