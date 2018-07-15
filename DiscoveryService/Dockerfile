FROM java:8
COPY /root/.jenkins/workspace/docker-test/DiscoveryService/target/discovery-service.jar discovery-service.jar
EXPOSE 8761
CMD java -jar discovery-service.jar