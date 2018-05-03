# Some docker recipes

All containers can configure the `VERSION` variable to set the container image version.

## Elasticsearch

Exposed to 9200 TCP port.

## Gitlab Runner

Copy `gitlab-runner/.env.dist` to `gitlab-runner/.env` and configure the `CI_SERVER_URL` variable.

## MariaDB

Copy `mariadb/.env.dist` to `mariadb/.env` and configure the `MYSQL_ROOT_PASSWORD` variable.
The variable `COMPOSE_PROJECT_NAME` configure the container, network and volume name.

Container is labeled as `db` and uses `db_network` network and `db_data` volume.

## RabbitMQ

Copy `rabbitmq/.env.dist` to `rabbitmq/.env` and configure the `.env` variables.
