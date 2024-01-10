# Ascent Essentials - Dockerized

This repository is useful to start the entire system (Backend, Database, and Frontend) with a single command.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Usage

1. Clone the repository and its submodules with the following command:

    ```bash
    git clone --recurse-submodules --remote-submodules https://github.com/AscentEssentials/ascent-essentials-docker.git
    ```

2. Start the system using Docker Compose:

    ```bash
    docker-compose up
    ```

3. Access the components:

   - **Backend:**
     - URL: [http://127.0.0.1:3000/](http://127.0.0.1:3000/)
     - API Documentation: [http://127.0.0.1:3000/api-docs](http://127.0.0.1:3000/api-docs)

   - **Frontend:**
     - URL: [http://127.0.0.1:4200/](http://127.0.0.1:4200/)

   - **MongoDB Dashboard:**
     - URL: [http://127.0.0.1:8081/](http://127.0.0.1:8081/)
     - Username: test
     - Password: test
