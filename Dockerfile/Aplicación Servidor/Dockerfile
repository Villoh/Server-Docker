# Utiliza OpenJDK 18.0.1.1 como la imagen de base
FROM openjdk:18.0.1.1
# Creo un directorio para alojar el programa dentro de la imagen
RUN mkdir -p /app/gameworld
RUN mkdir /app/gameworld/Portadas
RUN mkdir /app/gameworld/Juegos
#Copio los archivos del programa
COPY /AplicacionServidor.jar /app/gameworld
#Indico el directorio donde se ejecutara el resto de comandos
WORKDIR /app/gameworld
#Comando que se ejecuta para que el programa se inicie
CMD java -jar AplicacionServidor.jar