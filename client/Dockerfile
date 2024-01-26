FROM openjdk:21

COPY SimpleClient.java /home/SimpleClient.java

WORKDIR /home

RUN javac SimpleClient.java

CMD ["java", "SimpleClient"]