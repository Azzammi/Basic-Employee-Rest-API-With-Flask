# Basic Employee Rest API With Flask

## Requiremnt
1. Flask
2. Flask Alchemy

## Seeding Database
`python
from app import db 
db.create_all()
from app import Employee`

`emp = Employee(firstname="John",lastname="Doe", gender="Male", salary=2500000)
db.session.add(emp)
db.session.commit()`

## How to Run The app
1. `flask run` or
2. `python -m flask run`

## Resource Learning
https://www.youtube.com/watch?v=G3lPb6mlqTA&t=295s
`
