# FlaskBlog_Tutorial
FlaskBlog Tutorial from https://www.youtube.com/watch?v=MwZwr5Tvyxo&amp;list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH&amp;index=1&amp;ab_channel=CoreySchafer

# To run the application in a linux machine: 
## install pip:
`sudo apt install python3-pip`
## install python3-venv:
`sudo apt install python3-venv`
## create virtual env:
python3 -m venv Flask_Blog/venv
## activate virtual env:
`source venv/bin/activate`
## install dependencies:
pip install -r requirements.txt
## set required environment variables:
SECRET_KEY - secret key for the flask application
SQLALCHEMY_DATABASE_URI - example:"sqlite:////site.db"
MAIL_USERNAME - any gmail account username
MAIL_PASSWORD
## create the sqlite db.
Open a python CLI, 
`from flaskblog import db`
`db.create_all()`
## run the application
`python3 run.py`

