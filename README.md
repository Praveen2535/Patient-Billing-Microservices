# 🏥 Distributed Healthcare Microservices Platform

[![Java](https://img.shields.io/badge/Java-17+-orange.svg?style=for-the-badge&logo=java)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg?style=for-the-badge&logo=springboot)](https://spring.io/projects/spring-boot)
[![gRPC](https://img.shields.io/badge/gRPC-Protobuf-blue.svg?style=for-the-badge&logo=grpc)](https://grpc.io/)
[![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-Event%20Driven-black.svg?style=for-the-badge&logo=apachekafka)](https://kafka.apache.org/)
[![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED.svg?style=for-the-badge&logo=docker)](https://www.docker.com/)

An enterprise-grade, event-driven microservices architecture designed for healthcare patient management, automated billing processing, and real-time notification dispatches. Built with **Spring Boot 3**, high-performance synchronous **gRPC**, asynchronous **Apache Kafka** event streaming, **JWT Security**, and **Docker Compose** orchestration.

---

## 📐 System Architecture

The platform separates core domains into independently deployable microservices behind a unified API Gateway:
