
# Overview

This repository contains two docker images project. With the files in each folder, you can build image which enables you to run a streamlit web app used for viewing cvs files and making statistical summary of the cvs file. 
The two folders contain a dockerfile, .py file and requirements.txt files while the second one has compose.yml file which enables you to run multiple containers after you have built the image of your web app. 
The first one enables you to build a streamlit web app built without a database while the second one with compose.yml file has a postgres database. 

A CVS file for testing the app is the student.csv file attached to the repo

## Project 1
Docker repo link: https://hub.docker.com/r/sundayore/streamlitapp
#### To build the Image
Run this on your terminal

    docker pull sundayore/streamlitapp:v1

## Project 2
Docker repo link: https://hub.docker.com/r/sundayore/streamlitapp2
#### To build the Image
Run this on your terminal

    docker pull sundayore/streamlitapp2:v1
