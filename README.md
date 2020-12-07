## BaScheD-Bot
An intelligent search engine for classifying the intent of the query. It uses LSTM model trained on the bbc dataset. It fetches the directory from Sharepoint.

# Installation 
After cloning the repo, follow the below steps to run the application -

# Frontend

$ cd front-end/basched-ui/src <br />
$ npm install <br />
$ npm start <br />

This should start the react frontend dev server on localhost:3000

# Backend

$ cd back-end/flask-api-backend <br />
$ python -m venv venv/ # create virtual env <br />
$ source venv/bin/activate # activate virtual env <br />
(venv) $ pip install -r requirements.txt <br />
(venv) $ python flask_api.py <br />

This should start the flask backend dev server on localhost:5000



