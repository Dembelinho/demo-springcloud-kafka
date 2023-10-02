# demo-springcloud-kafka

## 1. Start KAFKA & ZooKeeper Server
The provided  **command** will start the **ZooKeeper server** using the specified configuration file, which is assumed to be located in the "config" directory.
```bash
bin\windows\zookeeper-server-start.bat config\zookeeper.properties
```
The provided  **command** will start the **Kafka server** using the specified configuration file, which is assumed to be located in the "config" directory within Kafka installation.
```bash
bin\windows\kafka-server-start.bat config\server.properties
```
You can execute the provided command 
```bash
bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R1
```
`bin\windows\kafka-console-consumer.bat`: This is the script used to start the Kafka console consumer on Windows.

`--bootstrap-server localhost:9092`: This part specifies the Kafka broker(s) to connect to. In this case, it's connecting to a broker running on the local machine (localhost) on port 9092.

`--topic R1`: This part specifies the Kafka topic from which you want to consume messages. 
<br><br>
Make sure to replace "R1" with the name of the Kafka topic you want to consume messages from. <br>
The Kafka console consumer will start, and you should see messages from the specified topic displayed in the command prompt.
<br><br>
![Capt screen 2023-10-01 cmd kafka](https://github.com/Dembelinho/demo-springcloud-kafka/assets/110602716/c942d75b-1fcc-48b9-992c-90a4b2a93ec6)        


## KAFKA-Consumer & KAFKA-Producer Test :
                
![Capture d’écran 2023-10-01 ii](https://github.com/Dembelinho/demo-springcloud-kafka/assets/110602716/22c8f65e-48c5-4bd6-81b1-50acf60d2af0)


![Capture d’écran (22)](https://github.com/Dembelinho/demo-springcloud-kafka/assets/110602716/cf2ca6b4-de4d-46c7-af65-d3692ec9c3ba)




