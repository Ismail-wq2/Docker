# Docker I

## Ejercicio 1
![CAP1](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio1_Docker/Imagen%20pegada.png)
![CAP2](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio1_Docker/Imagen%20pegada%20(2).png)
---

## Ejercicio 2
### Busca por terminal la imagen de Docker hello-world.
![CAP3](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada.png)
### ¿Cuál de todas las imágenes es la oficial?
![CAP4](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(2).png)
### Haz lo mismo, pero en DockerHub. Marca a la izquierda la casilla Docker Official Image y comprueba que coincide con tu elección del punto anterior.
![CAP5](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(3).png)
### Descarga y ejecuta la imagen elegida en tu ordenador.
![CAP6](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(4).png)
### Haz lo mismo con la imagen hello-seattle.
![CAP7](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(5).png)
### Muestra las imágenes descargadas en tu ordenador.
![CAP8](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(6).png)
### Intenta borrar la imagen hello-seattle ¿Por qué te está dando error?
![CAP9](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(10).png)
### Lista los contenedores de tu ordenador con la opción ls sin parámetros ¿Ves algún contenedor de la imagen hello-seattle?
![CAP10](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(9).png)
### Vuelve a listar los contenedores con la opción ls -a ¿Por qué ahora sí que se muestra el contenedor de la imagen hello-seattle? ¿Para qué sirve la opción -a?
![CAP11](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(12).png)
### Elimina el contenedor que usa hello-seattle y la imagen.
![CAP12](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(13).png)
### Vuelve a listar las imágenes y comprueba que se ha borrado correctamente.
![CAP13](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio2_Docker/Imagen%20pegada%20(14).png)


---

## Ejercicio 3
### Crea una imagen derivada de la imagen hello-world descargada en el ejercicio anterior con docker image tag llamada smr/hola-mundo.
![CAP14](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada.png)

### Borra la imagen original (hello-world).
![CAP15](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada%20(2).png)

### Guarda la nueva imagen creada en el fichero smr-hola-mundo.tar
![CAP16](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada%20(3).png)

### Borra la imagen docker smr/hola-mundo y comprueba que no tienes ninguna imagen.
![CAP17](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada%20(4).png)
![CAP18](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada%20(5).png)

### Añade la imagen smr/hola-mundo mediante docker image load usando el archivo .tar creado anteriormente.
![CAP19](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio3_Docker/Imagen%20pegada%20(6).png)


---

## Ejercicio 4
### Descarga la imagen oficial de mysql.
![CAP20](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio4_Docker/Imagen%20pegada.png)

### Con la imagen que te has descargado, crea un contenedor con nombre mysql_smr y smr como password del usuario root.
![CAP21](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio4_Docker/Imagen%20pegada%20(2).png)

### Ejecuta desde la terminal la orden: docker container exec -it mysql_smr mysql -u root -p
![CAP22](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio4_Docker/Imagen%20pegada%20(3).png)
### Ejecuta la siguiente orden dentro de Mysql para crear una nueva base de datos: CREATE DATABASE prueba;
### Comprueba que se ha creado la bbdd con la orden: show databases;
![CAP23](https://github.com/Ismail-wq2/Docker/blob/main/drive-download-20261123T135658Z-1-001/Ejercicio4_Docker/Imagen%20pegada%20(4).png)

---

## Ejercicio 5
### Para el contenedor mysql_smr y vuelve a iniciarlo.
### Para salir de mysql y del contenedor ejecuta la orden exit
### Conéctate de nuevo a Mysql y comprueba que la bbdd prueba sigue estando.
### Elimina el contenedor mysql_smr.
### Vuelve a crearlo con los mismos parámetros y comprueba que la bbdd prueba no existe.
### Sal del contenedor y elimínalo.

---

## Ejercicio 6
### Crea un directorio llamado mysql_data.
### Vuelve a crear el contenedor mysql con los mismos parámetros anteriores pero indicando que la carpeta del contenedor /var/lib/mysql se guardará en el directorio recién creado (mysql_data).
### Crea de nuevo la bbdd pruebas dentro del Mysql del contenedor.
### Sal y elimina el contenedor.
### Crea de nuevo el contenedor sin mapear ninguna carpeta (sin utilizar volúmenes) y comprueba que la bbdd prueba no existe.
### Vuelve a salir y eliminar el contendor.
### Crea de nuevo el contenedor pero mapeando la carpeta igual que antes (la carpeta /var/lib/mysql del contenedor se guardará en mysql_data).
### Comprueba que la bbdd sigue estando en Mysql.

---

## Ejercicio 7
### Crea un directorio llamado php_data.
### Crea un archivo llamado index.php en el directorio recién creado con el siguiente contenido:
´´´ javascript
<?php
phpinfo();
´´´
### Arranca un contenedor con la imagen php:8.0-apache y nombre php_smr indicando que la carpeta del contenedor /var/www/html se guardará en la carpeta creada en el primer punto. Además, el puerto 80 del contenedor se mapeará al puerto 8085 de la máquina real.
### Abre un navegador accede a http://ip_maquina_virtual:8085 y comprueba que se muestra una página similar a ésta:

### Reinicia la máquina virtual.
### Comprueba que accediendo a la anterior url se produce un error.
### Borra el contenedor.
### Vuelve a crear el contenedor pero ahora añade que siempre se reinicie.
### Reinicia la máquina virtual.
### Comprueba que navegando a la anterior url ahora si que funciona.
