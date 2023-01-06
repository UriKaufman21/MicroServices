# MicroServices
Hello! Here I'm planning to implement a Microservice arcitecure that will include:
1. 2 Microservices that do the actual work
2. The input will be read from a kafka topic
3. The output will write to one
4. The communication between the two will be done using a API call that a third microservice will handle + The reading from kafka
5. All microservices will write logs with a deamon process
6. The logs will be processed with filebeat, sent to logstash and then to elastic search
7. Optionally, monitoring will be added
8. At the beggining this will all be done with docker compose, eventually kubernetes
9. Injection abillities for custom service might be added 
10. I want to be able to use the whole microservice arcitecture without it knowing about kafka or elastic
11. Everything should be scalable, think what happenes if 10000 messeges arrive every second and some take a long time to process and with no loss of messages

**Good Luck!**

