# Levels alert

This repository is made as an introduction to work with Apache Kafka using Golang.
It covers the basic implementation of Kafka producers and consumers, focusing on sending and receiving messages asynchronously.
It contains 3 microservices with different responsibilities defined below.

## Project Structure
- `Receiver`: First microservice, it manages input REST requests and produces kafka events based on these request.
- `Persistency`: Second microservice, it consumes events produced by `Receiver` microservice and stores the needed information.
- `Alert`: Third microservice, it consumes events and filter information to raise alerts if needed.

## How to use

## Microservices
### Receiver
#### General design
#### Components
#### More
Wiki url


