# Poster-Recognition
Machine Learning, Deep Learning

Poster 1recognition Project Demo to check, if a single poster is there or not in a group-poster image

This demo is done in python3 & Flask

Need to install via pip3 for the Demo
install python3
install flask

It contains the following folders:
templates: to keep the HTML pages for Flask
static: CSS and JS should inside the static folder for Flask
uploads: all uploaded files goes here before categorized them into poster or trained images
train: to keep the train images
trainSmall: to keep the resized train images
poster: to keep the uploaded group-poster images
posterMid: to keep the resized group-poster images which are used during comparing with trained images
posterSmall: to keep the small resized group-poster images which are used during uploading to check for duplicates

After all those installation need to 
Run flask server

Main file to run : app.py
python3 app.py
