FROM openjdk:8

RUN java -jar -Dspring.profiles.active=profile_name target/spring-boot-rest-example-0.5.0.war

COPY target/spring-boot-rest-example-0.5.0.war spring-boot-rest-example-0.5.0.war

EXPOSE 8090 8091 8092 3306

ENTRYPOINT ["java", "-jar", "/spring-boot-rest-example-0.5.0.war"]
