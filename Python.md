﻿# TRABAJO PRÁCTICO ESPECIAL

  

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

### Comentarios

Los comentarios en Python, al igual que sucede en otros lenguajes de programación, sirven para explicar a las personas que puedan leer el programa en el futuro, qué es lo que hace el programa, así como explicar algunas partes del código. Estos comentarios son ignorados por las computadoras cuando ejecutan el código.
En python los comentarios se pueden poner de dos formas:
* Escribiendo el símbolo almohadilla delante de la línea de texto donde está el comentario.
```python
# Este es un comentario en python
```
* Escribiendo triple comilla doble (“””) al principio y al final del comentario (que puede ocupar más de una línea).
```python
""" Este es un comentario multilínea. Y
este texto solo quiere ocupar
múltiples líneas """
```
  
### Salida por pantalla: la función print()
En los programa, para mostrar texto o variables hay que utilizar la función _print()_.
La función _print()_ permite mostrar texto en pantalla. El texto a mostrar se escribe como argumento de la función:

 ```python
print("Hola")
Hola
```
Las cadenas se pueden delimitar tanto por comillas dobles (") como por comillas simples ('). Una cadena debe abrirse y cerrarse con el mismo tipo de comillas.
```python
print('Hola')
```
La función _print()_ permite incluir variables o expresiones como argumento, lo que nos permite combinar texto y variables:

```python
nombre = "Pepe"
edad = 25
print("Me llamo", nombre, "y tengo", edad, "años.")
Me llamo Pepe y tengo 25 años.
```
  
### Entrada por teclado: la función input()

La función _input()_ permite obtener texto escrito por teclado. Al llegar a la función, el programa se detiene esperando que se escriba algo y se pulse la tecla **Intro**, como muestra el siguiente ejemplo:

```python
print("¿Cómo se llama?")
nombre = input()
print(f"Me alegro de conocerle, {nombre}")

¿Cómo se llama?
Pepe
Me alegro de conocerle, Pepe
```

### Conversión de tipos
De forma predeterminada, la función _input()_ convierte la entrada en una cadena, aunque escribamos un número. Si intentamos hacer operaciones, se producirá un error.
Si se quiere que Python intérprete la entrada como un número entero, se debe utilizar la función _int()_ de la siguiente manera:

```python
cantidad = int(input("Dígame una cantidad en pesetas: "))
```

De la misma manera, para que Python interprete la entrada como un número decimal, se debe utilizar la función _float()_.

```python
cantidad = float(input("Dígame una cantidad en euros (hasta con 2 decimales): "))
```

 
### Sentencias condicionales: if ... elif ... else ...
La estructura de control **if** ... permite que un programa ejecute unas instrucciones cuando se cumplan una condición. En inglés "if" significa "si" (condición). La orden en Python se escribe así:

**if** condición:

    aquí van las órdenes que se ejecutan si la

    condición es cierta

    y que pueden ocupar varias líneas

La primera línea contiene la condición a evaluar y es una expresión lógica. Esta línea debe terminar siempre por dos puntos (:).
A continuación viene el bloque de órdenes que se ejecutan cuando la condición se cumple (es decir, cuando la condición es verdadera). Es importante señalar que este bloque debe ir sangrado (indentado), puesto que Python utiliza el sangrado para reconocer las líneas que forman un bloque de instrucciones.
Los fragmentos de código escritos en el mismo nivel de sangría en Python constituyen un bloque de código.


#### Bifurcaciones: **if** ... **else** ...
La estructura de control _if ... else ..._ permite que un programa ejecute unas instrucciones cuando se cumple una condición y otras instrucciones cuando no se cumple esa condición.

**if** _condición_:

	aquí van las órdenes que se ejecutan si la condición es cierta

	y que pueden ocupar varias líneas

**else**:

	y aquí van las órdenes que se ejecutan si la condición es

	falsa y que también pueden ocupar varias líneas

  
 La primera línea contiene la condición a evaluar. A continuación viene el bloque de código que se ejecuta cuando la condición se cumple (es decir, cuando la condición es verdadera).
Después viene la línea con la orden else, que indica a Python que el bloque que viene a continuación se tiene que ejecutar cuando la condición no se cumpla (es decir, cuando sea falsa). La línea con la orden else no debe incluir nada más que el else y los dos puntos.
En último lugar está el bloque de instrucciones sangrado que corresponde al else.
Si por algún motivo no se quisiera ejecutar ninguna orden en alguno de los bloques, el bloque de órdenes debe contener al menos la orden _pass_ (esta orden le dice a Python que no tiene que hacer nada).
  

#### Más de dos alternativas: **if** ... **elif** ... **else** ...
La estructura de control _if ... elif ... else ..._ permite encadenar varias condiciones. _elif_ es una contracción de _else if_. La orden en Python se escribe así:

**if** _condición1_:
	bloque 1

**elif** _condición2_:
	bloque 2

**else**:
	bloque 3

Si se cumple la condición 1, se ejecuta el bloque 1.
Si no se cumple la condición 1 pero sí que se cumple la condición 2, se ejecuta el bloque 2.
Si no se cumplen ni la condición 1 ni la condición 2, se ejecuta el bloque 3.
Se pueden escribir tantos bloques elif como sean necesarios. El bloque else (que es opcional) se ejecuta si no se cumple ninguna de las condiciones anteriores.



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


### Listas
Una lista es una estructura de datos y un tipo de dato en python con características especiales. Lo especial de las listas en Python es que nos permiten almacenar cualquier tipo de valor como enteros, cadenas y hasta otras funciones; por ejemplo:

```python
lista = [1, 2.5, 'programacion', [5,6] ,4]
```
Una lista es un arreglo de elementos donde podemos ingresar cualquier tipo de dato, para acceder a estos datos podemos hacer mediante un índice.
 
```python
print lista[0] # 1
print lista[1] # 2.5
print lista[2] # programacion
print lista[3] # [5,6]
print lista[3][0] # 5
print lista[3][1] # 6
print lista[1:3] # [2.5, 'programacion']
print lista[1:6] # [2.5, 'programacion', [5, 6], 4]
print lista[1:6:2] # [2.5, [5, 6]]
```
Como pueden darse cuenta podemos hasta insertar una lista dentro de otra lista.
Si no quieres estar imprimir uno por uno los elementos de una lista, puedes recorrerlo utilizando un **for**.
 
```python
for element in lista:
    print element
```
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
 



### Como lenguaje orientado a objetos.

El objetivo principal de un lenguaje orientado a objetos es hacer que el código sea reutilizable; esto se logra usando clases y objetos. Por ejemplo: Para diseñar un nuevo tipo de automóvil, se puede comenzar con lo que tienen en común: ruedas, asientos, un marco. Luego de determinar qué tienen los automóviles en común, podemos implementar más fácilmente cualquier tipo de automóvil que deseemos empezando a partir de ese modelo básico.

