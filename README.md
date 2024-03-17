# Docker MariaDB

## Requirements

- Docker
- Docker Compose

## Building and Running the Project

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a `.env` file in the root directory of the project and set the `MYSQL_ROOT_PASSWORD` environment variable. For example:
   ```
   MYSQL_ROOT_PASSWORD=your_password
   ```
4. Build the Docker images using Docker Compose:
   ```
   docker-compose build
   ```
5. Start the services:
   ```
   docker-compose up
   ```

## Services

- **MariaDB**: A popular open source relational database. It is available on port `3310` of your local machine.
- **phpMyAdmin**: A free software tool written in PHP, intended to handle the administration of MySQL over the Web. It is available on port `8080` of your local machine.

Please ensure that the ports `3310` and `8080` are not being used by other services on your machine.
