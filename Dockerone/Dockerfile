# FROM openjdk:21-jdk
# WORKDIR /usr/src/myapp
# ENV PORT 8080
# EXPOSE 8080
# COPY . /usr/src/myapp/
# ENTRYPOINT exec java $JAVA_OPTS -jar ToDoApp-0.0.1-SNAPSHOT.jar



FROM openjdk:21-jdk
WORKDIR /usr/src/myapp
COPY . /usr/src/myapp/
CMD [ "java","-jar","ToDoApp-0.0.1-SNAPSHOT.jar" ]
EXPOSE 8091
