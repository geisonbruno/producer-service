## Comunicação Assíncrona com Spring Boot, RabbitMQ e Docker
Este repositório demonstra uma comunicação assíncrona utilizando dois projetos Spring Boot separados:

### 🧩 **Conceitos Fundamentais**

- **Producer** envia mensagens.
- **Consumer** recebe mensagens.
- **Broker** (RabbitMQ) faz o roteamento entre eles.

📨 Producer (Responsável pelo envio de mensagens ao RabbitMQ). Esse envio acontece por meio das exchange.

📬 Consumer (Responsável pelo consumo e processamento das mensagens recebidas via RabbitMQ).

![exchanges-topic-fanout-direct](https://github.com/user-attachments/assets/34449dad-b100-413d-a497-ec646e1c4f6b)

## 🚀 Tecnologias Utilizadas
Java 17

Spring Boot

RabbitMQ

Docker e Docker Compose

Gradle
