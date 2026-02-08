# Práctica 2: Creación API REST

En esta práctica se nos pide la creación de un servidor web REST que responda a las acciones CRUD.

## Repositorio GIT
En este caso, para crear el repositorio de git lo hemos hecho a través de la terminal con el comando ***git init***. A continuación, para poder vincularlo con github hemos creado un repositorio allí a través de "crear repositorio ya existente".
Para poder conectar las dos ramas era necesario hacer un commit con cambios añadidos y desde ahí hacer el push. A la hora de añadir los archivos al commit podemos observar como hay archivos ocultos que no basta con hacer el git add *. Utilizamos entonces lo siguiente:

```
git add * // Para añadir todos los elementos visibles
git add .* // Para añadir todos los elementos ocultos
```

Una vez mandado el commit podemos recargar github y encontraremos todos nuestros archivos copiados.

## Código JAVA

Nos creamos las dos clases Java de Carrito y CarritoControlador y programamos en ellas los distintos métodos CRUD.

|HTTP Status Codes|Descripción|
|---|---|
|200|Todo correcto|
|201|CREATED|
|400|Error en el paso de parámetros|
|405|No existe el path especificado|
