# NotificationHandlingSystem
This system designed to handle multiple types of notifications from different sources

# Functional requirements

Should process notification concurrently from different sources

Should persist the data (ORM mandatory)

Once the notification is processed , the system should generate different type of message formats (sms, email, push etc.,)

Should expose REST APIs to see the details

Should be able to easily extendable and plugable new notification message types in future

# Non functional requirements

Scalability considerations

Unit testing

# Technology of choice

Spring Boot

Hibernate

RabbitMQ or some standard message oriented middleware

Junit

Any standard caching framework


