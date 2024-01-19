FROM openjdk:17
WORKDIR /app
COPY *.jar app.jar
ENV TZ=Africa/Johannesburg
ENTRYPOINT ["java", "-Dspring.profiles.active=test","-jar","app.jar"]



#FROM maven:3.8-openjdk-17 as buildstage
#WORKDIR /app
#COPY / .
#RUN mvn clean install
#
#FROM openjdk:17
#WORKDIR /app
#COPY --from=buildstage /app .
#WORKDIR /app/discover-server/target
#ENV TZ=Africa/Johannesburg
#
#ENTRYPOINT ["java","-jar","discover-server-0.0.1-SNAPSHOT.jar"]
#ENTRYPOINT ["java", "-Dspring.profiles.active=test","-jar","skynet-rest-0.0.1-SNAPSHOT.jar"]