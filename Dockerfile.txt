FROM adoptopenjdk/openjdk11
WORKDIR /
ADD truyum-0.0.1-SNAPSHOT.jar truyum-0.0.1-SNAPSHOT.jar
EXPOSE 5000
CMD java -jar truyum-0.0.1-SNAPSHOT.jar