FROM adoptopenjdk/openjdk11:alpine-jre

# simplify the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app 

COPY ${artifact} app.jar

ENTRYPOINT [ "java","-jar","app.jar" ]