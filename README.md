# Microservices Architecture Project

This repository contains a microservices architecture with the following components:

* API Gateway
* Service Registry
* Question Service
* Quiz Service

## Services Overview

### API Gateway

The API Gateway routes client requests to the appropriate microservices, acting as a reverse proxy. It handles:

- Request routing
- Composition
- Protocol translation

### Service Registry

The Service Registry is a central database tracking all available services and their instances, enabling dynamic service discovery.

### Question Service

The Question Service manages questions in the system, providing endpoints to:

- Create questions
- Read questions
- Update questions
- Delete questions

### Quiz Service

The Quiz Service manages quizzes, including:

- Creating quizzes
- Associating questions with quizzes
- Managing quiz results

![image](https://github.com/user-attachments/assets/3dab58e5-7974-4dd7-b52c-234e919f7cb4)
