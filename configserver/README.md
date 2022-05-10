# Spring_Boot_Microservices_and_Cloud_config_AV
Central repository configurations for Spring_Boot_Microservices


#to build Docker image: from project-root directory:  
mvn ckean install -Dmaven.test.skip=true
mvn spring-boot:build-image -Dmaven.test.skip=true
or 
docker build . -t eazybytes/configserver (but add Dockerfile first)