FROM amazoncorretto:17

LABEL authors="marzzio"

RUN mkdir -p /home/ksero
COPY /retailers-microservice-0.0.1-SNAPSHOT.jar /home/ksero

EXPOSE 8102

CMD ["java", "-jar", "/home/ksero/retailers-microservice-0.0.1-SNAPSHOT.jar"]