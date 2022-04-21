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
