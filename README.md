# Lista de comandos

Esta es la lista de comandos que usaremos durante la práctica de servidores web

## Comenzando 🚀

sudo apt-get update

### Instalar paquete para administración de red
sudo apt-get install net-tools -y


### Revisar dirección IP
ifconfig


### Instalar Apache
sudo apt-get install apache2 -y


### Instalar NGINX
sudo apt-get install nginx -y


### Instalar servidor MySQL
sudo apt-get install mysql-server -y


### Revisar el estado de los servicios
- sudo systemctl status apache2
- sudo systemctl status nginx
- sudo systemctl status mysql


### Detener un servicio
- sudo systemctl stop apache2
- sudo systemctl stop nginx
- sudo systemctl stop mysql


### Iniciar un servicio
- sudo systemctl start apache2
- sudo systemctl start nginx
- sudo systemctl start mysql


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
