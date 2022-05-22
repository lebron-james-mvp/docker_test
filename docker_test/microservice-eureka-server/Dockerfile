FROM java:8-jre
MAINTAINER Jacy <changjing@gcu.edu.cn>

ADD ./target/microservice-eureka-server-1.0-SNAPSHOT.jar /app/microservice-eureka-service.jar
CMD ["java", "-Xmx200m", "-jar", "/app/microservice-eureka-service.jar"]

EXPOSE 8761