# TRABAJO PRÁCTICO ESPECIAL

  

**Cátedra**: Tecnología de la Información en las Organizaciones

**Carrera**: Tecnicatura en Desarrollo de Aplicaciones Informáticas

  

**Integrantes**:

  

* Studler, Ana

* Argüelles, Facundo

* Salvadó, Alejandra

  

## PROGRAMACIÓN EN PYTHON

Python se denomina **lenguaje interpretado** porque pasa por un intérprete que convierte el código que escribe en el idioma que entiende el procesador de su computadora. Un intérprete toma el código que escribe y ejecuta las acciones que haya especificado, crea las variables que has creado y realiza una gran cantidad de trabajo en segundo plano para asegurarse de que funcione sin problemas o te informa sobre errores.

### Principales Usos de Python

Es un lenguaje de programación versátil **multiplataforma y multiparadigma** que se destaca por su código legible y limpio. La licencia de código abierto permite su utilización en distintos contextos sin la necesidad de abonar por ello y se emplea en plataformas de alto tráfico como Google, YouTube o Facebook. Su objetivo es la **automatización de procesos para ahorrar tanto complicaciones como tiempo**, los dos pilares en cualquier tarea profesional. Dichos procesos se reducirán en pocas líneas de código que insertarás en una variedad de plataformas y sistemas operativos. Python es la opción por defecto de lenguaje de scripting para muchos desarrolladores.
Python es ideal para trabajar con **grandes volúmenes de datos* porque favorece su extracción y procesamiento, siendo el elegido por las empresas de **Big Data**. A nivel científico, posee una amplia biblioteca de recursos con especial énfasis en las matemáticas para aspirantes a programadores en áreas especializadas. 
Asimismo, Python puede ayudarte a la hora de llevar a cabo una **visualización de datos avanzada**, esencial en el proceso de decisión. 
Python, asimismo, también está consolidándose a la hora de dar acceso al trabajo con matrices y tablas de forma eficiente, a ejecutar cálculo estadístico avanzado y a aplicar algoritmos de **Machine Learning** sobre esas estructuras.
#### Frameworks Web
Entre sus numerosos Frameworks, nos podemos encontrar unas bestias: **Django** y **Flask**.
Django sería lo más cercano a Laravel en PHP o Ruby on Rails para Ruby. Un marco de trabajo completo y eficiente para desarrollar Aplicaciones Web de una gran complejidad con un mínimo esfuerzo. Casi cualquier cosa que necesites posiblemente estará integrado.
Para desarrollos altamente personalizados o con unos tiempos cortos, nos encontramos a Flask. Autodenominado microframework, pero con funcionalidades sencillas e inteligentes para construir cualquier sitio que se te pase por la cabeza.


### TIPOS DE DATOS BÁSICOS

En Python, y cuando se programa en general, necesitamos construir sistemas para manejar los datos que cambian con el tiempo. Esa información podría ser la ubicación de un avión, o la hora del día, o el programa de televisión que está viendo actualmente. Lo único importante es que puede ser diferente en diferentes momentos. Python usa _variables_ para definir cosas que están sujetas a cambios.


En Python existen varios tipos de datos, comenzaremos por utilizar y entender los tres tipos datos básicos que tenemos en Python:

* **Números:** como es el caso de 5 (entero), 34.21 (coma flotante) o también tenemos el caso de 3+8 (complejo).

* **Cadenas de texto (strings):** por ejemplo la famosa frase _“Hola Mundo”_. Una cadena, llamada así porque son una serie de letras, números o símbolos conectados en orden, como si estuvieran unidos por una cuerda. Se pueden combinar varias cadenas usando +.

* **Valores booleanos:** Verdadero y Falso

Debemos tomar en cuenta que en Python no es necesario declarar el tipo de variable, como si es el caso de otros lenguajes de programación, como por ejemplo Java.

  

###OPERADORES

El operador **==** es uno de los operadores de comparación; los otros son:

* x != y x no es igual a y

* x > y x es mayor que y

* x < y x es menor que y

* x >= y x es mayor o igual que y

* x <= y x es menor o igual que y

Aunque probablemente estas operaciones le resulten familiares, los símbolos en
Python son diferentes de los matemáticos. Un error habitual es utilizar un signo
igual sencillo (=) en lugar del doble (==). Recuerde que = es un operador de
asignación y == es un operador de comparación.



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

### El bucle _for_
En general, un bucle es una estructura de control que repite un bloque de instrucciones. Un bucle _for_ es un bucle que repite el bloque de instrucciones un número prederminado de veces. El bloque de instrucciones que se repite se suele llamar cuerpo del bucle y cada repetición se suele llamar **iteración**.

La sintaxis de un bucle for es la siguiente:

**for** _variable_ **in** _elemento iterable_ (lista, cadena, range, etc.):

	cuerpo del bucle
  
No es necesario definir la variable de control antes del bucle, aunque se puede utilizar como variable de control una variable ya definida en el programa.
El cuerpo del bucle se ejecuta tantas veces como elementos tenga el elemento recorrible (elementos de una lista o de un _range()_, caracteres de una cadena, etc.).


### El bucle while
Un bucle _while_ permite repetir la ejecución de un grupo de instrucciones mientras se cumpla una condición (es decir, mientras la condición tenga el valor _True_).
La sintaxis del bucle _while_ es la siguiente:

**while** _condicion_:
	cuerpo del bucle
 
Cuando llega a un bucle _while_, Python evalúa la condición y, si es cierta, ejecuta el cuerpo del bucle. Una vez ejecutado el cuerpo del bucle, se repite el proceso (se evalúa de nuevo la condición y, si es cierta, se ejecuta de nuevo el cuerpo del bucle) una y otra vez mientras la condición sea cierta. Únicamente cuando la condición sea falsa, el cuerpo del bucle no se ejecutará y continuará la ejecución del resto del programa.
La variable o las variables que aparezcan en la condición se suelen llamar **variables de control**. Las variables de control deben definirse antes del bucle while y modificarse en el bucle while.


