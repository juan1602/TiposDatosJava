# TIPOS DE DATOS EN JAVA

## JVM(Java Virtual Machine)

* Realiza una gestion efciiente de la memoria.
* Distribuye la memoria en dos zonas: stack(pila) y heap (montón)

![RAM](/modelo/ram.jpeg "RAM")

### Stack
* Se alamacenan : variables locales, llamadas a métodos(parametros de resultados), variables primitivas, referencias a objetos del heap.
* Memoria estática.

### Heap
* Gestionado por el Garbage Collector
* Espacio de memoria en tiempo de ejecución donde se registran los objetos.
* Memoria dinámica.
* No posee estructura de asignación de espacios.

### Variable
* Contenedor de memoria donde se almacena informacion.
* En Java se declara como un tipo que se conservara durante todo su ciclo de vida en el interior de la app.
* La varibale debe tenr un nombre.
* Existen de tipo primitivo y referenciado.

## PRIMITIVOS
* Contenedores de tamaño específico  que almacenan valores y no tienen métodos.
* Ejemplos: boolean, char, byte, short, long, float, double.

## REFERENCIADOS
* Almacenan las referencias a los datos
* Estos datos se escriben en una zona de memoria llamada heap.
* Accesible desde otras instancias de clase 
* Su cicclo de vida termina cuando no se necesita más
* Mientras exista al menos una referencia activa en la zona de datos esta se mantendrá.
* Tan pronto como no hayan más referencias, la zona se considera no utilizada y se procede a su destruccion por parte del Garbage Collector.
* Un tipo referenciado puede no referenciar nada -> null.
* El operador new: se utiliza para instanciacion de una clase. Reserva una dirección de area de memoria

### Variable de referencia 
* Caracteriza una instancia de clase, es decir la direccion donde está el objeto.
* Contiene la direccion de un objeto, cuyo valor por defecto es null.
* Durante una prueba e igualdad entre dos variables por referencia, son las direcciones de los objetos lo que se compara, y no el contenido de los objetos en si mismos.
* Cuando se usa una referencia como argumento de un método es la dirección del objeto lo que se pasa, y no el objeto en si mismo.
