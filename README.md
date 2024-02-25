# RabbitMQ-demo
Demonstration of RabbitMQ using all types of exchanges

# Run RabbitMQ using Docker
docker run -d --hostname my-rabbit --name ecomm-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management

Rabbit managemtn is accesible at http://localhost:15672/ with login/passwd: guest