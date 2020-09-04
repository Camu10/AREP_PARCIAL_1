# AREP_PARCIAL_1

1. Construir un servicio WEB (puede usar Spark o Sockets) que reciba una lista de números y retorne una estructura JSON con: La lista de números ordenada. Para probar, y para ver como el browser arma el query, puede usar una cadena puede enviarla en un solo campo con valores separados por comas. Ayuda: use un form html con un solo campo.
2. Usted debe implementar el ordenamiento por medio de bubble sort. Piense que este algoritmo se podría user para objetos de otro tipo.
3. Su diseño debe soportar la composición de nuevas operaciones sobre la lista para modificar servicios existentes o componer nuevos servicios. Por ejemplo, piense que en el futuro podemos solicitar que se creen nuevos servicios sobre la lista aumentando el API web, es decir,  debe ser fácilmente extensible.
4. Agregue una operaciónes para calcular la sumatoria  y el promedio de la lista y modifique su programa para que la estructura Json contenga estos valores.
5. El diseño del servidor debe tener en cuenta buenas prácticas de diseño OO.
6. Despliegue el servicio en Heroku.
7. Construya un cliente JAVA para probar el servicio en heroku.
8. El cliente y el servidor debe entregarlos en un proyecto estructurado con Maven.
9. El cliente debe traer "quemada" en el código fuente la url de su aplicación desplegada en Heroku.

## Pre-requisitos
* [MAVEN](https://maven.apache.org/) - Administrador de dependencias.
* [GIT](https://git-scm.com/) - Control de versiones.
Para estar seguro de las versiónes que posee de maven, git y de java ejecute los siguientes comandos:
```
mvn -version  
git --version  
java -version  
```
## Instalación 
Para descargar el proyecto desde GitHub ejecute la siguiente linea:
```
git clone https://github.com/Camu10/AREP_PARCIAL_1.git
```

## Ejecutar
Dentro del directorio AREP_LAB2, desde la consola de comandos para compilar ejecutamos la siguiente linea:
```
mvn package
```
Para ejecutar el proyecto de manera local desde la consola de comandos ejecutamos la siguiente linea y desde un navegador buscamos `localhost:36000/` :
```
mvn exec:java -D "exec.mainClass"="edu.escuelaing.arep.App"
```

## Ejecutando las pruebas
Para correr las pruebas ejecutamos la siguiente linea:
```
mvn test
```
## Despliegue en Heroku
Para ingresar a la aplicación web desde cualquier navegador puede hacerlo dando click [aqui](https://arepparcial1.herokuapp.com/)

## Construido con
* [MAVEN](https://maven.apache.org/) - Administrador de dependencias.
* [GIT](https://git-scm.com/) - Control de versiones.
* [JUNIT](https://junit.org/junit5/) - Framework para realizar y automatizar pruebas.
* [SPARK](http://sparkjava.com/) - Framework para el desarrollo de aplicaciones web.
* [HEROKU](https://www.heroku.com/) - Plataforma para el despliegue.
* JAVA - Lenguaje de programación.

## Autor
* **Carlos Murillo** - [Camu10](https://github.com/Camu10)

## Licencia
Este proyecto está bajo la Licencia GNU(General Public License) - mira el archivo [LICENSE](LICENSE) para detalles.