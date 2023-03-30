<center> <h1>SISTEMAS OPERATIVOS</h1> </center> 
<center> <h3>Wander Jerez 2021-0990</h3> </center>

# Nota
*Si no ve las imagenes tiene que descargar el repositorio, es un error de github por asignarle las imagenes con los nombres de imagen1,2 y asi*

*-Para crear mi CRON, me dirigí a la terminal de linux (Ubuntu) y puse el comando contrab -e, el cual me permitira crear un CRON y me muestra una serie de instrucciones para la creacion de este, instrucciones las cuales podemos borrar.*

![foto1](/imagenes/Imagen1.png)


*-Escribí los parametros 0 20 * * 3, indicando que solo se ejecutara  los miércoles a las 8:00 pm (horario de la clase de teoria de sistemas operativos II), lo que escribí me devolverá la fecha por el date +%D, y la hora por el date +%T la hora, y todo esto se guardara en un documento de texto llamado almacen.txt, gracias al archivo bash llamado horarioclase.sh.*

![foto2](/imagenes/Imagen2.png)

*Esto es lo que contiene dentro el archive bash que se esta usando: horarioclase.sh.*

![foto3](/imagenes/Imagen3.png)

*-Ahora utilicé el comando crontab -l para confirmar que se ha guardado mi CRON.*

![foto4](/imagenes/Imagen4.png)

*-Ahora con el comando sudo service cron start se inició la ejecución de mi cron, y con sudo service cron stop la detengo cuando desee hacerlo.*

![foto5](/imagenes/Imagen5.png)

![foto6](/imagenes/Imagen6.png)

*Ahora como ejemplo de que funciona voy a mostrarles que ocurre cuando ejecuto mi cron a cada minuto (* * * * * * *).*

![foto7](/imagenes/Imagen7.png)

![foto8](/imagenes/Imagen8.png)

