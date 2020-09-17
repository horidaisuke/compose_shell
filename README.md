# Compose Shell

Docker compose command utility, collection of convenient shortcuts

## What is this?

`compose` is shell script of docker-compose command utility, collection of convenient shortcuts on development environments.

## Install and use

You can copy and use anywhere(or into bin path) simply.
It has some convenient shortcuts options for docker-compose.

* `compose up` - start up to service(s) defined into docker-compose 
* `compose halt` - stop to service(s) defined into docker-compose
* `compose reload` - restart to service(s) defined into docker-compose
* `compose destroy` - stop and terminate service(s) defined into docker-compose
* `compose build` - build docker image(s) defined into docker-compose
* `compose ps` - show process of service(s) defined into docker-compose
* `compose volume` - show list data volume(s) defined into docker-compose 
* `compose volume rm [data_volume_name..]` - remove data volume(s) defined into docker-compose

Other options is passed to docker-compose command as is.

## License

This software is free and unencumbered software released into the public domain.
