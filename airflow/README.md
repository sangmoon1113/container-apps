
# Apache Airflow
* Apache Airflow: https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html
* Docker Hub: https://hub.docker.com/r/apache/airflow

## docker-compose
* `docker-compose.yml` : `curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.8.2/docker-compose.yaml'`

## init
```bash
docker compose up airflow-init
```

## run
```bash
docker compose up 
```

## cleaning up
```bash
docker compose down --volumes --rmi all
```