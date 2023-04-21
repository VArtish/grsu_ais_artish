FROM openjdk:8-jdk-slim
COPY PingPongArtish.java /
RUN javac PingPongArtish.java
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["PingPongArtish"]