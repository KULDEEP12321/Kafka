# 📬 Kafka Integration Demo

This repository demonstrates how to set up **Apache Kafka** and integrate it into two Java-based applications – a **Producer** (Customer App) and a **Consumer** (Hotel App) – using **Spring Tool Suite (STS)** or **IntelliJ**.

Kafka acts as a **message broker** between these two apps, showcasing how microservices can communicate asynchronously through event streaming.

---

## 📌 Project Overview

- **Kafka Setup** → Basic configuration for running Kafka locally
- **Customer App (Producer)** → Sends messages/events to Kafka
- **Hotel App (Consumer)** → Listens for messages/events from Kafka

> ⚠️ These are **demo-level apps**, intended to help you understand how Kafka works in a microservice-like architecture. They are **not production-ready**.

---

## 📁 File Structure

Kafka-Integration/
├── kafka-setup.txt # Instructions to set up Kafka locally
├── Producer-Code-Kafka.txt # Java code for the Customer (Producer) app
├── Consumer-Kafka-Code.txt # Java code for the Hotel (Consumer) app
└── README.md # Project documentation


---

## 🧰 Prerequisites

- Java (JDK 8 or above)
- Spring Tool Suite (STS) or IntelliJ
- Apache Kafka & Zookeeper
- Apache Maven (for building apps)

---

## 🔧 Setup Instructions

### 1. 🛠 Kafka Setup

Follow the steps in `kafka-setup.txt` to download, install, and run Apache Kafka and Zookeeper on your local system.

### 2. 🧾 Create Customer App (Producer)

Use the code from `Producer-Code-Kafka.txt` to create a basic Spring Boot project that acts as a Kafka **producer**.

### 3. 🧾 Create Hotel App (Consumer)

Use the code from `Consumer-Kafka-Code.txt` to build another Spring Boot project that acts as a Kafka **consumer**.

---

## 🔄 Flow Diagram

Customer App (Producer)
|
| --> Kafka Topic (Broker)
|
Hotel App (Consumer)


Kafka enables seamless communication between both services via **topics**.

---

## 🚀 Run the Apps

1. Start Zookeeper and Kafka using your terminal.
2. Run the **Customer App** to send messages.
3. Run the **Hotel App** to receive and log messages from Kafka.

---

## 📌 Notes

- The purpose is to **understand Kafka basics** like producers, consumers, and topic-based communication.
- Apps are intentionally kept simple to keep the focus on Kafka functionality.

---

## 🙌 Acknowledgements

Thanks to the open-source community and the Kafka documentation that helped shape this project.

---

## 📄 License

This project is open for educational use. You can modify and extend it freely.

