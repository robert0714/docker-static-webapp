

## Basic Usage

run the commands to build and run the Docker image:
 
 ```bash
 $ docker build -t my-apache2 .
 $ docker run -dit --name my-running-app -p 8080:80 my-apache2

 ```
 
Visit http://localhost:8080 and you will see It works!

## Developing Single Page Application With Docker

run the commands to develop it .
 
 ```bash

 $ docker run -dit --name my-running-app -p 8080:80     -v $PWD/public-html:/usr/local/apache2/htdocs my-apache2

 ```
 Using Docker-compose
 ```bash

 $ docker-compose up -d 

 ```

