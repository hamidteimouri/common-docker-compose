# common-docker-compose
There are several docker-compose To runKafka, mysql and ... .<br>
This repo includes :
1. Kafka
2. Clustered Kafka
3. Mysql & PhpMyadmin
4. Postgres & PgAdmin
5. ELK (Elasticsearch, Logstash, Kibana)
6. Redis
7. RabbitMQ

## Kafka
- Kafka
- Kafka Zookeeper
- Kafka UI

To run kafka use command below:
```shell
docker compose -f docker-compose.kafka.yml up -d
```


## Kafka-Cluster
- Kafka (3 nodes)
- Kafka Zookeeper (3 nodes)

To run kafka-cluster use command below:
```shell
docker compose -f docker-compose.kafka-cluster.yml up -d
```


## MySQL
- MySql
- PhpMyAdmin

To run Mysql use command below:
```shell
docker compose -f docker-compose.mysql.yml up -d
```

## Postgres
- Postgres
- PgAdmin

To run Postgres use command below:
```shell
docker compose -f docker-compose.postgres.yml up -d
```

## ELK
- Elasticsearch
- Logstash
- Kibana
 
To run ELK use command below:
```shell
docker compose -f docker-compose.elk.yml up -d
```

## Redis
- redis
 
To run redis use command below:
```shell
docker compose -f docker-compose.redis.yml up -d
```

## RabbitMQ
- rabbitmq
- rabbitmq-panel
 
To run rabbitmq use command below:
```shell
docker compose -f docker-compose.rabbitmq.yml up -d
```