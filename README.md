# KafkaMicroServices

setup:

1. download kafka: \n
brew install kafka

2. edit listen host to localhost 9092 \n
vi /usr/local/etc/kafka/server.properties \n
eg: listeners=PLAINTEXT://localhost:9092

3.start zookeeper and kafka:\n
brew services start zookeeper \n
brew services start kafka

