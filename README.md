# simple-node-docker
Deploying a simple Node JS application, created using Express and Bootstrap, using Docker


This Node JS Application was built to demonstrate the creation of a simple web application that can server static pages as well.

Eventually the application and its dependencies are packaged into a Dockerfile for delivery.

You can refer to the docker-compose file for setting up the app with custom volume and network. 

The .travis.yml file tests the application, builds the Dockerimage and then uses the docker-compose.yml to deploy the app to verify the build's sanctity. 

# Order of Use
Clone/Fork the repository and integrate your Travis-CI and GitHub accounts. 
Set build triggers at Travis-CI and enter Docker Hub credentials in project environment variables. 
Start the build or wait for the trigger. 
