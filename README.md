# Kafka Example
	
A Simple producer/consumer clients example of kafka, you should have kafka up and running, and you change the configs [here](src/main/java/com/med8bra/kafka/constants/IKafkaConstants.java).

## Run (Java 8)

To run the producer :
```sh
$ java -jar target/kafka-example-jar-with-dependencies.jar produce
```

To run the consumer :
```sh
$ java -jar target/kafka-example-jar-with-dependencies.jar consume
```