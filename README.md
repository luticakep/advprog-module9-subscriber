# Kayla Soraya Djakaria - 2306256381

1. What is amqp?

    `amqp` is a protocol for message-oriented middleware that allows communication between different applications or services.

2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for? 

    `guest:guest@localhost:5672` is a connection string for connecting to an amqp broker. The first `guest` is the username, the second `guest` is the password, and `localhost:5672` is the address and port of the broker.


### Simulation slow subscriber
![](rabbit.png)
The total number of messages in queue is 21. It is because the publisher sends messages at a faster rate than the subscriber can consume them, causing the messages to accumulate in the queue.
