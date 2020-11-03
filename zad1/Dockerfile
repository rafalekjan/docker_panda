FROM openjdk:11.0
ARG JAR_FILE="*.jar" 
RUN echo ${JAR_FILE}
COPY ${JAR_FILE} /app.jar
CMD ["java", "-jar", "/app.jar"]