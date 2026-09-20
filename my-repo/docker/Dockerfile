# usa una imagen base oficial de nginx
FROM nginx:latest

# copia el archivo de configuracion de nginx al contenedor
COPY default.conf /etc/nginx/conf.d/default.conf

# copia el contenedor de la aplicacion (por ejemplo, archivos html) al directorio donde nginx los servira
COPY ./html /usr/share/nginx/html

# exponer el puerto en el que nginx esta escuchando
EXPOSE 80