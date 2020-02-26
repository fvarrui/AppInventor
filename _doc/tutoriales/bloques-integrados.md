---
layout: tutorial
title: Bloques integrados (built-in blocks)
sections:
  - Bloques de control
  - Bloques de lógica
  - Bloques de matemáticas
  - Bloques de texto
  - Bloques de listas
  - Bloques de colores
  - Bloques de variables
  - Bloques de procedimientos
---

En [App Inventor](http://ai2.appinventor.mit.edu/) existen unos bloques integrados que son comunes a todos los proyectos, independientemente de los componentes que estos contengan.

[![Bloques integrados](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/bloques_integrados.png)](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/bloques_integrados.png)

## Bloques de Control

### si ... entonces

![control01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-10.27.11.png)

El bloque `si … entonces` prueba una condición dada. Si la condición es verdadera, realiza las acciones en una determinada secuencia de bloques; de lo contrario, los bloques son ignorados. 

El segundo bloque, `si … entonces … si no`, prueba una condición dada. Si el resultado es verdadero, realiza las acciones de la secuencia de bloques -entonces; de lo contrario, realiza las acciones en la secuencia de bloques `si no`. 

El tercero, `si … entonces … si no, si … entonces`, prueba una condición dada. Si el resultado es verdadero, realiza las acciones en la secuencia de bloques `entonces`; de otro modo prueba la segunda condición `si no, si`. Si el resultado es verdadero, realiza las acciones en la secuencia de bloques `entonces`; de lo contrario, pasa al siguiente bloque. Todos ellos y alguna otra combinación se construye a partir del primer bloque, desde el botón azul de la esquina superior izquierda del mismo.

### por cada (variable) desde

![control02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-10.27.41.png)

Ejecuta los bloques que engloba para cada valor numérico en el rango a partir del valor `desde` y termina en `hasta`, incrementando el número por el valor determinado. Se puede cambiar el nombre de la variable por otro si se desea. La variable `número` irá cogiendo valores entre `desde` y `hasta` en cada iteración. Esta variable se podrá usar sólo dentro del bloque.

### por cada (elemento) en la lista

![control03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.02.png)

Ejecuta los bloques para cada elemento de una lista. La variable `elemento` contendrá un elemento de la lista en cada iteración.

### mientras comprobar

![control04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.14.png)

Se ejecuta el conjunto de bloques mientras el valor a comprobar sea cierto.

### si ... entonces ... sino

![control05](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.20.png)

Prueba una condición dada. Si la afirmación es cierta, realiza las acciones en la secuencia entonces y devuelve ese valor al origen; de lo contrario, lleva a cabo las acciones del si no y devolverá el valor que de.

### ejecutar ... resultado

![control06](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.25.png)

Realiza las acciones definidas en ejecutar y devuelve una sentencia o resultado. Útil cuando se requiere ejecutar un procedimiento antes de devolver un valor a una variable.

### evaluar pero ignorar el resultado

![control07](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.31.png)

Ejecuta el bloque de código conectado pero ignora el valor devuelto.

### abrir otra pantalla

![control08](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.41.png)

Abre otra pantalla con el nombre proporcionado.

### abre otra pantalla con un valor inicial

![control09](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.05.56.png)

Se abre otra pantalla y pasa un valor a la misma.

### tomar el valor inicial

![control10](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.02.png)

Devuelve el valor inicial dado en la pantalla actual desde la pantalla anterior. Este valor se indica con el uso del bloque anterior, `abre otra pantalla con un valor inicial`.

### cerrar pantalla

![control11](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.07.png)

Cierra la pantalla actual.

### cerrar la pantalla con un valor

![control12](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.11.png)

Cierra la pantalla actual y devuelve un valor a la pantalla anterior.

### cerrar la aplicación

![control13](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.16.png)

Cierra la aplicación.

### tomar el texto inicial

![control14](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.24.png)

Devuelve el texto sin formato que se pasó a esta pantalla cuando ésta se inició por otra aplicación. Si no se pasa ningún valor, devuelve el texto vacío. Para aplicaciones con múltiples pantallas es mejor utilizar el bloque tomar el valor inicial.

### cerrar pantalla con texto

![control15](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-28-at-15.06.33.png)

Cierra la pantalla actual y pasa el texto a la aplicación que abrió éste. Este comando es para devolver texto a actividades que no son de App Inventor, no para las pantallas de App Inventor. Para las pantallas de App Inventor, como para aplicaciones con múltiples pantallas, utiliza el bloque cerrar la pantalla con un valor resultado.

## Bloques de Lógica {#bloques-de-logica}

### cierto / falso

![logica01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-08.36.13.png)

Representa el valor constante verdadero. Se utiliza para establecer valores de propiedades booleanas de los componentes, o como el valor de una variable que representa una condición. `falso` Igual que el anterior pero valor falso o no verdadero.Se puede alternar entre cierto y falso mediante la flecha que apunta hacia abajo.

### no

![logica02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-08.36.31.png)

Realiza negación lógica, devolviendo falso si la entrada es un valor cierto, y verdadero si la entrada es falso.

### =

![logica02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-09.03.44.png)

Comprueba si los argumentos son iguales. Este bloque permite cambiar también por el valor desigual.

### y / o

![logica04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-08.36.41.png)

El bloque `y` devuelve cierto si todos los valores lo son.

El bloque `o` comprueba si cualquiera de las dos condiciones son verdaderas.

## Bloques de Matemáticas {#bloques-de-matematicas}

### 0

![mates01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-10.51.43.png)

Se puede utilizar como cualquier número positivo o negativo (decimales incluidos). Haciendo doble clic en el "0" del bloque le permitirá cambiar el número.

### = / ≠ / > / ≥ / < / ≤

![mates02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/mates02.gif)

Compara dos valores y devuelve si es verdadero o falso.

### +

![mates03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.25.34.png)

Devuelve el resultado de la suma de bloques que tienen un valor numérico. 

Este bloque puede mutar ampliándose para permitir más números en la suma.

![suma](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/suma.gif)

### -

![mates04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.29.26.png)

Devuelve el resultado de restar el segundo número del primero.

### *

![mates05](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.29.32.png)

Como el de la suma con mutador, pero con la operación de multiplicación.

### /

![mates06](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.32.08.png)

Devuelve el resultado de dividir el primer número por el segundo.

### ^

![mates07](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.32.15.png)

Devuelve el resultado elevar el primer número a la potencia indicada en el segundo.

### entero aleatorio

![mates08](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.32.25.png)

Devuelve un valor entero aleatorio entre los valores dados, ambos inclusive. El orden de los argumentos no importa. En la imagen anterior, el bloque devuelve un entero aleatorio entre 1 y 100, ambos inclusive.

### decimal aleatorio

![mates09](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.32.30.png)

Devuelve un número decimal aleatorio entre 0 y 1, ambos inclusive.

### semilla aleatoria

![mates10](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-12.32.36.png)

Este bloque establece la semilla de generación de números aleatorios. Una misma semilla genera la misma secuencia de números aleatorios (o pseudo-aleatorios). 

### min / max

![mates11](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/minmax.gif)

`min` devuelve el valor mínimo de un conjunto de números.

`max` es igual pero el valor máximo.

### raíz cuadrada

![mates12](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.26.png)

Devuelve la raíz cuadrada del número dado.

### valor absoluto

![mates13](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.30.png)

Devuelve el valor absoluto del número dado.

### neg

![mates14](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.35.png)

Devuelve el negativo de un número dado.

### log

![mates](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.46.56.png)

Devuelve el logaritmo natural de un número dado, es decir, el logaritmo en base **e** (2,71828 …).

### e^

![Screenshot 2016-01-29 at 13.47.03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.47.03.png)

Devuelve **e** (2,71828 …) elevado a la potencia del número dado.

### redondear

![mates15](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.39.png)

Devuelve el número dado redondeado al entero más cercano. Si la parte fraccionaria es < 0,5 se redondeará hacia abajo. Si es > 0,5 se redondeará hacia arriba. Si es exactamente igual a 0.5, números con una parte aún entera se redondean hacia abajo, y los números con una parte entera impar se redondearán hacia arriba.

### superior / inferior

![Screenshot 2016-01-29 at 13.12.44](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.44.png)

`superior` devuelve el número entero más pequeño que es mayor que o igual al número dado.

`inferior` devuelve el mayor entero que es menor o igual al número dado.

### modulo

![Screenshot 2016-01-29 at 13.12.48](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.12.48.png)

Devuelve el resto de la división entera de dos números. Por ejemplo, el módulo (11, 5) = 1, módulo (-11, 5) = 4, módulo (11, -5) = -4, módulo (-11, -5) = -1. Modulo (a, b) siempre tiene el mismo signo que b, mientras que resto (a, b) siempre tiene el mismo signo que a. Puede mutar también como *resto de* y *cociente de*.

### sen / cos / tan / asen / acos / atan

![Screenshot 2016-01-29 at 13.56.57](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.56.57.png)

Devuelve el seno, coseno, tangente, arco-seno, arco-coseno y arco-tangente respectivamente del número en grados.

### atan2

![Screenshot 2016-01-29 at 13.57.15](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.57.15.png)

Devuelve el arco tangente de y / x.

### convertir rad a gra / convertir gra a rad

![Screenshot 2016-01-29 at 13.57.20](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.57.20.png)

`convertir radiantes a grados` devuelve el valor en grados del número dado en radianes. El resultado será un ángulo en el rango [0, 360).

`convertir grados a radiantes` convierte grados a radianes. El resultado será un ángulo en el intervalo [-π, π +)

### dar formato decimal al número

![Screenshot 2016-01-29 at 13.57.24](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.57.24.png)

Formatea un número a un decimal con un número dado de posiciones después del punto decimal. El número de plazas debe ser un número entero no negativo. El resultado se realiza mediante el redondeo del número o añadiendo ceros a la derecha.

### ¿es un número?

![Screenshot 2016-01-29 at 13.57.29](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.57.29.png)

Devuelve verdadero si el objeto dado es un número, y falso en caso contrario.Este bloque se puede cambiar por *¿es base 10?, ¿es hexadecimal?* y *¿es binario?*.

### convert number

![Screenshot 2016-01-29 at 13.57.33](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-01-29-at-13.57.33.png)

Bloque sin traducir que toma una cadena de texto que representa un número entero positivo en una base y devuelve una cadena que representa el mismo número en otra base. 

## Bloques de Texto

### " "

![texto01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.52.36.png)

Contiene una cadena de texto. Esta cadena puede contener caracteres (letras, números u otros caracteres especiales). En App Inventor se considerará un objeto de texto.

### unir

![texto02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.52.40.png)

Concatena todas las entradas para hacer una sola cadena. Si no hay entradas, devuelve una cadena vacía.

### longitud

![texto03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.52.45.png)

Devuelve el número de caracteres, incluidos los espacios en la cadena. Esta es la longitud de la cadena de texto dada.

### está vacío

![texto04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.52.50.png)

Devuelve si la cadena contiene caracteres (incluyendo espacios) o no. Cuando la longitud de la cadena es 0, devuelve verdadero de lo contrario, devuelve falso.

### comparar textos

![texto05](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.52.55.png)

Compara si la primera cadena es lexicográficamente **<**, **>** o **=** a la segunda.

### recortar

![texto06](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.00.png)

Elimina todos los espacios iniciales o finales de la cadena de entrada y devuelve el resultado.

### mayúsculas / minúsculas

![texto07](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.05.png)

Devuelve una copia de la cadena de texto pasada como argumento en mayúscula o en minúscula.

### comienzo en el texto

![texto08](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.09.png)

Devuelve la posición en el que aparece por primera vez la cadena en el texto, o cero si no está presente. Por ejemplo, la cadena *ico* en el texto *Perico* es 4.

### contiene texto

![texto09](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.14.png)

Devuelve verdadero si el *texto* aparece en la *cadena*; de lo contrario, devuelve falso.

### recorta texto

![texto10](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.19.png)

Divide el texto en partes utilizando el texto **en** como punto de corte y genera una lista con los resultados.

### divide por espacios

![texto11](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.23.png)

Divide el texto dado en partes separadas por espacios (pueden ser tanto espacios en blanco, como tabulados o saltos de línea).

### segmento de texto

![texto12](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.27.png)

Extrae parte del texto a partir de la posición inicial y la longitud de los caracteres.

### sustituye en todo el texto

![texto13](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.32.png)

Devuelve un texto nuevo resultado de sustituir todas las ocurrencias del segmento por su sustituto.

### Obsfuscated Text

![texto14](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-10.53.37.png)

Produce texto, como un bloque de texto simple. La diferencia es que este se oculta en el archivo APK generado.

## Bloques de Listas

### `crear una lista vacía`

![listas01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.45.52.png)

Crea una lista sin elementos.

### `construye una lista`

![listas02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.45.57.png)

Crea una lista con un número de elementos dados. Si no se proporciona ningún argumento se crea una lista vacía. Este bloque es un mutador. Al hacer clic en el icono azul se permite añadir elementos adicionales a la lista.

### `añadir elementos a la lista`

![listas03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.01.png)

Añade elementos al final de una lista.

### `¿Está en la lista?`

![listas04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.07.png)

Si **cosa** es uno de los elementos de la **lista**, devuelve verdadero; de lo contrario falso. Conviene tener en cuenta que si una lista contiene sublistas, los miembros de las sublistas no son miembros de la lista.

### `longitud de a lista`

![listas05](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.11.png)

Devuelve el número de elementos de la lista.

### `¿está vacía la lista? `

![listas06](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.17.png)

Si la lista no tiene elementos, devuelve verdadero; de lo contrario devuelve falso.

### `toma un elemento al azar`

![listas07](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.22.png)

Devuelve un elemento de la lista al azar.

### `índice en la lista`

![listas08](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.29.png)

Devuelve la posición de la *cosa* en la lista. Si no está en la lista, devuelve 0.

### `seleccionar elemento de la lista`

![listas09](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.34.png)

Selecciona el elemento en el índice que figura en la lista dada. El primer elemento de la lista está en el índice 1.

### `insertar elemento en la lista`

![listas10](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.38.png)

Inserta un elemento en la lista en la posición dada.

### `sustituye elemento de la lista`

![listas11](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.43.png)

Inserta **sustituto** en la lista dada en el **índice** de posición. Se elimina el elemento anterior de esa posición.

### `eliminar elemento de la lista`

![listas12](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.47.png)

Elimina el elemento de la posición indicada.

### `añadir a la lista`

![listas13](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.52.png)

Añade los elementos de la segunda lista al final de la primera lista.

### `copiar lista`

![listas14](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.46.56.png)

Hace una copia de una lista, incluyendo la copia de todas las sublistas.

### `¿es una lista?`

Si **cosa** es una lista, devuelve verdadero; de lo contrario falso.

### `lista a registro csv`

![listas16](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.47.05.png)

Interpreta la lista como un registro de una tabla y devuelve una cadena de texto en formato CSV (valor separado por comas) que representa al registro.

### `lista a tabla csv`

![listas17](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.47.09.png)

Interpreta la lista como una tabla y devuelve un texto CSV que representa a la tabla.

### `lista desde registro csv`

![listas18](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.47.13.png)

Analiza un texto como un registro en formato CSV para generar una lista de campos.

### `lista desde tabla csv`

![listas19](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.47.18.png)

Analiza un texto como una tabla con formato CSV para producir una lista de registros, cada uno de los cuales es una lista de campos.

### `buscar por parejas`

![listas20](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-13.47.23.png)

Se utiliza para buscar información en una estructura similar a un diccionario representado como una lista. La entrada **parejas** debe ser una lista de listas de parejas (listas de dos elementos, una clave y un valor).

## Bloques de Colores

### `bloques básicos de colores`

![bloques_colores](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/bloques_colores.gif)

Se trata de bloques de distintos colores identificados por el color de en medio. Si hace clic en centro de cualquier color aparece una ventana emergente y se puede cambiar entre una paleta de colores.

### `crear color`

![Screenshot 2016-02-01 at 14.35.48](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.35.48.png)

Permite crear colores RGB. El primer valor es rojo (Red), el segundo verde (Green) y el último azul (Blue). Cada componente del color puede tomar una valor entre 0 y 255, ambos inclusive.

### `separar color`

![Screenshot 2016-02-01 at 14.35.52](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.35.52.png)

Al revés que el bloque anterior. Devuelve el código RGB.

## Bloques de Variables

### `inicializar global ... como`

![variables01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.45.37.png)

Este bloque se utiliza para crear variables globales y asignarle el valor de los bloques encajados. Se puede cambiar el **nombre** de esta variable global. Las variables gobales se pueden leer desde cualquier conjunto de bloques de la pantalla.

### `tomar ...`

![variables02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.45.42.png)

Este bloque proporciona una manera de conseguir cualquier variable que se haya creado. En la lista desplegable podemos elegir la variable de la que se quiere obtener el valor.

### `poner ... a`

![variables03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.45.46.png)

Asigna a esta variable el valor especificado como entrada.

### `inicializar local ... como`

![variables04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.45.50.png)

Permite crear variables que solamente son accesibles en la parte ejecutar de este bloque.

## Bloques de Procedimientos

### `como procedimiento ... ejecutar`



![procedimientos01](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.56.55.png)

Agrupa una secuencia de bloques juntos. Luego se podrá utilizar la secuencia de bloques establecida mediante una llamada al procedimiento. Si el procedimiento tiene argumentos, especifique los argumentos con el botón mutador del bloque. Si haces clic en el icono azul, podemos arrastrar argumentos adicionales en el procedimiento.

### `como procedimiento ... resultado`

![procedimientos02](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.57.00.png)

Igual que un el anterior bloque, pero al llamar a este procedimiento se devuelve un resultado.

### `llamar ...`

![procedimientos03](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.57.05.png)

Llama a un procedimiento que no devuelve un valor.

### `llamar ...` 

![procedimientos04](http://codigo21.educacion.navarra.es/wp-content/uploads/2016/01/Screenshot-2016-02-01-at-14.57.09.png)

Hacer una llamada a un procedimiento que devuelve un valor.

## Referencias

* [Descripción de los bloques integrados de App Inventor (Código21)](https://codigo21.educacion.navarra.es/autoaprendizaje/descripcion-de-los-bloques-integrados-de-app-inventor-2/)