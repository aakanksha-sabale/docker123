From maven:3.8.5-openjdk-17
WORKDIR /opt
COPY . /opt/
Run mvn clean package -DskipTests
Expose 8080
Cmd ["java" , "-jar" , "target/student-registration-backend-0.0.1-SNAPSHOT.jar"]