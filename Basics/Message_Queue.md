# Messaging Queue / Task Queue

eg -  RabbitMQ, ZeorMQ

##### Scenario

Multiple Clients order pizza when and they get responses immediately like "please sit down", "we will deliver your pizza in 10 minutes", "can you come back after sometime"
like a confirmation message.

Maintain a list of orders and notify the clients when the order is ready.
Add it to the Queue of Pizza Order
Once Pizza is done notify the clients and remove the order from the queue.
Best thing about this was the process was Asynchronous.

Consider there are 4 pizza shops and one of them goes down because of electricity outage. You can redirect the order to other shops. But because of the electricity outage, the order is not delivered to the client. So we need to persist the data.'

We need persistance in data !!


```
S0 <------>

S1 <------>

        Assignment/Notification + Notifier(heartbeat) + Load Balancing + Persistance <----------> Database                                                          

S2 <------>

S3 <------>

```

All of the Assignment/Notification + Notifier(heartbeat) + Load Balancing + Persistance is encapsulated in the messaging queue.

[Messaging Queue](https://www.youtube.com/watch?v=oUJbuFMyBDk&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=5)

