FROM eclipse-temurin:latest
COPY src/Main.java/josep/src
WORKDIR /josep
RUN javac-d ./build src/Main.java
WORKDIR /josep/build
RUN jar cfe hellowdocker.jar Main Main.class
CMD java-jar hellowdocker.jar