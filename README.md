# Wordpress Docker Compose file

## Setup and running
This docker-compose file is a pretty straight forward Wordpress setup, based on some other scripts I found in the web. Just run ```docker-compose up``` and you will be ready to go!

To access it, don't forget to get your Docker IP, which can be retrieved using ```docker-machine ip```. Don't forget that the default port is 8000 (so, to access it you will need to use http://IP:8000). You can modify it directly on the docker-compose file if you wish so.

## Cleaning everything
To clean everything (databases, persistence data and so on), you can use the following command: ```docker-compose down --volumes```

## Run it as a background task
To run it as a background task, you can use the ```docker-compose up -d``` do start it and ```docker-compose down``` to stop it.
