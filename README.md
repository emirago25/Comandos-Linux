# Comandos-Linux
Este es un repositorio de comandos de Linux del curso Sistemas Operativos

pwd - muestra la ruta del directorio de trabajo actual.
  Ej: 
pwd
pwd {--help, --version 

cd:
  cd .. - sirve para ir un directorio hacia atrás
  cd (nombre de la carpeta/ruta) - sirve para ir directamente a la carpeta o ruta en específica
  cd - sirve para ir directamente a la carpeta de inicio.
 Ej: cd temp\fotos Abre el directorio temp\fotos
  
ls - se usa para ver el contenido de un directorio
  ls -R lista todos los archivos en los subdirectorios
  ls -a muestra los archivos ocultos
  ls -al lista los archivos y directorios con información detallada como los permisos, tamaño, proprietario, etc.
 Ej: ls -d Podemos listar los directorios con el parámetro -d.
  
cat (nombre del archivo) - crea un nuevo archivo.
Ej: cat tarea.txt Crea un archivo llamado tarea con extensión .txt

cp - copia los archivos del directorio actual a un directorio diferente.
 Ej: cp tarea.jpg /home/tareas
  
mv - Se usa para mover archivos o  cambiar el nombre de los archivos
 Ej: mv casa.jpg /home/casas
           mv casa.jpg casa2.jpg Se movió el archivo a la ruta /home/casas pero con el nombre casa2.jpg
           
mkdir - crea un nuevo directorio
 Ej: mkdir Ulacit Se creó el directorio Ulacit 
  
rm - se usa para elminar directorios y el contenido dentro de ellos
  rm -r elmina el directorio
 Ej rm taras.txt Elimina el directorio tareas.txt
  
touch - permite crear un nuevo archivo en blanco.
 Ej: touch tarea Crea el archivo en blanco tarea
  
sudo - permite realizar tareas que requieren permisos administrativos o raíz
Ej: sudo find / -type f -name "iphone.ovpn" Busca entre los directorios el archivo iphone.ovpn

top - mostrará una lista de los procesos en ejecución y la cantidad de CPU que utiliza cada proceso
Ej top -u usuario Verifica los procesos que pertenecen al usuario

history - lista los comandos que ingresados anteriormente
Ej History 
lsb_release
clear
ip addr
mkdir Muestra los ultimos comandos utilizados. 

clear - utilizado para limpiar la línea de comandos
Ej: Clear

htop - usado para monitorear los recursos vitales del sistema o los procesos en tiempo real.

su - Linux nos solicitará la contraseña y accederemos directamente a dicha cuenta.
Ej: su Emmanuel Se accede a la cuenta Emmanuel, luego de ingresar la contraseña

stat -  muestra información detallada sobre archivos o sistemas de archivos determinados. 
Ej: stat foto1.txt
Fichero: el nombre del archivo.
Tamaño: el tamaño del archivo en bytes.
Bloques: la cantidad de bloques asignados que toma el archivo.
Bloque E/S: el tamaño en bytes de cada bloque.
Tipo de archivo: archivo regular, directorio, enlace simbólico …
Dispositivo: número de dispositivo en hexadecimal y decimal.
Inode: número de inode.
Enlaces: número de enlaces físicos.
Acceso: permisos de archivo en los métodos numérico y simbólico.
Uid: ID de usuario y nombre del propietario.
Gid: ID de grupo y nombre del propietario.
Acceso: la última vez que se accedió al archivo.
Modificación: la última vez que se modificó el contenido del archivo.
Cambio: la última vez que se modificó el atributo o el contenido del archivo.

file - permite detectar el tipo y formato de un archivo. 
  Ej: file *.txt Busca todos los archivos .txt

chown - Es una abreviatura del 'Change owner',se utiliza en los sistemas operativos Unix y Unix-like para cambiar el propietario de archivos del sistema de archivos, directorios
  Ej: chown root /var/home/musica.mp3 Establece como propietario del archivo musica.mp3 al usuario root

chmod - permite cambiar o transferir la propiedad de un archivo al nombre de usuario especificado
  Ej: chmod 644 file.js[/code] Establece los permisos de file.js en el propietario puede leer y escribir, el grupo solo puede leer y otros solo pueden leer.

df - Sirve para ver el espacio de disco disponible en cada una de las particiones de su sistema.

kill -9 - si se tiene un programa que no responde, se puede cerrar manualmente utilizando el comando kill.

ps -  es un comando que permite visualizar el estado de un Proceso.

du - permite verificar cuánto espacio ocupa un archivo o un directorio.

ping - verifica el estado de conectividad a un servidor o computadora.
Ej: ping 192.168.2.5 Se hará una comunicacion entre nuestra computadora y el dispositivo con la ip 192.168.2.5

uname - Sirve para imprimir información detallada sobre el sistema Linux, como el nombre de la máquina, el sistema operativo, el núcleo, etc.

man - muestra el manual de un comando.

echo - permite mover algunos datos a un archivo

ip address - muestra la ip utilizada en el momento, ademas de informacion de red

nano - Se utiliza para crear o editar scripts en Linux
  Ej: nano openvpn-install.sh Verifica el codigo de script del archivo openvpn-install.sh 
