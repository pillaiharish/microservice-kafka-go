# microservice-kafka-go

1. Topic :- (Once Written , can't be changed - Immutable)
      - Particular stream of data (in relational database we call it as table)
      - Identified by name , can have N' number of topics 
      -  any kind of formats (JSON,CSV,..)
      - topics cant be queried directly , send data to producer , use consumer to read data. 
      - can have many partitions - topic split into partitions
      - each partition have incremental id (ordered) called offset.

2. Kafka Producer - publish message to topics
3. Kafka Consumer - Subscribe message from topics 
4. Kafka Broker - manages the storage of messages in topics (persist and replicate) , more than one broker called cluster.
5. Kafka Zookeeper -  offers the brokers with metadata about the process running system, health checks and helps in broker leadership election.
