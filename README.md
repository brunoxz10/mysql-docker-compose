# MySQL and Adminer

Docker compose with MySQL and Adminer, for local development.

## Overview

This repository contains a Docker Compose configuration for setting up a local environment with MySQL and Adminer.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

Follow these steps to set up and run.

1. Clone this repository:

   ```bash
   git clone https://github.com/brunoxz10/mysql-docker-compose.git

2. Navigate to the project directory:

    ```bash
    cd mysql-docker-compose

3. Change MYSQL_ROOT_PASSWORD if you want.

4. Run the Docker Compose command to start the services:

    ```bash
    docker-compose up -d

This command will download the necessary Docker images and start the MySQL and Adminer containers.

5. Access Adminer in your web browser:
Adminer URL: http://localhost:8080

6. Login:
System: MySQL
Server: db
Username: root
Password: As specified in MYSQL_ROOT_PASSWORD

## Stopping the Environment

    ```bash
    docker-compose down