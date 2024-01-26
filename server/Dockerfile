FROM openjdk:21

COPY SimpleServer.java /home/SimpleServer.java

WORKDIR /home

RUN javac SimpleServer.java

EXPOSE 5432

CMD ["java", "SimpleServer"]