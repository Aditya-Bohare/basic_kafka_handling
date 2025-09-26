# basic_kafka_handling
this shows us how kafka handles the producer and consumer with multiple consumer and partitioning the topic in broker..

## Basic Setup.
### run this command for basic node and kafkajs setup 
```bash
npm init
npm install
```

### run this command to run the docker image
if you dont image locally then itll pull the image from docker hub
```bash
docker-compose up -d
```

### run this command for creating the topic inside these broker.
```bash
node admin.js
```
### run this command for creating producer.
```bash
node producer.js
```
here you can put two input name and north or south value. ex:-(aditya south)

### run this command for creating consumer.
you can create as many as cosumer you want depending upon the partition provided and consumer group as well..
create this consumer in another terminal..
```bash
node consumer.js
```
## workings