# comando-linux
Este es un repositorio de comandos de Linux del curso de Sistemas Operativos
apt: paquete que permite instalar el software
dpkg -l instalador: instalar un programa
sudo apt install paquete: instalar un paquete de software
sudo apt remove paquete: desinstalar paquete
sudo apt update: verificar si hay alguna actualización
sudo apt upgrade: actualizar todos los paquetes
sudo su: entrar en modo root
exit: salir del modo root
pwd:	mostrar la ruta del directorio en el cual estoy ubicado
rm: borrar archivos 
rm -R:	remueve un directorio
rm -Rf:	remueve un directorio de manera forzada
clear: limpiar la consola
history: ver el historial de todos los comandos que se han utilizado
ip addr: mostrar la dirección IP
useradd: crear un usuario
sudo chown user root archivo.ext: dar permisos
kill -9 PID: matar un proceso que se quiera
ps -aux: ver procesos que estan corriendo en ese momento
cat archivo: ver el contenido de un archivo
cd nombredir: cambiar de directorio
cd: regresar al directorio anterior
cp nombre destino: copiar el contenido a otra ubicación
du -h comprimido.tar: ver tamaño del archivo
find -name archivo: encontrar un archivo por nombre
head -n #: imprimir las primeras lineas de un archivo
ls: mostrar los directorios
ls -l:	listar todos los archivos con sus permisos
ls -a/-l: listar los archivos
mkdir: crear una carpeta o directorio
mv archivo.txt PruebaNombre.txt: cambiar nombre
mv PruebaNombre /ruta: mover ubicación
nano: editar un archivo
pwd: ver la ruta actual
tail -n #: mostrar el final de un archivo
tar -xvf comprimido.tar: descomprimir
tar -tvf comprimido.tar: ver los archivos adentro
bash script.sh: ejecutar un script de bash
df-h: mostrar todos los discos
gnome-disk-utility: ver información del disco
gparted: administrar particiones
mount: montar particiones nuevas
sudo mkdir /mnt/particion1: montar el disco en en la ubicación deseada
grep -r: busca patrones dentro de archivos
docker run:	inicia o empieza a correr una imagen
docker run -ti:	Empieza a correr una imagen de forma interactiva
docker run -ti --rm	Corre de forma interactiva la imagen pero cuando salimos esta se borra con todo lo que se hizo
docker stop:	Para una imagen en ejecucion
docker history:	muestra el historial de una imagen
docker info: mostrar información del sistema
docker build:	construir una imagen en el Dockerfile
docker ps: ver los contenedores que están activos
docker find ./:	muestra dockerfiles que se han instalado de repositorios oficiales
docker push: pushea a la cuenta de docker hub
docker run --rm: elimina un contenedor
docker find	Muestra ficheros
mginx docker built -t:	Crea una imagen
docker rmi:	elimina una imagen
vim dockerfile: crea variables en el Dockerfile
vim Dockerfile: se utiliza para dar una serie de ordenes de agregar imagenes, variables ficheros, entre otros
sudo apt install docker-ce: instalar docker
sudo systenctl start docker: iniciar el contenedor
sudo docker images: mostrar las imágenes descargadas
sudo docker pull imagen: descargar una imagen
sudo pacman Syuu:	sincroniza y hace actualización de paquetes en Manjaro
sudo pacman -S yay:	instala paquetes de PKGBUILDs en Manjaro
yay -S google-chrome:	instala chrome en Manjaro
sudo pacman -S apache:	instala apache en Manjaro
