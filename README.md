# Airflow Base Repository


## Desenvolvento o Workflow
Para trabalhar com este projeto, você precisa [Docker](https://docs.docker.com/install/) e [docker-compose](https://airflow.apache.org/docs/apache-airflow/stable/docker-compose.yaml).

### Utilizando o Airflow

Para todos os serviço:

```
docker-compose up -d
```

Depois, para derrubar todos os serviços:
```
docker-compose down
```

E, para reiniciar todos os serviços:
```
docker compose down && docker compose up -d
```

### Recriando o ambiente

```
docker-compose down --volumes --rmi all
```