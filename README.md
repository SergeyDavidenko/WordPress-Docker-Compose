# WordPress Docker Compose

docer-compose.yml witch WordPress MySQL and phpmyadmin

## Requirements

**[Docker](https://docs.docker.com/install/)** and **[Docker Compose](https://docs.docker.com/compose/install/)**  installed on your machine.

## Configuration

Edit the `.env` file to change the port, MySQL version root password and WordPress database name.

## Usage

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
docker-compose up -d
```

## Removing containers

To stop and remove all the containers use the `down` command:

```
docker-compose down
```