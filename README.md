# FlaskBlog_Tutorial
FlaskBlog Tutorial from https://www.youtube.com/watch?v=MwZwr5Tvyxo&amp;list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH&amp;index=1&amp;ab_channel=CoreySchafer

To run the application, you will need to set some environment variables:
SECRET_KEY - secret key for the flask application
SQLALCHEMY_DATABASE_URI - example:"sqlite:////site.db"
MAIL_USERNAME - any gmail account username
MAIL_PASSWORD

Will also need to create the sqlite db.
Open a python CLI, 
`from flaskblog import db`
`db.create_all()`

