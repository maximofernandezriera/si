---
# Title, summary, and page position.
linktitle: Unidad 1
summary: Una picelada sobre sistemas operativos
weight: 1
icon: book-reader
icon_pack: fas

# Page metadata.
title: Los sistemas informáticos y los sistemas operativos
date: "2018-09-09T00:00:00Z"
type: book  # Do not modify.
---

## La informática

* Nace para evitar tareas repetitivas de cálculo y gestión. 

* El término informática apareció en Francia en 1962: 

**INFOR**mation auto**MATIQUE** 

**La informática es la ciencia que estudia el tratamiento  automático y racional de la información** 

* Desarrollo y mejora de **máquinas**
* Desarrollo y mejora de nuevos **sistemas** automáticos de trabajo
* Construcción de **aplicaciones informáticas**

## El sistema binario

* Para los ordenadores todos los datos son números y todo acaban  siendo conjuntos de 0 s y 1 s

* Debido a esto último, el ordenador no utiliza el sistema decimal si  no el **sistema binario**

* El ordenador utiliza mecanismos que traducen los datos a: sistemas numéricos 

* Códigos alfanuméricos

## Medida de la información

* Como en la mayoría de ámbitos, en la informática se utiliza una  unidad base y sus múltiples → **el bit (b**)

### Permiten dos valores: **0** y **1.** 

1. ¿Cuántas combinaciones podemos representar con un único bit? 

1. ¿Cuántas combinaciones tenemos con 2 bits? con 3? con 4? ... 

### La información que da un bit es mínima, por lo tanto hay que buscar  sus múltiples: 

* Conocemos como **byte (B)** los conjuntos de 8 bits.

# Puesta en producción segura

# Tema 1: Prueba de aplicaciones web y para dispositivos móviles

# Índice

Introducción

Objetivos

Fundamentos de programación

Elementos principales de un programa

Pruebas software

Entornos de ejecución

Seguridad de los lenguajes de programación

# Fundamentos de programación

Objetivos

Definir que es un lenguaje de programación así como los distintos tipos de lenguaje\.

Comprender la diferencia entre lenguajes compilados e interpretados\.

Reconocer los elementos básicos de un programa así como entender su significado\.

Conocer los diferentes tipos de prueba existentes en el ciclo de desarrollo\.

Conocer los diferentes riesgos y vulnerabilidades existentes\.

Lenguajes de programación

* Es un conjunto de instrucciones y reglas que forman un lenguaje formal y proporcionan la capacidad de escribir ordenes que controlan el comportamiento de un ordenador\.
* Se descomponen en:
  * Sintaxis: Estructura gramatical del lenguaje\. “Que lo que escribes sea gramaticalmente correcto”\.
  * Semántica: Se refiere al significado del código\. Un programa puede ser sintácticamente correcto pero semánticamente incorrecto\.

Paradigmas de programación

* Es un estilo o filosofía que adoptan los lenguajes de programación para resolver un problema\. Define el lenguaje de programación y como funciona éste\.
* Tipos:
  * Imperativo
  * Declarativo
  * Eventos

Lenguajes compilados e interpretados

* Compilados: Son lenguajes de programación que se traducen normalmente a código máquina para producir el ejecutable del programa\.
* Ventajas:
  * Son más rápidos y eficientes
  * No acceso al código fuente
* Inconvenientes:
  * Necesidad de compilar el programa cada vez que se cambia algo en el código fuente\.
  * Deben ser compilados específicamente para cada plataforma
  * El ciclo de desarrollo es más lento

Lenguajes compilados e interpretados

* Interpretados: Son lenguajes de programación que cuyo código es traducido a lenguaje máquina durante la ejecución dinámica a medida que va siendo leído por el interprete\.
* Ventajas:
  * Multiplataforma
  * El ciclo de desarrollo es más rápido que en los lenguajes compilados\.
  * Sencillo de probar
  * Más flexibles
* Inconvenientes:
  * Se puede obtener el código fuente
  * En general son más lentos y consumen más recursos que los lenguajes compilados
  * Se requiere del interprete para ejecutar el código

Lenguajes compilados e interpretados

Mixtos: Proceso de compilación a un código intermedio que luego es interpretado\.

Java: El código fuente es compilado a un código intermedio conocido comobytecodey este código es ejecutado a través de la máquina virtual de java \(JVM\)\.

\.NET: Similar a java\, su código se compila a un lenguaje intermedio llamado “CIL” que después en tiempo de ejecución es convertido a código nativo\.

Código fuente y entornos de desarrollo

Código fuente: Es el conjunto de instrucciones escritas por los programadores y en un lenguaje que es entendible por los humanos\.

Entornos de desarrollo integrado \(IDE\): Es un software o un marco de trabajo con diferentes utilidades que facilita el proceso de desarrollo a los programadores\.

Código fuente y entornos de desarrollo

* Principales característicasIDEs:
  * Editor/visualizador de código
  * Resaltado de la sintaxis
  * Depurador de código
  * Compilador/Interprete de código
  * Completado de código
  * Soporte para uno o varios lenguajes de programación
* Ejemplos: eclipse\,netbeans\, visualstudio\,pycharm\,phpstorm\, Androidstudio\,etc…\.\.

# Elementos principales de un programa

Introducción apython

* Lenguaje interpretado
* Tipado dinámico
  * La variables asumen el tipo de dato
* Multiplataforma
  * Windows\, Linux\, macOS
* Multiparadigma
  * Orientado a objetos\, imperativa\, funcional

Variables y tipos de datos

Las variables en Python por defecto son locales

Su tipo se asigna de manera automática

Identificador “global” para convertir una variable en global cuando se considera oportuno

Ejemplo				Output:

![](img/Tema%2010.png)

![](img/Tema%2011.png)

Variables y tipos de datos

* Casting de variables: Conversión de un tipo de datos a otro tipo\.
* Ejemplo:
  * >>> var2 = 123
  * >>> var2 = “HOLA”
  * >>>print\(var1 \+ var2\)
* ¿Qué creéis que ocurriría?

Variables y tipos de datos

* Casting de variables: Conversión de un tipo de datos a otro tipo\.
* Ejemplo:
  * var2 = 123
  * var2 = “HOLA”
  * print\(var1 \+ var2\)
* ¿Qué creéis que ocurriría?
* Solución:print\(var1\+str\(var2\)\)

Sentencias de control de flujo

      * __if__ condición:
      * instrucciones
      * __elif__ condición:
      * instrucciones
      * __else__  __:__
      * instrucciones
    * Noswitch

Sentencias de control de flujo \- Condicionales

    * 1\)
    * 2\)
    * ¿Daría una salida correcta? ¿Por qué?

![](img/Tema%2012.png)

![](img/Tema%2013.png)

Sentencias de control de flujo \- Bucles

    * While
    * For
      * 1\)
      * 2\)

![](img/Tema%2014.png)

![](img/Tema%2015.png)

![](img/Tema%2016.png)

Entrada y salida

* Teclado
  * La entrada por teclado se almacena como una cadena de texto\, si queremos un número entero hay que hacer una conversión de tipo \->num=int\(input\(\)\)
* Pantalla

![](img/Tema%2017.png)

![](img/Tema%2018.png)

Entrada y salida

* Ficheros
  * Lectura\.
  * Escritura

![](img/Tema%2019.png)

![](img/Tema%20110.png)

![](img/Tema%20111.png)

Funciones

* Parámetros: Son valores que la función necesita recibir cuando es invocada en cualquier parte del programa\.
* Parámetros por omisión: Definición de una función con parámetros por defecto que serán usados en caso de no ser pasados cuando se invoque a la función\.
* Múltiples parámetros

![](img/Tema%20112.png)

![](img/Tema%20113.png)

Funciones

* Son declaradas a través de al palabra reservada “def”
* Al igual que todas las estructuras de control anteriormente vistas\, la definición finaliza con “:”
* Las instrucciones que formen parte de la función deben encontrarseidentadas\.
    * __def__ mi\_funcion\(\):
    * __print__ \(“Esto forma parte de mi función”\)
    * __print__ \(“Esto ya no forma parte de mi función”\)

Funciones

* Parámetros: Son valores que la función necesita recibir cuando es invocada en cualquier parte del programa\.
* Parámetros por omisión: Definición de una función con parámetros por defecto que serán usados en caso de no ser pasados cuando se invoque a la función\.

![](img/Tema%20114.png)

![](img/Tema%20115.png)

Funciones

* Múltiples parámetros: Permite definir un número desconocido de parámetros\, permitiendo definir un número desconocido de ellos\.
* ¿Qué pasaría si realizamos la llamada ami\_sumacomo “mi\_suma\(\)”?
* ¿Y si la llamada es “mi\_suma\(‘1’\,’2’\,’3’\,’4’\)”?

![](img/Tema%20116.png)

Funciones

* Múltiples parámetros: Permite definir un número desconocido de parámetros\, permitiendo definir un número desconocido de ellos\.
* ¿Qué pasaría si realizamos la llamada ami\_sumacomo “mi\_suma\(\)”?
* ¿Y si la llamada es “mi\_suma\(‘1’\,’2’\,’3’\,’4’\)”?

![](img/Tema%20117.png)

Estructuras de datos

* Listas : Colección simple de datos\.
  * Ejemplo				Output
* ¿Qué resultado se obtendría al acceder ami\_lista\[\-1\] ?

![](img/Tema%20118.png)

![](img/Tema%20119.png)

Estructuras de datos

* Listas : Colección simple de datos\.
  * Ejemplo				Output
* ¿Qué resultado se obtendría al acceder ami\_lista\[\-1\] ?
  * Devolvería el último elemento de la lista\.
  * mi\_lista\[\-2\] el penúltimo y así\.\.
  * Se puede obtener un subconjunto de valores conmi\_lista\[0:4:2\]

![](img/Tema%20120.png)

![](img/Tema%20121.png)

Estructuras de datos

* Tuplas\. Colección simple de datos inmutables\, es decir\, una vez se genera una tupla no puede modificarse el valor de ninguno de sus elementos\.
  * ¿Qué pasa si intentamos modificar un elementomi\_tupla\[2\]= “adios” ?

![](img/Tema%20122.png)

Estructuras de datos

* Tuplas\. Colección simple de datos inmutables\, es decir\, una vez se genera una tupla no puede modificarse el valor de ninguno de sus elementos\.
  * ¿Qué pasa si intentamos modificar un elementomi\_tupla\[2\]= “adios” ?

![](img/Tema%20123.png)

![](img/Tema%20124.png)

Estructuras de datos

* Diccionarios\. Estructura de datos del tipo clave\-valor\. Cada clave es única y a través de ésta se accede a su valor\.
  * Output:

![](img/Tema%20125.png)

![](img/Tema%20126.png)

![](img/Tema%20127.png)

![](img/Tema%20128.png)

Clasesy Objetos

Forma de empaquetar un conjunto de datos y métodos que trabajan sobre esos datos

Un objeto es una instancia de una clase y se pueden crear múltiples objetos sobre una clase\.

Las clases en Python tienen las mismas características que cualquier lenguaje orientado a objetos Herencia\, polimorfismo\, delegación

En Python\, todos los atributos de una clase son públicos\.

Clasesy Objetos

![](img/Tema%20129.png)

Algoritmos

* ¿Qué es un Algoritmo?
  * Conjunto de instrucciones o pasos bien definidos para resolver un problema\.
* Características:
  * Debe ser claro\.
  * Debe tener sus entradas y salidas bien definidas\.
  * Deben ser finitos\.
  * Deben ser independientes de cualquier código de programación\.

Módulos

* Son los ficheros que contienen las distintas definiciones de datos\, funciones\, clases\, etc\.
* Cualquier fichero de Python puede ser importado en otro y utilizar los datos de ese modulo\.
* Se realiza mediante la directiva “import”\.
  * Ejemplo: __import__  __json__
* Existen un gran numero de módulos ya implementados en Python que pueden instalarse desde su repositorio\.
  * Ejemplo: __pip__  __install__  __requests__  __\,__  __shodan__  __\,__  __nmap__

# Pruebas de software

* Las pruebas de software son un proceso cuya intención es la búsqueda de errores y comprobación de que una aplicación o sistema funciona de la manera que se espera\.
* Tipos:
  * Pruebas funcionales\.
  * Pruebas no funcionales\.

* Pruebas funcionales
  * Pruebas unitarias
  * Pruebas de integración
  * Pruebas de componentes
  * Pruebas de regresión
* Pruebas no funcionales
  * Pruebas de estrés
  * Pruebas de carga
  * Pruebas de volumen
  * Pruebas de configuración

  * Pruebas de aceptación
  * Pruebas de humo
  * …\.\.
  * Pruebas de escalabilidad
  * Pruebas de seguridad
  * ……

Prueba unitaria – ejemplo enpython

![](img/Tema%20130.png)

![](img/Tema%20131.png)

# Entornos de ejecución

* Entorno de ejecución:  Término que se refiere al entorno donde se ejecutará el software así como los requerimientos necesarios para su correcto funcionamiento\.
* Principales requerimientos:
  * Dependencias de biblioteca
  * Interprete/Máquina virtual
  * Variable de entorno
  * Sistema operativo
  * …\.\.

Sandboxes

* Sandbox: Es un entorno de prueba controlado que se utiliza para ejecutar archivos sin afectar al sistema o plataforma principal\.
* Principales usos:
  * Probar software nuevo antes de pasarlo a producción\.
  * Para analizar software potencialmente malicioso\.
  * Para proteger que el software no pueda acceder a datos privados de usuario \->Ej: Navegadores
* Es una característica del lenguaje java que proporciona un entorno limitado para ejecutar código no confiable\.

# Seguridad de los lenguajes de programación

Principales vulnerabilidades

![](img/Tema%20132.png)

Fuente:[cvedetails\.com](https://www.cvedetails.com/vulnerabilities-by-types.php)

Principales vulnerabilidades

![](img/Tema%20133.png)

Fuente:[cvedetails\.com](https://www.cvedetails.com/vulnerabilities-by-types.php)

