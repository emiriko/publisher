# Publisher with Message Broker

## Knowledge Check
1. How many data your publlsher program will send to the message broker in one run?

There are 5 data that will be sent by the publisher, because there is a publish_event call that carries out a `UserCreatedEventMessage` with 5 messages.

2. The url of `ampq://guest:guest@localhost:5672`, is the same as in the subscriber program, what does it mean?

This means that Subscribers and Publishers are connected to a message broker with the same `AMPQ` protocol. The broker is run on the same machine as the Subscriber, namely on localhost with port number 5672.

## RabbitMQ Management
![alt text](rabbitmq.png)

# Send Processing Event

![alt text](console.png)

## Monitoring Chart
![alt text](monitor.png)
