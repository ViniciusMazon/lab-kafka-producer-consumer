
Execute o comando para criar um topic
```bash
docker exec -it kafka /opt/bitnami/kafka/bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic test
```

# Construído utilizando
* [node-rdkafka](https://www.npmjs.com/package/node-rdkafka)
* [avsc](https://www.npmjs.com/package/avsc)