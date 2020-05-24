# Explicacion-HashSet

## HashSet
HashSet es una **colección** que contiene elementos no ordenados. Forma parte de una de las implementaciones de la interfaz **Set**. Una de las características de HashSet es que *no permite repetir elementos*, y que no sabremos en qué orden se almacenarán. Todos ellos se guerdan en una tabla Hash. Su principal ventaja es la velocidad, por lo que en ciertas situaciones, el uso de HashSet puede ser crucial.

## Métodos de HashSet
* boolean add: Solo se añade si el elemento no está presente en Set.
* void clear(): Elimina todos los elementos del Set.
* Object clone(): Devuelve una copia del objeto del hashSet.
* boolean contains: Devuelve true si si contiene el elemento especificado.
* boolean isEmpty(): Comprueba si el hashSet está vacío o no.
* Iterator iterator(): Devuelve el iterador, para que puede recorrer los elementos del hashSet.
* boolean remove: Elimina la primera ocurrencia del elemento especificado.
* int size(): Devuelve el tamaño del hashSet

## Funcionamiento de HashSet
Aquí se puede ver una simple aplicación que utilizará HashSet para mostrar unos modelos de teléfonos móviles. Los modelos son iterados con Iterator y acaban siendo mostrados de forma no ordenada.

![hashcode](https://github.com/torrespedrob/Explicacion-HashSet/blob/master/hashcode.png)

### Salida
Esta es la salida de la aplicación, como se puede ver, aparece desordenada.

![hashrunning](https://github.com/torrespedrob/Explicacion-HashSet/blob/master/hashrunning.png)
