# Kafka

Kafka is a distributed messaging system which runs as a cluster of nodes.

**Components**

The key components in a Kafka based architecture are

* producers
* consumers
* brokers
* topics
* messages

*Broker*

Kafka is a distributed messaging system which runs as a cluster of nodes. Each node in a cluster is referred to as a broker.

*Topic*

The messages sent through Kafka are categorized into groups known as topics.

*Producers*

An application that publishes messages to a Kafka topic is known as a producer.

*Consumers*

An application that subscribes to a Kafka topic and processes messages is knownn as a consumer.

**Partitions**

A topic in Kafka can be split into partitions.


**Messaging Models**

Kafka supports the following messaging models

* Queuing
* Publish-Subscribe

**Features**

Kafka uses ZooKeeper to form the cluster nodes.

Kafka can be used to receive data and forward it to Spark Streaming. 
