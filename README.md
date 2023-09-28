# Introducing

The project includes docker-compose file to run Grafana and Postgres in Docker. 
Grafana will be exposed on 3000 port.

More information about Grafana: [Grafana official site](https://grafana.com/docs/grafana/latest/)
More information about PostgreSQL: [PostgreSQL official site] (https://www.postgresql.org/about/)

## Running Grafana and PostgreSQL in Docker

### Running

```sh
docker-compose up -d
```
Grafana will be available on the port 3000.

### Stopping

```sh
docker-compose stop && docker-compose rm
```