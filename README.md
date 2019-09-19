# Publisher-Subscriber-System-using-Docker
Implemented centralized and distributed Pub/Sub Architecture using Docker
Publish and Subscribe System using Docker. This repository consists of two projects:
1)Centralised Pub/Sub System.
2)Distributed Pub/Sub System.
Both the projects are Containerised using Docker. Distributed Pub/Sub project emulates real world's Kafka's Pub/Sub Architecture.
In Realworld Pub-sub systems are seperated geographically so we implemented pub-sub systems on different docker containers to simulate this.
In this distributed system brokers broadcast the events to subscribers as soon as a publisher publishes an event using RIP algorithm.
