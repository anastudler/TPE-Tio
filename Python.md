# TRABAJO PRÁCTICO ESPECIAL

  

**Cátedra**: Tecnología de la Información en las Organizaciones

**Carrera**: Tecnicatura en Desarrollo de Aplicaciones Informáticas

  

**Integrantes**:

  

* Studler, Ana

* Argüelles, Facundo

* Salvadó, Alejandra

  

## PROGRAMACIÓN EN PYTHON

Python se denomina **lenguaje interpretado** porque pasa por un intérprete que convierte el código que escribe en el idioma que entiende el procesador de su computadora. Un intérprete toma el código que escribe y ejecuta las acciones que haya especificado, crea las variables que has creado y realiza una gran cantidad de trabajo en segundo plano para asegurarse de que funcione sin problemas o te informa sobre errores.

#### Métodos de las Listas
Las listas en Python  tienen muchos métodos que podemos utilizar, entre todos ellos vamos a nombrar los más importantes.
 
 
#### Append()
Este método nos permite agregar nuevos elementos a una lista.
 
```python
my_list.append(10) # [2, 5, 'programacion', 1.2, 5, 10]
my_list.append([2,5]) # [2, 5, 'programacion', 1.2, 5, [2, 5]]
```
Podemos agregar cualquier tipo de elemento a una lista, pero tengan en cuenta lo que pasa cuando agregamos una lista dentro de otra, esta lista se agrega como uno y solo un elemento.
 
#### Remove()
El método remove va a remover un elemento que se le pase como parámentro de la lista a donde se le esté aplicando.
 
```python
my_list.remove(2) # [5, 'programacion', 1.2, 5]
```
En este ejemplo estamos removiendo el elemento 2, de la lista que tiene por nombre _"my_list"_.
 
 
#### Index()
Index devuelve el número de índice del elemento que le pasemos por parámetro.
 
```python
my_list.index('programacion') # 2
```
Aquí estamos preguntando por el índice de la cadena 'programacion' dentro de la lista _"my_list"_, esto devuelve 2.
 
 
### Tuplas
 
Una tupla permite tener agrupados un conjunto inmutable de elementos, es decir, en una tupla no es posible agregar ni eliminar elementos. Las tuplas se declaran separando los elementos por comas y éstos, opcionalmente, pueden ir entre paréntesis. Se recomienda el uso de paréntesis para evitar ambigüedades del tipo: print(9, 8, 7) y print((9, 8, 7)).
```python
tuplaDiasSemana = (“LU”, “MA”, “MI”, “JU”, “VI”, “SA”, “DO”)  # Declara tupla
```
 
 
### Diccionarios o matrices asociativas
 
Los diccionarios son objetos que contienen una lista de parejas de elementos. De cada pareja un elemento es la clave, que no puede repetirse, y, el otro, un valor asociado. La clave que se utiliza para acceder al valor tiene que ser un dato inmutable como una cadena, mientras que el valor puede ser un _número_, una _cadena_, un _booleano_ (True/False), una _lista_ o una _tupla_.
Los pares **clave-valor** están separados por dos puntos, las parejas por comas y todo el conjunto se encierra entre llaves.
 
Ejemplos:
```python
capitales = {'Chile':'Santiago', 'España':'Madrid', 'Francia':'París'}
```
 
Para definir un diccionario vacío hay dos opciones:
```python
capitales = {}
capitales = dict() 
```
