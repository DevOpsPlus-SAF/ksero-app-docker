FROM amazoncorretto:17

LABEL authors="erik"

RUN mkdir -p /home/ksero
COPY /wholesalers-microservice-0.0.1-SNAPSHOT.jar /home/ksero

EXPOSE 8101

CMD ["java", "-jar", "/home/ksero/wholesalers-microservice-0.0.1-SNAPSHOT.jar"]

