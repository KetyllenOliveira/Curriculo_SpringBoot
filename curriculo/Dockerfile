# Use uma imagem base do Java
FROM openjdk:17-jdk-slim

# Defina o diretório de trabalho
WORKDIR /app

# Copie o arquivo .jar para o contêiner
COPY target/curriculo-0.0.1-SNAPSHOT.jar app.jar

# Exponha a porta que a aplicação utilizará
EXPOSE 8080

# Comando para executar o .jar
ENTRYPOINT ["java", "-jar", "app.jar"]
