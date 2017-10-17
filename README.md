# Investigating using Apache Beam with Apache Kafka

* Start Kafka
    * `make up`
* Create the Kafka topic
    * `make topic`
* Ensure it has been created
    * `make describe`
* Use Beam to write to topic
    * `make producer`
* Check messages in topic
    * `make offset`
* Dump messages from topic
    * `make dump`
* Consume messages and run wordcount with Beam
    * `make consumer`
* Check output
    * `cat wordcount*`
* Clean up
    * `make clean`