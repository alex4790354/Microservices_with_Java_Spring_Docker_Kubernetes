# Spring_Boot_Microservices_and_Cloud_config_AV
Account service for Spring_Boot_Microservices


#to build Docker image: from project-root directory:
mvn ckean install -Dmaven.test.skip=true
docker build . -t eazybytes/accounts
docker compose up                   // start images in docker-compose.yml