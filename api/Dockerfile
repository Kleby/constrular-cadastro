# Use uma imagem base que tenha o JDK 17 instalado
FROM openjdk:17-jdk-slim

# Diretório de trabalho dentro do contêiner
WORKDIR /app

# Copia o arquivo JAR gerado pelo Maven para dentro do contêiner
COPY target/constrular-API-0.0.1-SNAPSHOT.jar /app/constrular-API-0.0.1-SNAPSHOT.jar

# Define o ponto de entrada para o contêiner
ENTRYPOINT ["java", "-jar", "constrular-API-0.0.1-SNAPSHOT.jar"]

# Exponha a porta usada pelo aplicativo Spring Boot
EXPOSE 8080
