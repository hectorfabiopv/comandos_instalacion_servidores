# Lista de comandos

Esta es la lista de comandos que usaremos durante la práctica de servidores web

## Comenzando 🚀
Crearemos un contenedor basados en la imagen oficial de ubuntu con el siguiente comando:
docker run -dit --name apache -p 8080:80 ubuntu

Podemos revisar los contenedores que hemos creado con información respecto a ellos con el siguiente comando:
docker ps

Ingresamos al contenedor para operar dentro de él:
docker exec -it apache bash

Actualizamos el listado de repositorios
apt update

### Instalar paquete para administración de red
apt install net-tools -y


### Revisar dirección IP
ifconfig


### Instalar Apache
apt install apache2 -y


### Instalar NGINX
sudo apt-get install nginx -y


### Instalar servidor MySQL
apt install mysql-server -y


### Revisar el estado de los servicios
service nombre_servicio status


### Detener un servicio
service nombre_servicio stop


### Iniciar un servicio
service nombre_servicio start


### Rutas de configuración Nginx y Apache
- /etc/nginx/sites-available/default
- /etc/apache2/sites-available/000-default.conf


### Editar archivos, guardar con CTRL + X y aceptar con Y
nano nombreArchivo


### Configurar MySQL
sudo mysql_secure_installation


### Escribir password y a todo dar Y
### Conectarse a MySQL
sudo mysql -u root -p
### Luego colocar el password
