
* Apache Airflow: https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html
* DockerHub: https://hub.docker.com/r/apache/airflow


## docker-compose.yml
```bash
curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.8.2/docker-compose.yaml'
```

## .env
```
AIRFLOW_UID=50000
```

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