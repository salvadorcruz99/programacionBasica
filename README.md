# programacionBasica
# curso completo de python 
**ESTO ES UN RESUMEN DE LA MATERIA DE PROGRAMACION BASICA ENFOCADO AL USO DE PYTHON Y SUS FUNCIONES**

**COMENZEMOS PREGUNTANDO ¿QUE ES PYTHON?**

Queremos presentar un lenguaje de programación de propósito general, cuya expansión y popularidad es relativamente reciente.

 Se trata de Python, una apuesta por la simplicidad, versatilidad y rapidez de desarrollo. A continuación, veremos unas notas imprescindibles del lenguaje, extractadas básicamente de la página de inicio del lenguaje que se puede ver en [www.python.org](http://www.python.org/)

Python es un lenguaje de scripting independiente de plataforma y orientado a objetos, preparado para realizar cualquier tipo de programa, desde aplicaciones Windows a servidores de red o incluso, páginas web. Es un lenguaje interpretado, lo que significa que no se necesita compilar el código fuente para poder ejecutarlo, lo que ofrece ventajas como la rapidez de desarrollo e inconvenientes como una menor velocidad.

Programar una computadora es una habilidad que mejor se aprende mediante la practica por lo que es importante gastar el tiempo frente a la computadora poniendo en práctica la teoría usada en clase

La ventaja de los lenguajes compilados es que su ejecución es más rápida sin embargo los lenguajes interpretados son mas flexibles y portables

Este reporte esta diseñado para mostrar ejercicios que cubren una variedad de diciplinas académicas y situaciones día a día

Cada ejercicio complementa su entendimiento y su habilidad para enfrentar desafíos de programación

**COMENZAREMOS DESCRIBIENDO Y EJEMPLIFICANDO CADA UNA DE LAS FUNCIONES DE PYTHON**

**PRINT**

En los programas, para que python nos muestre texto o variables hay que utilizar la función print().

La función print() permite mostrar texto en pantalla. El texto a mostrar se escribe como argumento de la función:

Las cadenas se pueden delimitar tanto por comillas dobles (&quot;) como por comillas simples (&#39;).

La función print() admite varios argumentos seguidos. En el programa, los argumentos deben separarse por comas. Los argumentos se muestran en el mismo orden y en la misma línea, separados por espacios:

Cuando se trata de dos cadenas seguidas, se puede no escribir comas entre ellas, pero las cadenas se escribirán seguidas, sin espacio en blanco entre ellas

Al final de cada print(), Python añade automáticamente un salto de línea:

Para generar una línea en blanco, se puede escribir una orden print() sin argumentos.

Como las comillas indican el principio y el final de una cadena, si se escriben comillas dentro de comillas se produce un error de sintaxis.

La función print() permite incluir variables o expresiones como argumento, lo que nos permite combinar texto y variables.

**EJEMPLOS**

1.- Crear un programa que despliegue tu nombre con una variable

print(&#39;inserta tu nombre&#39;) #insertar el nombre de la persona

nombre = input()     #input sirve para dar entrada a una respuesta

print (&#39;hola &#39; + nombre)   #el programa imprimirá hola y el nombre de la persona

2.- Escriba un programa en el cual despliegue nombre , dirección , código postal como en una carta

nombre=&#39;Salvador Cruz urvina&#39; #variable

calle=&#39;Chalchihuites 23&#39; #variable

colonia=&#39;San Jose de los Leones&#39;    #variable

municipio=&#39;Naucalpan de Juarez&#39;    #variable

estado=&#39;Estado de Mexico&#39;   #variable

codigo\_postal=53760     #variable

print(nombre + &#39;\n&#39; + calle + &#39;\n&#39; + colonia + &#39;\n&#39; + municipio + &#39;\n&#39; + estado + &#39;\n&#39; ,codigo\_postal)  #en el programa se mete como argumento todas la variables usando un + y comillas en &#39;\n&#39;

3.- Escriba un programa en la que el usuario determine la cantidad de estatura determinada en pies y pulgadas

pies = 2.54 centimetros

Pulgadas = 12 pulgadas

metros = 100 cm

estatura de Gibby = 150 centimetros

print(&#39;Cual es la estatura de Gibby en pies&#39;)

print(&#39;Cual es la estatura de Gibby en pulgas&#39;)

print(&#39;150 centimetros \* 12 pulgadas&#39;)

print(&#39;150 centimetros \* 2.54 centimetros&#39;)

**2.- FUNCION FLOAT, INT**

El método float () se usa para devolver un número de punto flotante desde un número o una cadena.

El método solo acepta un parámetro y también es opcional de usar. Veamos los distintos tipos de argumentos, el método acepta:

1. **a)****Un número:** puede ser un número entero o flotante.

1. **b)****Una cuerda:**

1.
  1. Debe contener números de cualquier tipo.
  2. Cualquier espacio en blanco izquierdo o derecho o una nueva línea es ignorada por el método.
  3. Se pueden utilizar operadores matemáticos.
  4. Puede contener NaN, Infinity o inf (en cualquier caso)

**Valores que el método float () puede devolver dependiendo del argumento pasado:**

- Si se pasa un argumento, se devuelve el número de punto flotante equivalente.
- Si no se pasa ningún argumento, el método devuelve 0.0.
- Si se pasa una cadena que no es un número de punto decimal o no coincide con ninguno de los casos mencionados anteriormente, se generará un error.

Ahora veamos varios ejemplos y el funcionamiento del método float ():

1.- Crear un programa que te de el lugar exacto en donde se ubica la ficha dependiendo de su posición en un tablero de ajedrez

x=input(&#39;ingresa la corderdenada en letra&#39;)

y=int(input(&#39;ingresa la corderdenada 2 en numero&#39;))

a=y%2

if x == a :

     print(&#39;es blanco&#39;)

elif:

    print(&#39;es negro&#39;)

2.- Escriba un programa que calcule el largo y ancho de una habitación dependiendo de los valores dados por el usuario y además el resultado lo de en metros cuadrados

argo = float(input(&#39;insertar el largo de la habitacion: &#39;))

ancho = float(input(&#39;insertar el ancho de tu habitacion: &#39;))

area = largo \* ancho

print(&#39;el area de tu habitacion es&#39; ,area, &#39;metros cuadrados&#39;)

3.- Escriba un programa que calcule el área de un campo de futbol y además lo determine en pies , metros cuadrados y acres

-\*- coding: utf-8 -\*-

print(&#39;hola chava que vas a medir&#39;)

respuesta=input()

largo=float(input(&#39;cuanto mide el largo del campo de futbol: &#39;))

ancho=float(input(&#39;cuanto mide el ancho del campo de futbol: &#39;))

area=largo \* ancho

area2=area \* 90.70

area3=area2 / 43560

print(&#39;el area del campo de futbol es&#39; ,area, &#39;metros cuadrados&#39;)

print(&#39;el area del campo de futbol es&#39; ,area2, &#39;en pies cuadrados&#39;)

print(&#39;el area del campo de futbol es&#39; , area3, &#39;en acres&#39;)

4.- Escriba un programa que determine la suma de la cantidad ingresada

numero=int(input(&#39;ingresa un numero:&#39;))

suma=(numero\*(numero+1))/2

print(suma)

5.- Escriba un programa en el que en una tienda donde se vende widgates y gizmos , y que  una persona lleve n numero de productos y de gizmos  y el programa determine el peso de cada producto y al final determine el peso total

widgets=int(input(&#39;ingresa el numero de widgets:&#39;))

gizmo=int(input(&#39;ingresa el numero de gizmos:&#39;))

peso1=widgets\*75

peso2=gizmo\*112

peso3=peso1 + peso2

print(&#39; el peso de widgets es:&#39;,peso1,)

print(&#39; el peso de gizmos es:&#39;,peso2,)

print(&#39; el peso total es:&#39;,peso3,&#39;gramos&#39;)

6.- Escriba un programa en el que se trate el tema de un banco en el que un usuario invierta cierta cantidad y al pasar de cierto tiempo imprima el interés generado durante 1, 2 y 3 años

inversion= float(input(&#39;ingrese el monto que desea invertir:&#39;))

interes= inversion\*4/100

a2=inversion\*2

a3=inversion\*3

print(&#39;el interes generado en su cuenta de ahorro al cabo de 1 anios es:&#39;,interes,&#39;pesos&#39;)

print(&#39;el interes generado en su cuenta de ahorro al cabo de 2 anios es:&#39;,a2,&#39;pesos&#39;)

print(&#39;el interes generado en su cuenta de ahorro al cabo de 3 anios es:&#39;,a3,&#39;pesos&#39;)

7.- Escriba un programa en el que el usuario introduzca la cantidad de km recorrisdos por un taxi sabiendo que por cada vez que recorra 40 km la cantidad aumente 7 pesos , asi que el programa deberá calcular la tarifa total

ilo=input(&#39;ingrese la distancia recorrida en kilometros:&#39;)

def tarifa(ilos):

    return (40+7\*ilo)

    resultado=tarifa(ilos)

print(resultado)

8.- Escriba un programa en el que se calcule el area de un triangulo usando formula simple e introduciendo los datos de base y altura

print(&#39;calcular el area de un triangulo usando b y h&#39;)

longitud=float(input(&#39;inserta cuando medira b: &#39;))

b=longitud

altura=float(input(&#39;inserta cuanto medira h: &#39;))

h=altura

area= b \* h / 2

print(&#39;el area del triangulo es&#39; ,area, &#39;centimetros cuadrados&#39;)



9.- Escriba un programa en el que se obtenga la equivalencia en metros dependiendo de las cantidades especificas de pies y pulgadas

print(&#39;obten elequivalente en metros de los siguientes datos&#39;)

pies= float(input(&quot;inserta elnumero de millas: &quot;))

pulgadas= float(input(&quot;inserta el numero de pulgadas: &quot;))

metros= 0.3048 \* pies + 0.0254 \* pulgadas

print(&#39;tienes un equivalente de&#39; ,metros, &#39;metros&#39;)

10.- Escriba un programa en el que determine la cantidad de seguntos de las cantidades en años, horas y minutos

dias=float(input(&#39;inserta el numero de dias: &#39;))

d=dias

horas=float(input(&#39;inserta el numero de horas: &#39;))

h=horas

minutos=float(input(&#39;inserta el numero de minutos: &#39;))

m=minutos

segundos=float(input(&#39;inserta el numero de segundos: &#39;))

s=segundos

resultado=d \* 86400

resultado2= h \* 3600

resultado3= m \* 60

resultado4= s \* 1

resultado5= resultado + resultado2 + resultado3 + resultado4

print(&#39;en dias tienes&#39; ,resultado,&#39;segundos&#39;)

print(&#39;en horas tienes&#39; ,resultado2, &#39;segundos&#39;)

print(&#39;en minutos tienes&#39; ,resultado3,&#39;segundos&#39;)

print(&#39;en segundos tienes&#39; ,resultado4,&#39;segundos&#39;)

print(&#39;tienes un total de&#39; ,resultado5,&#39;segundos&#39;)



11.- Escriba un programa en el que se determine la eficiencia de gasolina dependiendo la cantidad de litros introducida por el usuario

numero=float(input(&#39;ingrese la cantidad de eficiencia de gasolina: &#39;))

eficiencia=235.215/numero

print(&#39;la eficiencia de gasolina en L/100km es: &#39;,eficiencia,)

12.- Escriba un programa que determine en unidades conocidas por el país de MPG ingresadas por el usuario y el resultado sea en L/km

milla=float(input(&#39;ingresa el numero de MPG:&#39;))

conversion=235.215/milla

print(&#39;la conversion a unidades mexicanas es:&#39;,conversion,&#39;L/100km&#39;)

13.-  Escriba un programa en el que apartir de dos números enteros el sistema determine la suma, resta, multiplicación , división y potencia entre ellos

numero1 = float(input(&#39;inserte un numero entero: &#39;))

a = numero1

numero2 = float(input(&#39;inserte un numero entero: &#39;))

b = numero2

suma=a+b

resta=a-b

producto=a\*b

cociente=a/b

residuo=a%b

elevacion=a\*\*b

import math

print(&#39;la suma es&#39; ,suma,)

print(&#39;la resta es&#39; , resta,)

print(&#39;el producto es&#39; , producto,)

print(&#39;el cociente es&#39; , cociente,)

print(&#39;el residuo es&#39; , residuo,)

print(&#39;la elevacion es&#39; , elevacion,)

print(&#39;el logaritmo 10 de a es:&#39;,math.log(a))

14.- En una cuenta de ahorro se ingresa cierta cantidad por cierto tiempo por lo cual se cobra un interés de un 4.22, 8.34 y 12.59 , sabiendo que se deposita cierta cantidad , determinar la cantidad total ya aplicando el interés

print(&#39;Cuenta de ahorro&#39;)

ahorro = float(input(&#39;ingrese la cantidad que se ahorra: &#39;))

interes= ahorro/100\*4.22

interes2= ahorro/100\*8.34

interes3= ahorro/100\*12.59

total= ahorro + interes

total2= ahorro + interes2

total3= ahorro + interes3

print(&#39;la cantidad que se ahorra es&#39;,&#39;$&#39; ,total, &#39;MXN&#39;)

print(&#39;la cantidad que se ahorra es&#39;,&#39;$&#39; ,total2, &#39;MXN&#39;)

print(&#39;la cantidad que se ahorra es&#39;,&#39;$&#39; ,total3, &#39;MXN&#39;)

15.- Escriba un programa que calcule la suma de los numero dependiendo la cantidad introducida

print(&#39;DESPLIEGUE DE SUMA DE NUMEROS ENTEROS&#39;)

numero = float(input(&#39;inserte un numero entero y positivo: &#39;))

n= numero + 1

n2= numero + 2

n3= numero + 3

n4= numero + 4

n5= numero + 5

n6= numero + 6

n7= numero + 7

n8= numero + 8

n9= numero + 9

n10= numero + 10

suma = n \* n + 1

suma2= n2 \* n2 + 1

suma3= n3 \* n3 + 1

suma4= n4 \* n4 + 1

suma5= n5 \* n5 + 1

suma6= n6 \* n6 + 1

suma7= n7 \* n7 + 1

suma8= n8 \* n8 + 1

suma9= n9 \* n9 + 1

suma10= n10 \* n10 + 1

print(&#39;la suma de numeros es&#39; ,suma,)

print(&#39;la suma de numeros es&#39; ,suma2,)

print(&#39;la suma de numeros es&#39; ,suma3,)

print(&#39;la suma de numeros es&#39; ,suma4,)

print(&#39;la suma de numeros es&#39; ,suma5,)

print(&#39;la suma de numeros es&#39; ,suma6,)

print(&#39;la suma de numeros es&#39; ,suma7,)

print(&#39;la suma de numeros es&#39; ,suma8,)

print(&#39;la suma de numeros es&#39; ,suma9,)

print(&#39;la suma de numeros es&#39; ,suma10,)

16.-  Escriba el nombre de un restaurante y en ese mismo te muestre la cuenta tal cual lo haría en un ticket

restaurante = &quot;HUSH&quot;

direccion = &quot;Chalchihuites 23 San Jose de Los Leones&quot;

comida =float(input(&#39;ingrese precio de la comida: &#39;))

impuesto = comida/100\*16

propina = comida/100\*10

r = comida + propina + impuesto

print(restaurante)

print(direccion)

print(comida)

print(impuesto)

print(propina)

print(&#39;$&#39; , r , &#39;MXN&#39; )



17.-Escriba un programa en el que determine el total de botellas llevadas de 1L y mas de ¡l y además calcule el valor total sabiendo que mas de 1L = 2.50 y de  1 L = 1

 botella1=int(input(&#39;cuantas botellas de 1 litro o menos traes: &#39;))

botella2=float(input(&#39;cuantas botellas de 1 litro o mas traes: &#39;))

total=botella1 + botella2

print(&#39;tienes un total de&#39; ,total, &#39;botellas&#39;)

precio1=botella1 \* 1

print(&#39;el precio de botellas de menos de 1 litro es &#39;,precio1,&#39;pesos&#39;)

precio2=botella2 \* 2.50

print(&#39;el precio de botellas de mas de 1 litro es &#39;,precio2,&#39;pesos&#39;)

precio= precio1 + precio2

print(&#39;el precio total es&#39; ,precio,&#39;pesos&#39;)









**MODULO IMPORT MATH**

Cuando escribimos programas en nuestra vida diaria, usualmente nos encontramos con situaciones en donde necesitamos usar un poco de matemáticas para hacer una tarea. Como otros lenguajes de programación, Python proporciona varios operadores para realizar cálculos básicos como \* para multiplicación, % para módulos y // para división.

Si estás escribiendo un programa para realizar tareas específicas como estudiar movimiento periódico o simular circuitos eléctricos, necesitarás trabajar con funciones trigonométricas así como números complejos. Mientras que no puedes usar estas funciones directamente, puedes acceder a ellas incluyendo dos módulos matemáticos primero. Estos módulos son [math](https://docs.python.org/3/library/math.html) y [cmath](https://docs.python.org/3/library/cmath.html).

Una factorial es el producto de un entero y todos los enteros positivos menores que este. Es usado extensivamente cuando se trabaja con combinaciones y permutaciones. También puede ser usado para calcular el valor de las funciones seno y coseno.

**EJEMPLOS:**

1.- Escriba un programa en el que determine el area y volumen  de un circulo con los conocimientos básicos

import math

from math import pi

radio=float(input(&#39;ingresa el radio de la esfera: &#39;))

rad=radio

resultado = 3.1416\*(rad) \*\*2

volumen = 4 / 3 \* 3.1416 \* (rad) \*\* 3

print(&#39;tu area es&#39; ,resultado,&#39;centimetros cuadrados&#39; )

print(&#39;el volumen de la esfera es&#39; ,volumen, &#39;centimetros cubicos&#39;)





2.- Escriba un programa en el que determine la distancia de dos puntos que rodean la tierra en latitud y longitud

import math

from math import sin, cos, acos

latitud=float(input(&#39;ingresa tu latitud: &#39;))

lat=latitud

resultado= math.degrees(lat)

print(&#39;estas en&#39; ,resultado, &#39;grados al norte&#39;)

longitud=float(input(&#39;ingresa tu longitud: &#39;))

long=longitud

resultado2= math.degrees(long)

print(&#39;estas en&#39; ,resultado2, &#39;grados al oeste&#39;)

latitud2=float(input(&#39;ingresa tu segunda latitud: &#39;))

lat2=latitud2

resultado3= math.degrees(lat2)

print(&#39;estas en&#39; ,resultado3, &#39;grados al sur&#39;)

longitud2=float(input(&#39;ingresa tu segunda longitud: &#39;))

long2=longitud2

resultado4= math.degrees(long2)

print(&#39;estas en&#39; ,resultado4, &#39;grados al este&#39;)

distancia=  6371.01 \* acos(sin(latitud)) \* sin(latitud2) + cos(latitud) \* cos(latitud2) \* cos(longitud - longitud2)

print(&#39;la distancia entre los puntos que siguen la superficie de la tierra es de&#39; ,distancia, &#39;kilometros&#39;)











**MODULO IMPORT TIME:**

Python tiene un módulo llamado timepara manejar tareas relacionadas con el tiempo. Para usar las funciones definidas en el módulo, primero debemos importar el módulo. Así es cómo:

1. import time

La time()función devuelve el número de segundos pasados ​​desde la época.

**EJEMPLOS:**

1.- Escriba un programa que muestre la fecha y la hora actual

import time

print(&#39;la hora actual es &#39;,time.strftime(&quot;%I:%M:%S&quot;))

print(&#39;la fecha actual es &#39;,time.strftime(&quot;%d/%m/%y&quot;))

# MODULO IF, ELSE, ELIF

Si un programa no fuera mas que un alista de ordenes a ejecutar de forma secuencial, una por una, no tendría mucha utilidad

Las condiciones permiten comprobar condiciones y hacer que nuestro programa se comporta de una forma u otra, que ejecute un fragmento de código u otro, dependiendo de la condición

Aquí es donde toman importancia los operadores

Cuando utilizamos un if , la forma mas simple de una sentencia condicional en ingles seria (si), seguido de la condicion a evaluar (:) y en la siguiente línea e identado el código a ejecutar en caso de que se cumpla la condición.

If :  condiciones

Elif : comparación 3

Else : en caso de que los componentes no sean ciertos







EJEMPLOS:

1.- Escriba un código que describa si el numero introducido es par o impar

N = float(input(&#39;Introduce algun numero entero: &#39;)

if n%2 == 2:

    print(&#39;Este numero es par&#39;)

elif n%2 != 2:

    print(&#39;Este numero es impar&#39;)

2.- ESCRIBA UN PROGRAMA EL CUAL PUEDA IMPRIMIR EL NUMERO DE AÑOS DE UN HUMANO CONVERTIDOS A AÑOS PERRO DEPENDIENDO LA CANTIDAD DE AÑOS ESTABLECIDA

edad=float(input(&#39;introduce el numero de edad que quieres conocer en edad perro: &#39;))

e1= 2

e2= 1

e3= edad \*4-10.5

if edad==e1:

    print(&#39;la conversion en edad perro es: 10.5 en anios humanos:&#39;)

elif edad == e2:

    print(&#39;la conversion en edad perro es: 5.25 en anios humanos:&#39;)

elif edad \&gt; e1:

    print(&#39;la conversion en edad perro es: &#39;,e3)

elif edad \&lt; e2:

    print(&#39;lo siento no se permiten negativos , ingresalo de nuevo&#39;)

3.- Escribe un programa que le permita al usuario ingresar el password de su cuenta y poder confirmarla , en caso de que no se pueda confirmar por error del usuario deberá imprimir un error

password\_user1 =  input(&#39;Inserte un  nuevo password: &#39;)

password\_user2 =  input(&#39;Confirme su password: &#39;)

if password\_user1 == password\_user2:

    print(&#39;Su password ha sido establecido&#39;)

else:

    print(&#39;Lo sienti, ha introducido mal los datos&#39;)

print(&#39;Gracias!&#39;)

4.- Escriba un programam que permita calcular si se tiene o no delgadez u obesidad dependiendo de datos y una tabla especifica como la masa y su altura

# Calculo del indice de masa corporal

masa = float(input(&#39;Introduce tu peso en kg: &#39;))

altura = float(input(&#39;Introduce tu altura en metros: &#39;))

imc = masa/altura\*\*2

if imc \&lt; 16:

    print(&#39;Tienes delgadez severa&#39;)

elif imc \&gt;= 16 and imc \&lt; 17 :

   print(&#39;Tienes delgadez moderada&#39;)

elif imc \&gt;= 17 and imc \&lt; 18.5 :

   print(&#39;Tienes delgadez leve&#39;)

elif imc \&gt;= 18.5 and imc \&lt; 25 :

   print(&#39;Tienes el IMC correcto&#39;)

elif imc \&gt;= 25 and imc \&lt; 30 :

   print(&#39;Tienes obecidad&#39;)

elif imc \&gt;= 30 and imc \&lt; 35 :

   print(&#39;Tienes obecidad leve&#39;)

elif imc \&gt;= 35 and imc \&lt; 40 :

   print(&#39;Tienes obecidad morbida&#39;)

else:

   print(&#39;Favor de introducir datos correctos&#39;)

print(&#39;Gracias!&#39;)

5.- Escriba un programa que permita saber el signo zodiacal que eres dependiendo del dia y del mes en que halla nacido la persona

dia = int (input (&#39;Ingresa el dia en que naciste: &#39;))

mes = int (input (&#39;Ingresa el mes en que naciste: &#39;))

if (dia\&gt;=21 and mes==3) or (dia\&lt;=20 and mes==4):

    print (&#39;Aries&#39;)

if (dia\&gt;=24 and mes==9) or (dia\&lt;=23 and mes==10):

    print (&#39;Libra&#39;)

if (dia\&gt;=21 and mes==4) or (dia\&lt;=21 and mes==5):

    print (&#39;Tauro&#39;)

if (dia\&gt;=24 and mes==10) or (dia\&lt;=22 and mes==11):

    print (&#39;Escorpio&#39;)

if (dia\&gt;=22 and mes==5) or (dia\&lt;=21 and mes==6):

    print (&#39;geminis&#39;)

if (dia\&gt;=23 and mes==11) or (dia\&lt;=21 and mes==12):

    print (&#39;Sagitario&#39;)

if (dia\&gt;=21 and mes==6) or (dia\&lt;=23 and mes==7):

    print (&#39;cancer&#39;)

if (dia\&gt;=22 and mes==12) or (dia\&lt;=20 and mes==1):

    print (&#39;Capricornio&#39;)

if (dia\&gt;=24 and mes==7) or (dia\&lt;=23 and mes==8):

    print (&#39;Leo&#39;)

if (dia\&gt;=21 and mes==1) or (dia\&lt;=19 and mes==2):

    print (&#39;Acuario&#39;)

if (dia\&gt;=24 and mes==8) or (dia\&lt;=23 and mes==9):

    print (&#39;Virgo&#39;)

if (dia\&gt;=20 and mes==2) or (dia\&lt;=20 and mes==3):

    print (&#39;Piscis&#39;)

print ()

**CICLO FOR**

En general, un bucle es una estructura de control que repite un bloque de instrucciones.

Un bucle for es un bucle que repite el bloque de instrucciones un número prederminado de veces. El bloque de instrucciones que se repite se suele llamar cuerpo del bucle y cada repetición se suele llamar iteración.

Si la lista está vacía, el bucle no se ejecuta ninguna vez.

Si la variable de control no se va a utilizar en el cuerpo del bucle, como en los ejemplos anteriores, se puede utilizar el guion (\_) en vez de un nombre de variable. Esta notación no tiene ninguna consecuencia con respecto al funcionamiento del programa, pero sirve de ayuda a la persona que esté leyendo el código fuente, que sabe así que los valores no se van a utilizar.

EJEMPLOS:

1.-

for precio in range (4,5,199):

    descuento= precio \* 60 /100 + 0.95

    print(precio,&#39;|&#39;,descuento)

2.-

print(&quot;Comienzo&quot;)

for i in [0, 1, 2]:

    print(&quot;Hola &quot;, end=&quot;&quot;)

print()

print(&quot;Final&quot;)

**MODULO WHILE:**

En Python tenemos una palabra reservada llamada &quot; **while**&quot; que nos permite ejecutar ciclos, o bien secuencias periódicas que nos permiten ejecutar codigo múltiples veces.

El ciclo while nos permite realizar multiples iteraciones basandonos en el resultado de una expresión logica que puede tener como resultado un valor verdadero o falso (true o false).

Para utilizar este ciclo tenemos la siguiente sintaxis.

EJEMPLO:

1.- Escriba un programa en el que determine una contraseña y el usuario al ingresarla correctamente le aparezca un mensaje de bienvenida , de lo contrario le vuelva a pedir la contraseña

llave= &#39;tesh123&#39;

while True:

    pasword= input(&#39;ingrese la contraseña&#39;)

    if pasword==llave:

        print(&#39;felicidades entraste al sistema&#39;)

        break

    else:

        print(&#39;pasword incorrecto men&#39;)

        print(&#39;favor de intertar de nuevo&#39;)

**MODULO TURTLE:**

En 1967 Wally Feurzeig y Seymour Papert crearon Logo, un lenguaje de programación con fines educativos. Ese lenguaje incluía las llamadas &quot;gráficas tortuga&quot;.

La &quot;tortuga&quot; de Logo es un cursor al que se le pueden dar órdenes de movimiento (avance, retroceso o giro) y que puede ir dejando un rastro sobre la pantalla. Moviendo adecuadamente la tortuga se pueden conseguir dibujar todo tipo de figuras.

Python incluye un módulo llamado &quot;turtle&quot; que permite crear gráficos de tortuga.

En esta lección se explica cómo utilizar el módulo turtle para crear dibujos sencillos, pero sin utilizar la tortuga.

Para utilizar el módulo turtle sólo hace falta importarlo:

Si se va a escribir código no orientado a objetos:

from turtle import \*

Si se va a escribir código orientado a objetos:

import turtle

El módulo turtle dibuja en una ventana distinta a la ventana de IDLE. Esta ventana de dibujo se crea al ejecutar un programa y se mantiene al acabar la ejecución del programa, pero se destruye al volver a ejecutar el programa).

La función **setup(ancho, alto, posicionX, posicionY)** permite definir el tamaño y la posición inicial de la ventana. Los cuatro argumentos de la función son (en píxeles):

- ancho: ancho de la ventana.
- alto: alto de la ventana.
- posicionX: posición horizontal de la ventana. Los valores positivos se miden desde el borde izquierdo de la pantalla, los negativos desde el borde derecho de la pantalla.
- posicionY: posición vertical de la ventana. Los valores positivos se miden desde el borde superior de la pantalla, los negativos desde el borde inferior de la pantalla.

## **El área de dibujo: screensize()**

La ventana de dibujo contiene el área de dibujo, una superficie plana en la que se puede dibujar.

El área de dibujo tiene un tamaño inicial de 400 x 300 píxeles (en Windows), pero la función **screensize(ancho, alto)** permite definir el tamaño del área de dibujo, en píxeles.

El área de dibujo puede ser mayor o menor que la ventana de dibujo.

- Si la ventana es más grande que el área de dibujo, no se muestran barras de desplazamiento:

### Mover el lápiz: goto(), setx() y sety()

Los píxeles del área de dibujo se pueden localizar mediante un sistema de coordenadas XY centrado en el centro del área de dibujo. Al crear la ventana, el cursor se sitúa en el centro de la ventana, de coordenadas (0, 0).

La función **goto(x, y)** permite desplazar el cursor a una posición determinada del área de dibujo. En el ejemplo siguiente el cursor se muestra en la posición (0, 0) (el centro de la ventana):

### Levantar y bajar el lápiz: penup() y pendown()

Las funciones **pendown()** y **penup()** son equivalentes a bajar y levantar el lápiz del papel. Una vez levantado el lápiz del papel, al desplazar el lápiz ya no se dibujan segmentos. Al volver a bajar el lápiz, al desplazar el lápiz vuelven a dibujarse los fragmentos.

### Color del trazo: pencolor() y colormode()

La función **pencolor(rojo, azul, verde)** permite modificar el color del trazo. El color se da como combinación de rojo, azul y verde. Los valores de color se pueden dar como valores enteros entre 0 y 255 o como valores decimales entre 0 y 1. Para elegir entre un modo y otro de indicar los colores hay que utilizar la función **colormode(1)** o **colormode(255)**.

EJEMPLOS:

1.- Escriba un programa el cual reproduzca la tortuga en una distancia especifica y regrese

import turtle

ti=turtle.Screen()

t = turtle.Turtle()

side = 0

for i in range(100):

   t.forward(side)

   t.right(90)

   side = side + 2

ti.mainloop()

3.-

import turtle

window= turtle.Screen()

window.addshape(&#39;nicolas.gif&#39;)

border= turtle.Turtle()

border.speed(0)

border.up()

border.hideturtle()

border.pensize(5)

border.color(&#39;white&#39;)

border.goto(300,300)

border.down()

border.goto(300,-300)

border.goto(-300,-300)

border.goto(-300,300)

border.goto(300,300)

gato=turtle.Turtle()

gato.speed(1)

gato.shape(&#39;nicolas.gif&#39;)

gato.up()

dx=1

while True:

    x,y= gato.position()

    if x+dx\&gt;=300 or x+dx\&lt;=-300:

        dx=-dx

    gato.goto(x+dx,y)

window.mainloop()

4.-

import turtle

ventana= turtle.Screen()

ventana.setup(500,500)

ventana.tracer(0)

ventana.addshape(&quot;gato.gif&quot;)

gato = turtle.Turtle()

gato.speed(0)

gato.shape(&quot;gato.gif&quot;)

gato.penup()

gato.goto(-350, 0)

while True :

    ventana.update()

    gato.forward(0.01)

5.-

import turtle

window= turtle.Screen()

window.addshape(&#39;nicolas.gif&#39;)

window.bgcolor(&#39;lightblue&#39;)

border= turtle.Turtle()

border.speed(0)

border.up()

border.hideturtle()

border.pensize(5)

border.color(&#39;white&#39;)

border.goto(300,300)

border.down()

border.goto(300,-300)

border.goto(-300,-300)

border.goto(-300,300)

border.goto(300,300)

sc = turtle.Screen()

sc.reset()

sc.setworldcoordinates(0,-1.5,360,1.5)

for angle in range(360):

    y = math.sin(math.radians(angle))

    fred.goto(angle,y)

wn.exitonclick()

gato=turtle.Turtle()

gato.speed(1)

gato.shape(&#39;nicolas.gif&#39;)

gato.up()

dx=1

while True:

    x,y= gato.position()

    if x+dx\&gt;=300 or x+dx\&lt;=-300:

        dx=-dx

    gato.goto(x+dx,y)

window.mainloop()

6.- Este programa lo que hará es dibujar un pentagono siguiendo la dirección

import turtle

def dibujar\_poligono(tur , d):

    for i in range(8):

        tur.forward(d)

        tur.left(45)

ventana = turtle.Screen()

ventana.bgcolor(&#39;white&#39;)

ventana.title(&#39;funciones&#39;)

hush = turtle.Turtle()

hush.speed(1)

dibujar\_poligono(hush, 50)

ventana.mainloop

7.-

import turtle

def spiral(t,side):

  for i in range(2):

    #t.speed(0)

    t.forward(side)

    t.left(89)

    spiral(t,side+10)

t=turtle.Turtle()

8.-

import turtle

ventana= turtle.Screen()

ventana.setup(50,60)

ventana.tracer(0)

ventana.addshape(&quot;gato.gif&quot;)

gato = turtle.Turtle()

gato.speed(100)

gato.shape(&quot;gato.gif&quot;)

x=50

y= 60

x,y=gato.pos()

gato.penup()

gato.goto(50,60)

while True :

    ventana.update()

    gato.forward(0.01)

9.-

import turtle

ventana= turtle.Screen()

ventana.setup(500,500)

ventana.tracer(1)

ventana.addshape(&quot;gato.gif&quot;)

gato = turtle.Turtle()

gato.speed(1)

gato.shape(&quot;gato.gif&quot;)

gato.position()

(-1.05,0.75)

gato.forward(300)

gato.position(800.00,0.00)

gato.forward(-100)

gato.position(-600.00,0.00)

gato.penup()

gato.goto(0,1)

while True :

    ventana.update()

    ventana.mainloop()

10.-

import turtle

ventana= turtle.Screen()

ventana.tracer(1)

ventana.addshape(&quot;gato.gif&quot;)

gato = turtle.Turtle()

gato.speed(1)

gato.shape(&quot;gato.gif&quot;)

gato.position()

(-1.05,0.75)

gato.forward(300)

while True :

    ventana.update()

    ventana.mainloop()

11.-

import turtle

window= turtle.Screen()

window.addshape(&#39;nicolas.gif&#39;)

border= turtle.Turtle()

border.speed(0)

border.up()

border.hideturtle()

border.pensize(5)

border.color(&#39;white&#39;)

border.goto(300,300)

border.down()

border.goto(300,-300)

border.goto(-300,-300)

border.goto(-300,300)

border.goto(300,300)

border.setworldcoordinates(0,-1.5,360,1.5)

gato=turtle.Turtle()

gato.speed(1)

gato.shape(&#39;nicolas.gif&#39;)

gato.reset()

for angle in range(360):

    y = math.sin(math.radians(angle))

    border.goto(angle,y)

gato.up()

dx=1

while True:

    x,y= gato.position()

    if x+dx\&gt;=300 or x+dx\&lt;=-300:

        dx=-dx

    gato.goto(x+dx,y)

window.mainloop()

12.-

import turtle

def drawSquare(t,side):

  for i in range(4):

      t.forward(side)

      t.left(90)

ventana = turtle.Screen()

ventana.bgcolor(&quot;light green&quot;)

hush = turtle.Turtle()

hush.fillcolor(&quot;red&quot;)

hush.speed(5)

m = -10

for s in range(20, 101,20):

  drawSquare(hush,s)

  hush.penup()

  hush.goto(m,m)

  hush.pendown()

  m = m -10

ventana.mainloop()

13.-

import turtle

def draw\_square(some\_turtle):

    for i in range(0,4):

        some\_turtle.forward(100)

        some\_turtle.right(90)

def draw\_art():

    ventana = turtle.Screen()

    ventana.bgcolor(&quot;red&quot;)

    hush = turtle.Turtle()

    hush.shape(&quot;turtle&quot;)

    hush.color(&quot;yellow&quot;)

    hush.speed(6)

    for i in range (0, 36):

        draw\_square(hush)

        hush.right(10)

draw\_art()

14.-

import turtle

wn = turtle.Screen()

wn.bgcolor(&#39;lightgreen&#39;)

hush = turtle.Turtle()

hush.pensize(2)

hush.color(&#39;blue&#39;)

def first\_two\_line(size):

    hush.right(180)

    hush.forward(size)

    hush.right(90)

    hush.forward(size)

def draw():

    size = 10

    first\_two\_line(size)

    for i in range(40):

        size += 5

        hush.right(90)

        hush.forward(size)

        hush.right(90)

        hush.forward(size)

draw()

wn.mainloop()

15.-

import turtle

wn = turtle.Screen()

wn.bgcolor(&#39;lightgreen&#39;)

hush = turtle.Turtle()

hush.pensize(2)

hush.color(&#39;blue&#39;)

def first\_two\_line(size):

    hush.right(180)

    hush.forward(size)

    hush.right(90)

    hush.forward(size)

def draw():

    size = 10

    first\_two\_line(size)

    for i in range(40):

        size += 5

        hush.right(89)

        hush.forward(size)

        hush.right(89)

        hush.forward(size)

draw()

wn.mainloop()

16.-

import turtle

import math

window= turtle.Screen()

window.addshape(&#39;nicolas.gif&#39;)

window.setworldcoordinates(0,-1,1000,1)

border= turtle.Turtle()

border.speed(0)

border.up()

border.hideturtle()

border.pensize(5)

border.color(&#39;white&#39;)

border.goto(300,300)

border.down()

border.goto(300,-300)

border.goto(-300,-300)

border.goto(-300,300)

border.goto(300,300)

gato=turtle.Turtle()

gato.speed(1)

gato.shape(&#39;nicolas.gif&#39;)

gato.up()

dx=1

while True:

    x,y= gato.position()

    y=math.sin(math.radians(x))

    if x+dx\&gt;=300 or x+dx\&lt;=-300:

        dx=-dx

    gato.goto(x+dx,y)

window.mainloop()

**PROGRAMACION ORIENTADA A OBJETOS:**

La programación orientada a objetos (POO, u OOP según sus siglas en inglés) es un paradigma de programación que viene a innovar la forma de obtener resultados. Los objetos manipulan los datos de entrada para la obtención de datos de salida específicos, donde cada objeto ofrece una funcionalidad especial.

Muchos de los objetos prediseñados de los lenguajes de programación actuales permiten la agrupación en bibliotecas o librerías, sin embargo, muchos de estos lenguajes permiten al usuario la creación de sus propias bibliotecas.

Los _objetos_ son abstracción de Python para data. Toda la data en un programa Python es representado por objectos o por relaciones entre objectos. (En cierto sentido, y en el código modelo de Von Neumann de una &quot;computadora almacenada del programa&quot; también es un código representado por los objetos.)

Cada objeto tiene una identidad, un tipo y un valor. Una identidad de objecto nunca cambia una vez es creada; usted puede pensar eso como la dirección de objeto en memoria. El operador [_in_](https://entrenamiento-python-basico.readthedocs.io/es/latest/leccion4/condicional_if.html#python-opers-in)compara la identidad de dos objetos; la función [_id()_](https://entrenamiento-python-basico.readthedocs.io/es/latest/leccion5/funciones_integradas.html#python-fun-id) devuelve un número entero representando la identidad (actualmente implementado como su dirección).

El _tipo_ de un objeto también es inmutable. El tipo de un objeto determina las operaciones que admite el objeto (por ejemplo, &quot;¿tiene una longitud?&quot;) Y también define los valores posibles para los objetos de ese tipo. La función &quot;[_type()_](https://entrenamiento-python-basico.readthedocs.io/es/latest/leccion5/funciones_integradas.html#python-fun-type)&quot; devuelve el tipo de un objeto (que es un objeto en sí mismo). El _valor \*de algunos objetos puede cambiar. Se dice que los objetos cuyo valor puede cambiar son \*mutables_; los objetos cuyo valor no se puede cambiar una vez que se crean se llaman _immutable_. (El valor de un objeto contenedor inmutable que contiene una referencia a un objeto mutable puede cambiar cuando se cambia el valor de este último; sin embargo, el contenedor todavía se considera inmutable, porque la colección de objetos que contiene no se puede cambiar. Por lo tanto, la inmutabilidad no es estrictamente lo mismo que tener un valor incambiable, es más sutil.) La mutabilidad de un objeto está determinada por su tipo; por ejemplo, los números, las cadenas y las tuplas son inmutables, mientras que los diccionarios y las listas son mutables.

## Atributos

Los atributos o propiedades de los objetos son las características que puede tener un objeto, como el color. Si el objeto es Persona, los atributos podrían ser: cedula, nombre, apellido, sexo, etc...

Los atributos describen el estado de un objeto. Pueden ser de cualquier tipo de dato.

## Métodos

Los métodos describen el comportamiento de los objetos de una clase. Estos representan las operaciones que se pueden realizar con los objetos de la clase,

La ejecución de un método puede conducir a cambiar el estado del objeto.

Se definen de la misma forma que las funciones normales pero deben declararse dentro de la clase y su primer argumento siempre referencia a la instancia que la llama, de esta forma se afirma que los métodos son [_funciones_](https://entrenamiento-python-basico.readthedocs.io/es/latest/leccion5/funciones.html#python-funciones), adjuntadas a [_objectos_](https://entrenamiento-python-basico.readthedocs.io/es/latest/leccion9/poo.html#python-objetos).

EJEMPLOS:

1.- Crear una clase llamada canción la cual interpretara un fragmento de la letra cuando el usuario lo pida

class cancion(object):

    def \_init\_(self,letra):

        self.letra=letra

    def feliz\_cumple(self):

        if self.letra:

            print(&#39;estas son lasmañanitas que cantaba el rey david, hoy por ser dia de tu santo de las cantamos a aqui&#39;)

3.- Crear una clase llamada coche la cual tendrá como atributo la gasolina lo cual ayudara a determinar la cantidad de gasolina restante cada que el coche avance

class Coche(object):

    def \_\_init\_\_(self,gasolina):

        self.gasolina = gasolina

    def arrancar(self):

        if self.gasolina \&gt; 0:

            print(&#39;encendido&#39;)

        else:

            print(&#39;no encendido&#39;)

    def conducir(self):

        if self.gasolina \&gt; 0:

            self.gasolina = self.gasolina - 1

            print(&#39;quedan&#39; , self.gasolina, &#39;litros&#39;)

        else:

            print(&#39;no se mueve&#39;)

#creacion de objetos

vocho = Coche(5)

tsuru = Coche(3)

vocho.arrancar()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

vocho.conducir()

5.-

class triangulo:

    def \_\_init\_\_(self,angulo1,angulo2,angulo3):

        self.angulo1 = angulo1

        self.angulo2 = angulo2

        self.angulo3 = angulo3

    def checar\_angulos(self):

        if self.angulo1 + self.angulo2 + self.angulo3== 180:

           print(&#39;es verdadero&#39;)

        else:

           print(&#39;es falso&#39;)

mitriangulo = triangulo(90,30,60)

mitriangulo.checar\_angulos()

ESTO ES LO QUE TUVIMOS EL PRIVILEGIO DE APRENDER DURANTE EL CURSO DE PROGRAMACION BASICA EN EL TECNOLOGICO DE ESTUDIOS SUPERIORES DE HUIXQUILUCAN
