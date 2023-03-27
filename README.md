# Flask Social Media App
This is a social media web application built with Flask framework, which is a follow-through of the Flask Web Development book by Miguel Grinberg. This app allows users to create an account, log in, and post messages. Users can also follow each other,and comment on posts.

The app is built using Flask, SQLAlchemy, and Bootstrap. It uses Flask-WTF for form handling, Flask-Login for user authentication, and Flask-Mail for sending email notifications. The project follows the Model-View-Controller (MVC) pattern, and the codebase is structured using the Blueprint pattern.

## Features
* User authentication (registration, login, logout)

* Post creation, viewing, editing, and deletion

* User profile pages

* Following other users

* Commenting on posts

* Email sending

* Pagination of posts

## Installation
1. Clone this repository:

`git clone https://github.com/your-username/flask-social-media-app.git`

2. Activate virtual environment

`venv/Scripts/activate`

3. Install the dependencies:

`pip install -r requirements.txt`

4. Set the FLASK_APP environment variable:

`export FLASK_APP=flasky.py`

5. Run the app:

`flask run`

6. Visit [http://localhost:5000/](http://localhost:5000/) in your browser to access the app.
## Credits
This project was built by Faizol as a follow-through of the Flask Web Development book by Miguel Grinberg.