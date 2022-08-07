# KafkaMicroServices

setup:

1. download kafka: 
brew install kafka

2. edit listen host to localhost 9092
vi /usr/local/etc/kafka/server.properties
eg: listeners=PLAINTEXT://localhost:9092

3.start zookeeper and kafka:
brew services start zookeeper 
brew services start kafka

