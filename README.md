TEST PROCESS FOR THE SCA-CLOUD APPLICATION.

I Started by creating a docker account to allow me build,run and manage my containers on a server.
I created index.html file where i wrote a text("Welcome to SCA Cloud School Application") that would be displayed in a webpage.
I linked my html file to my javascript file then clicked the go live to show the output.
I proceeded created a JavaScript file(app.js) and a Dockerfile.
In the docker file,i wrote a Dockerfile that builds an image which comes with other dependencies for example:FROM node:alpine,COPY . /app ,WORKDIR /app,CMD node app.js
After this process,i went to the terminal to pass commands.
I used the docker pull centos:latest pull command to download latest image from Docker Hub repositories.
I run the docker image with the following comand:docker run –it –name webserver centos:latest 
I received an output potraying my text in the webpage.
