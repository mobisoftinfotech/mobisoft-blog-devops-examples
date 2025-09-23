# ---------- Stage 1: Build ----------
FROM maven:3.9.4-eclipse-temurin-17 as build
WORKDIR /app

# Copy all project files
COPY . .

# Build the JAR file
RUN mvn clean package -DskipTests

# ---------- Stage 2: Run ----------
FROM openjdk:17-jdk-slim
WORKDIR /app

# Copy the built JAR from the build stage
COPY --from=build /app/target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
