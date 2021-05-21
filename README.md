# Proyecto
Es mi proyecto final
Presentación del proyecto final.
Título del proyecto: Juego del ahorcado
Justificación.
Mi justificación del porqué quiero hacer este programa es porque me gustan mucho los videojuegos, y aparte siento que es un muy buen proyecto para mi para practicar en un futuro si quiero dedicarme hacer algún videojuego o algo similar y creo es muy sencillo este programa. A lo mejor es algo que no hemos visto en clase pero es fácil al menos para mi.



Lenguaje a utilizar.
Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en la legibilidad de su código. Se trata de un lenguaje de programación multiparadigma, ya que soporta parcialmente la orientación a objetos, programación imperativa y, en menor medida, programación funcional. Es un lenguaje interpretado, dinámico y multiplataforma.


Primera parte del juego
Esta primera parte del juego, es muy sencilla y básica. Aquí solamente importamos el módulo “random”; este módulo, nos será muy útil, para poder generar un dato aleatorio, para así elegir una palabra entre muchas. Estas palabras están contenidas en una lista que programaremos más adelante.
Primer paso
Aquí realizamos un pequeño dibujo. Para así mostrarle al jugador, si está ahorcado o no.
import random
AHORCADO = ['''
      +---+
      |   |
          |
          |
          |
          |
    =========''', '''
      +---+
      |   |
      O   |
          |
          |
          |
    =========''', '''
      +---+
      |   |
      O   |
      |   |
          |
          |
    =========''', '''
      +---+
      |   |
      O   |
     /|   |
          |
          |
    =========''', '''
      +---+
      |   |
      O   |
     /|\  |
          |
          |
    =========''', '''
      +---+
      |   |
      O   |
     /|\  |
     /	|
          |
    =========''', '''
      +---+
      |   |
      O   |
     /|\  |
     / \  |
          |
    =========''']
Segundo paso
Ahora le otorgamos una serie de datos a “palabras”. Vamos a rellenarlo con todas y cada una de las palabras que serán usadas en nuestro juego.
Al iniciar una partida en nuestro juego, estas serán las palabras con las que nuestro programa nos pondrá a prueba.
Luego vamos a definir una función denominada “buscarPalabraAleat” que nos da una palabra aleatoria de nuestra lista.
Tercer paso
En este paso, definiremos algunas funciones, que nos permitirán mostrar mensajes en la consola con la letra incorrecta. Además se nos mostrara un dibujo “distinto”. Ya que se irá completando, hasta estar totalmente ahorcado.
Mas adelante, haremos otra función que nos permita comprobar si la letra que ingresamos está repetida, y le pediremos que ingrese una letra diferente.
Esto podemos hacerlos mediante los comandos if, elif y else.
Cuarto paso
En este pedazo de código, que te muestro a continuación; desarrollaremos la función “empezar”. Con ella, sabremos si nuestro jugador quiere jugar de nuevo, o no.
Más adelante dejamos unos trozos de código dentro de los cuales vamos a añadir la opción de jugar de nuevo y mostrar mensajes para cuando el jugador pierde o gana. Para todo esto haremos uso de las funciones previas.
Ahora vamos a hacer un análisis acerca de las estructuras y funciones que desarrollamos y utilizamos en la construcción de nuestro código, como lo son las listas en Python.
Módulo import random
Como tenemos que utilizar una palabra al azar, es importante usar este módulo. Con este módulo, se elegirá una palabra al azar, con la cual jugaremos.
AHORCADO = ['''
+---+
| |
|
|
|
|
=========''', '''
Realmente, el resto del código, es muy largo para colocarlo aqui; sin embargo, la variable AHORCADO, es utilizada hasta el final de la llave ].
Con esta línea de código, hacemos una asignación de variables, que se extiende a lo largo de distintas líneas.
Líneas múltiples en lenguaje Python
Generalmente, si escribimos texto en nuestro código, este se sitúa en una sola línea. Sin embargo, si utilizas un grupo de tres comillas dobles al comenzar, y al terminar nuestro texto, podemos hacer que ocupe varias líneas. Por ejemplo:
#Ejemplo:
>>>prueba = """hola
esto es una prueba
utilizando tres comillas"""
Listas en python
Las listas en Python, son simples variables capaces de contener o albergar, muchos valores dentro de sí. Probemos escribir el texto siguiente en un shell interactivo en Python:
>>>colores = ["rojo", "azul", "naranja"]
>>>print colores
["rojo", "azul", "naranja"]
Las listas son un excelente recurso para almacenar varios valores en una sola variable. Cada valor individual almacenado dentro de la lista, se llama elemento.
Puedes utilizar corchetes para acceder a un elemento ubicado dentro de una lista. Prueba escribir esto: colores[0], colores[1], colores[2].
>>>colores[0]="rojo"
>>>colores[1]="azul"
>>>colores[2]="naranja”
