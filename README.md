# postgre-pgadmin-docker

## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd postgre-pgadmin-docker`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **zilehuda**
* `POSTGRES_PASSWORD` the default value is **wzone.io**
* `PGADMIN_DEFAULT_EMAIL` the default value is **zilehuda@wzone.io**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **wzone.io**

## Access to postgres: 
* `localhost:5432`
* **Username:** zilehuda (as a default)
* **Password:** wzone.io (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:444`
* **Username:** zilehuda@wzone.io (as a default)
* **Password:** wzone.io (as a default)

* The default port for postgres is **5432**
* The default port for pgadmin is **444**
