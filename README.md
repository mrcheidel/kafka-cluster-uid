# A Kafka Cluster with an Admin Web UI running on Docker

A docker-compose in order to create a Kafka Cluster + an Admin user interface.

Run the bellow command:
```
docker-compose -f docker-compose.yml up -d
```

Then open a web browser in http://localhost:8080

For more datails, please see the [Kafka UI](https://github.com/provectus/kafka-ui) repository.

Plus: This immplement also a Confluent [Schema Registry](https://docs.confluent.io/platform/current/schema-registry/index.html) and a [Confluent Kafka Connect](https://docs.confluent.io/platform/current/connect/index.html)

![](/resources/ss1.png)

![](/resources/ss2.png)

![](/resources/ss3.png)
