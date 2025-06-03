# 📦 Notification Service

## 📄 Описание

Микросервис отвечает за принятие запросов на уведомления пользователей, а также за их отправку по email, sms или telegram.

## ⚙️ Технологии

### Основа:

- Java 17
- Spring Boot 3.0.6

### Базы:

- PostgreSQL
- Redis
- Liquibase

### Общение микросервисов:

- Kafka
- OpenFeign

### Тестирование:

- JUnit 5
- Mockito
- AssertJ
- Testcontainers

### Прочее:

- Lombok
- MapStruct
- Springdoc OpenAPI
- CI Pipeline (GitHub Actions)
- JaCoCo
- Slf4j
- Docker
- WebClient

## 🔗 Связанные сервисы

- Analytics Service - для сбора и анализа данных об уведомлениях
- User Service - для получения информации о пользователях
