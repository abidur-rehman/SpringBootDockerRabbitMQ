# SpringBootDockerRabbitMQ
Multi container spring boot app with docker compose sending messages to RabbitMQ. The app creates three containers. First container
contains RabbitMq, second containers deploys Producer app, third container deploys Cosumer app.

Producer app produces data and sends it to the RabbitMQ. The consumer app consumes the data and prints it on console.

### Steps to deploy the app.

1. Install docker on your machine and start it

2. Run docker-compuse up

3. Producer sends multiple json formated messages to the queue in the following format:-

3.1 {id: 1, telephoneNumber: +4187900087}


3. Access the app http://localhost:8080


