#traemos la imagen de jdk
FROM openjdk:17-jdk-alpine
#creamos directorio en el contenedor
WORKDIR /app
#copiamos el target al contenedor
COPY target/config-server-0.0.1-SNAPSHOT.jar config-server-app.jar
#exponemos el puerto
EXPOSE 8081
#comando para ejecutar la app
ENTRYPOINT ["java", "-jar", "config-server-app.jar"]