# Microservices_with_Java_Spring_Docker_Kubernetes
Master Microservices with Java, Spring, Docker, Kubernetes (traning)


docker push docker.io/eazybytes/configserver
docker push eazybytes/configserver
docker push docker.io/eazybytes/eurekaserver
docker push docker.io/eazybytes/accounts
docker push docker.io/eazybytes/loans
docker push docker.io/eazybytes/cards

# add Zipkin:
docker run -d -p 9411:9411 openzipkin/zipkin

#Add RabbitMQ (quest / quest):
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management 
