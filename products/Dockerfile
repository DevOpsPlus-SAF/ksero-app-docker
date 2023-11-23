FROM amazoncorretto:17

LABEL authors="marzzio"

RUN mkdir -p /home/ksero
COPY /products-microservice-0.0.1-SNAPSHOT.jar /home/ksero

EXPOSE 8200

CMD ["java", "-jar", "/home/ksero/products-microservice-0.0.1-SNAPSHOT.jar"]