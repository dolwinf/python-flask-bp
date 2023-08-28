## Python Flask API Boilerplate

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This is sample dockerised boiler plate for creating a REST api using Flask and friends in Python.
Code from blog post https://rest-apis-flask.teclado.com/docs/first_rest_api/getting_set_up/

## To run the app

- Install docker
- Run the command - docker build -t your-image-name .
- Run the command -docker run -p 5000:5000 your-image-name
- APIs are self documenting, to test if the app is running, on your browser go to http://localhost:5000/swagger-ui
