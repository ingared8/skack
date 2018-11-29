# SKACK

### Spark, Kafka, Akka and Cassandra on Kuberntes

This helm charts provides an easy way to install Spark, kafka and Cassandra on kubernetes. 


```helm repo add ingared  https://ingared8.github.io/skack/```

```helm repo search spark```

```helm install --name {CUSTOM_NAME} ingared/spark```

```helm install --name {CUSTOM_NAME} ingared/kafka```

```helm install --name {CUSTOM_NAME} ingared/cassandra```


