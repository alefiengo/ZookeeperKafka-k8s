# Getting Started

### k8s
Deploy Zookeeper, Kafka and Kafka UI
```
kubectl apply -f zookeeper-kafka-ns.yaml
kubectl apply -f zookeeper
kubectl apply -f kafka
kubectl apply -f kafka-ui
```

### Kafka UI
Open local kafka-ui in a browser

[http://SERVICE_IP:8080](http://SERVICE_IP:8080)