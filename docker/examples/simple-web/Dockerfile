FROM ubuntu:18.04

EXPOSE 8000

#La carpeta en la que se quiere posicionar dentro del contenedor la aplicación
WORKDIR /app 

#Copiar los archivos que están en la ruta que se le indique
COPY . .
#Podemos escribir un comando CMD mediante una lista con strings separados por comas
#También podemos hacerlo en una misma linea
#La linea dice: Ejecutame en bash el siguiente archivo
CMD ["bash", "hello.sh"]