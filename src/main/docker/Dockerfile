FROM java:8
VOLUME /tmp
ADD gs-messaging-rabbitmq-0.1.0.jar app.jar
EXPOSE 9055
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
