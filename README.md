# This repository is based on [piomin/sample-spring-reactive](https://github.com/piomin/sample-spring-reactive)
all versions are updated to the latest according to the updated date.

## Install Docker first:
[Install Docker for Mac](https://docs.docker.com/docker-for-mac/install/)

[Learn Docker for MongoDB](https://docs.docker.com/engine/examples/mongodb/#using-the-mongodb-image)


## Run Docker for MongoDB:
`docker run -d --name mongo -p 27017:27017 mongo`

## Run Maven at root folder:
`mvn clean install`

## `cd` to `account-server` folder and run `mvn spring-boot:run`
open browser [localhost:2222](http://localhost:2222)

## `cd` to `customer service` folder and run `mvn spring-boot:run`
open browser [localhost:2223](http://localhost:2223)

