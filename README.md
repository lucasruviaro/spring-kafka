

# API Documentation

This API, developed using Spring Boot, facilitates communication with Apache Kafka for seamless message handling. It includes two key functionalities:

## Send String Message to Kafka

### Endpoint

POST /api/v1/kafka/stringmessage/publish?message=insertherethemessage


### Description

This endpoint allows you to send a string message to a Kafka topic.

---

## Send JSON Object Message to Kafka

### Endpoint

POST /api/v1/kafka/jsonmessage/publish


### Description

This endpoint allows you to send a JSON object message to a Kafka topic.

### Request Body

```json
{
    "id": 1,
    "firstName": "Lucas",
    "lastName": "Ruviaro"
}


