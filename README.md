# Kafka Docker Swarm deployment

Took some time to put together a docker stack definition that incorporates zookeeper image itsaur/zookeeper-replicated:3.5 and the kafka image ebezium/kafka:0.8. Here are the respective URL's
to find them:

- https://store.docker.com/community/images/itsaur/zookeeper-replicated
- https://hub.docker.com/r/debezium/kafka/

There is no guarentee whatsoever that this stack is optimal with regard to memory and cpu settings.
Use at your own risk!