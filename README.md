# AREP-parcial2
# Parcial Segundo Tercio
## Requerimientos
Diseñe, construya y despliegue los siguientes servicios en un microcontenedor docker desplegado en una instancei a EC2 de AWS. Cada estudiante debe seleccionar para desarrollar dos funciones matemáticas de acuerdo a los dos últimos dígitos de su cédula como se especifica en la lista. Todas las funciones reciben un solo parámetro de tipo "Double" y retornan una prámetro sde tipo "Double".
0. log
1. ln
2. sin
3. cos
4. tan
5. acos
6. asin
7. atan
8. sqrt
9. exp (el número de eauler elevado ala potendia del parámetro)

Implemente los servicios para responder al método de solicitud HTTP GET. Deben usar el nombre de la función especificado en la lista y el parámetro debe ser pasado en la variable de query con nombre "value".

Ejemplo de una llamado:

https://amazonxxx.x.xxx.x.xxx:{port}/cos?value=3.141592

Salida. El formato de la salida y la respuesta debe ser un JSON con el siguiente formato

{
 "operation": "cos",
 "input":  3.141592,
 "output":  -0.999999
}

### Requisitos previos

* Tener maven instalado
* Tener git instalado
* Versión de Java 7 o Java 8
* Tener Docker instalado
* Tener un protocolo SSH instalado y habilitado


### Instalación

1. Para hacer uso de este proyecto debe clonarlo de este repositorio a su computadora desde cmd usando el siguiente comando:
   
```
git clone https://github.com/anamariasalazar/AREP-parcial2
```

## Ejecución
Para compilar el proyecto utilizando la herramienta Maven, nos dirigimos al directorio donde se encuentra alojado el proyecto, y dentro de este ejecutamos en un Shell o Símbolo del Sistema el siguiente comando:

```
mvn package
```


### AWS
Para comprobar que la página web ha sido desplegada con éxito utilizando AWS, y calcular el ArcoTangente en este caso será 90



Para comprobar que la página web ha sido desplegada con éxito utilizando AWS, y calcular el Logaritmo en este caso será 50



## Construido con

* [Java](https://www.oracle.com/java/) : Tecnología que se usa para el desarrollo de aplicaciones que convierten a la Web en un elemento más interesante y útil.
* [IntelliJ](https://es.wikipedia.org/wiki/IntelliJ_IDEA): Es un entorno de desarrollo integrado (IDE) para el desarrollo de programas informáticos.
* [Git](https://es.wikipedia.org/wiki/Git): Herramienta que realiza una función del control de versiones de código de forma distribuida
* [Maven](https://es.wikipedia.org/wiki/Maven): Maven es una herramienta de software para la gestión y construcción de proyectos Java creada por Jason van Zyl, de Sonatype, en 2002. 
* [JavaScript](https://es.wikipedia.org/wiki/JavaScript): Es el lenguaje de programación encargado de dotar de mayor interactividad y dinamismo a las páginas web.
* [Docker](https://www.docker.com/): Es un proyecto de código abierto que automatiza el despliegue de aplicaciones dentro de contenedores de software, proporcionando una capa adicional de abstracción y automatización de virtualización de aplicaciones en múltiples sistemas operativos.
* [AWS](https://aws.amazon.com/es/): s una colección de servicios de computación en la nube pública que en conjunto forman una plataforma de computación en la nube, ofrecidas a través de Internet por Amazon.com

## Autor

* [Ana Maria Salazar Bohorquez](https://github.com/anamariasalazar)

## Licencia

**©️** Ana Maria Salazar Bohorquez etudiante de Ingeniería de Sistemas de la Escuela Colombiana de Ingeniería Julio Garavito

Licencia bajo la [GNU General Public License](/LICENSE.txt)
