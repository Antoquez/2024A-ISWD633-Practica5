# Aprendizajes

   - Llegué a comprender la estructura y sintaxis de los archivos YAML tuve problemas por no realizar una indentación correcta y clara de los servicios, pero lo resolví revisando el archivo con atención para realizar las respectivas configuraciones correctamente.

   - Aprendimos a configurar servicios individuales y especificar sus imágenes, nombres de contenedores, puertos, variables de entorno, volúmenes y redes.

   - La creación y utilización de redes de tipo bridge en Docker permitió que los contenedores se comuniquen entre sí mediante nombres de servicio en lugar de direcciones IP.

   - Logré asegurar que los servicios se ejecuten correctamente a través de los healchecks, y de esta forma se logró una ejecución correcta del ejercicio.

   - Se utilizaron volúmenes en las configuraciones de los contenedores para mantener los datos dentro de nuestro entorno, siendo esta otra forma de verificar una correcta ejecución.

## En general

Este ejercicio fortaleció mis habilidades en docker Compose, y además destacó la importancia de la configuración y la monitorización de la salud de los servicios para mantener aplicaciones Dockerizadas en funcionamiento de manera eficiente y confiable.  

## Problema encontrado  
Se registro un inconveniente al momento de ejecutar el comando  
```
docker compose ps
```
pues este mismo no reflejaba que estuvieran en ejecución los contenedores creados en la práctica.  
Dicho problema se mantuvo, pero para revisar la ejecución de los contenedores se accedió a la aplicación de docker desktop donde se revisó la correcta ejecución de los servicios generados.
