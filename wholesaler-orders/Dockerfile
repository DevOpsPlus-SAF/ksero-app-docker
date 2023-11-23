FROM amazoncorretto:17

LABEL authors="emerson"

RUN mkdir -p /home/ksero
COPY /wholesaler-orders-microservice-0.0.1-SNAPSHOT.jar /home/ksero

EXPOSE 8090

CMD ["java", "-jar", "/home/ksero/wholesaler-orders-microservice-0.0.1-SNAPSHOT.jar"]