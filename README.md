# docker-compose-examples
A repo containing a number of docker-compose examples for commonly used containers (e.g. message brokers and databases)

# Getting started
Ensure that you have [Docker](https://www.docker.com/products/docker-desktop) installed on your machine.

Run the command required for the container that you wish to start:

| Container   | Command                            | Port   |
| ----------- | ---------------------------------- | ------ |
| Kafka       | `docker-compose up -d kafka`       | 29092  |
| DynamoDB    | `docker-compose up -d dynamodb`    | 8000   |
| MongoDB     | `docker-compose up -d mongodb`     | 27017  |
| Postgres    | `docker-compose up -d postgres`    | 5432   |

