# JobStream Helm Chart

This Helm chart deploys a Kubernetes application that includes the following services:

* Kafka Service: a messaging service that provides a scalable and fault-tolerant messaging system.
* Producer Service: a service that produces messages to the Kafka topic.
* Consumer Service: a service that consumes messages from the Kafka topic.
* Front Service: a service that provides a user interface to interact with the application.

The chart includes several dependencies, including Kafka, producer, and consumer services. These dependencies are defined in the `Chart.yaml` file.

To install the chart, run the following command:
```
helm install jobstream
```
This will deploy the application to your Kubernetes cluster.

For more information about the chart and its dependencies, please refer to the `Chart.yaml` file.
