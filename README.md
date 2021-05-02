# flask-demo-app
This repository contains a simple Flask (Python) based web application.

## Task
Create a Dockerfile with suitable commands to create an image that enables a container to run this application on port 5685, after installing any necessary dependencies.
Creation of Dockerfile is enough, and creation of the image is not necessary.
The created Dockerfile can be uploaded in the last section of the questionnaire given in the instructions.

## Description of the App

### Routes
* __`*GET /*` :__  Renders the homepage, prompting the user to enter his/her name.
* __`*POST /mainpage*` :__ Renders a page, that displays a greeting with the name given by the user in the main page

### Files/Folders

* __app.py :__ Entry point for the application
* __requirements.txt :__ Contains the list of necessary dependencies for the app to run.
*  __templates :__ Folder containing templates
   * __index.html :__ Template for `GET /`
   * __mainpage.html :__ Template for `POST /mainpage`
