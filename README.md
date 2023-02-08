# Introduction

a sandbox project for Apache Airflow.

# Official Documentation

`docker-compose.yaml` is copied from official apache airflow documentation
[Running Airflow in Docker](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html#fetching-docker-compose-yaml).

```sh
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.5.1/docker-compose.yaml'
```

and removed unnecessary ports.

# Run in Docker

Initialization is required once before running:

```sh
docker-compose up airflow-init
```

and then run:

```sh
docker-compose up
```

airflow webserver on http://localhost:8080
