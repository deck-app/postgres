# Postgresql & PgAdmin powered by compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd postgres`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **Abcd@1234**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **hello@get-deck.com**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **password**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** Abcd@1234 (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5050`
* **Username:** hello@get-deck.com (as a default)
* **Password:** password (as a default)

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `DB_USER`, by default: `postgres`
* **Password** as `DB_PASSWORD`, by default `Abcd@1234`