# Analysis and Design of Information Systems - National Technical University of Athens

## Tools
- Aapche Flink
- Apache Kafka
- Redis Data Platform
- Grafana

## How to run
The project can be run locally using the following commands:

- sudo systemctl start zookeeper 
- sudo systemctl start kafka 
- /usr/local/kafka/bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic TutorialTopic 
- /usr/local/kafka/bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic asynchronous
- .//home/panoplos/apache/flink/flink-1.16.1/bin/start-cluster.sh
- /usr/local/kafka/bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic TutorialTopic --from-beginning
- python flinkconsumer.py
- python3.10 producer.py