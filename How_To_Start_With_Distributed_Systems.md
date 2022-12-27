


### 🍕 PIZZA SHOP SCENERIO

Suppose you have a pizza shop and you want to scale what will you do:

1. Hire a chef, Pay him more (Vertical Scaling : optimise precision and increase through put with the same resources)
2. Preparing Ingredients for cooking and stuff before hand (preprossing (e.g cron job) : prepare before hand during non pick hours)
3. Now what If the chef get sick or on leave, (Single Point of Failure) - Keep Backups 
4. Hire More Chef (Master-Slave Architecture) (Horizontal Scaling: get more resources)
5. Different Chef have different speciality  - how can you route orders leveraging their strengths - (Micro Service Architecture)
6. What if their is Electricity Outage - (Distributed System (partioning))
7. Customer wants to order and we have Two Pizza shops open - which shop is closer, would serve faster ?  (Load Distribution and Load Balancer)
8. Delivery Agent and Customer can take the order our Pizza shop doesnt care. (Decoupling - Separating out concerns to handle them independently)
9. Pizza oven is broken, Delivery Agent is sick resulting in delay in delivery. (Logging and Metrics Calculation)
10. Scale out by Decoupling (Extensible)


Points to Remember: 

```

1: vertical scaling: optimise precision and increase through put with the same resources 
2: preprossing (e.g cron job) : prepare before hand during non pick hours 
3: Backups: keep backups and avoid single point of failure 
4: horizontal scaling: get more resources 
5: micro service architecture 
6: distributed system (partioning)
7: load distribution and Load Balancer
8: Decoupling 
9: Logging 
10: extensible 
```