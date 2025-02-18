# Kafka Basic

![Kafka](https://img.shields.io/badge/Apache%20Kafka-Event%20Streaming-black) ![Python](https://img.shields.io/badge/Python-Kafka-green) ![Docker](https://img.shields.io/badge/Docker-Compose-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Overview
This repository contains a basic setup for **Apache Kafka** using **Python** to demonstrate how to implement a **Kafka producer** and **Kafka consumer**. The infrastructure is managed via **Docker Compose**, providing a seamless environment to experiment with event-driven architectures.

## 📂 Repository Structure

- **producer.py** - Python script for sending messages to a Kafka topic.
- **consumer.py** - Python script for consuming messages from a Kafka topic.
- **Dockerfile.producer** - Dockerfile for building the producer container.
- **Dockerfile.consumer** - Dockerfile for building the consumer container.
- **docker-compose.yaml** - Configuration file for setting up Kafka, Zookeeper, Kafka UI, producer, and consumer.
- **pyproject.toml** - Dependency management for the Python project.
- **poetry.lock** - Lock file for dependency resolution.

## 🚀 Technologies Used

- **Apache Kafka**
- **Python**
- **Docker & Docker Compose**
- **Zookeeper**
- **Kafka UI**
