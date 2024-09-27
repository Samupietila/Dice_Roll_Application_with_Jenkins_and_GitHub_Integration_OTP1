FROM maven:latest

WORKDIR /app

COPY pom.xml /app

COPY . /app/

RUN mvn package

CMD ["java", "-jar", "target/dice_roll_app-0.0.1-SNAPSHOT.jar"]
