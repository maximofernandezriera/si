---
title: Sistemas informáticos
type: book  # Do not modify.
toc: false
---

```
M1 - Implantación de Sistemas Operativos
```
# Unidad Didáctica 2

```
Instalación de Sistemas Operativos
```
Raül Sala / José Luis Antúnez - 2017/
ED1ASIXDAI_ACT_0910_01_R1_M1_UF1_A04_Tr
Actividad 4


## El sistema operativo

```
Introducció.Composició. Funciones y objetivos. Tipo. Servicios. Introducción a los sistemas operativos DOS y UNIX.
```
#### La informática

##### ◉Nace para evitar tareas repetitivas de cálculo y

##### gestión.◉El término informática apareció en Francia

##### en 1962:

### INFOR mation auto MATIQUE

##### ◉ La informática es la ciencia que estudia el tratamiento

##### automático y racional de la información.

```
▪Desarrollo y mejora de máquinas
▪Desarrollo y mejora de nuevos sistemas automáticosde trabajo.▪
```

```
Construcción de aplicaciones informáticas.
```
```
3
```
#### El sistema binario

##### ◉Para los ordenadores todos los datos son númerosy todo

##### acaban siendo conjuntos de 0 s y 1 s.

##### ◉Debido a esto último, el ordenador no utiliza el sistema decimal

##### si no el sistema binario.

##### ◉El ordenador utiliza mecanismos que traducen los datos a:▪

```
Sistemas numéricos
▪Códigos alfanuméricos
```

```
4
```
#### Medida de la información

##### ◉Como en la mayoría de ámbitos, en la informática se utiliza

##### una unidad base y sus múltiples → el bit (b ).

```
▪Permiten dos valores: 0 y 1.
⚫Cuántas combinaciones podemos representar con unúnico bit?
⚫Cuántas combinaciones tenemos con 2 bits? con 3?con 4? ...
```
##### ◉La información que da un bit es mínima, por lo tantohay que

##### buscar sus múltiples:

```
▪Conocemos como byte (B) los conjuntos de 8 bits.
```

```
5
```
#### Múltiples en el Sistema Internacional

##### ◉En el Sistema Internacional utilizan prefijos paradesignar los

##### múltiplos de una unidad determinada:

```
nombre
unidad
```
```
símbolo valor en el SI
100 = 1
kilo k 103 = 1.
mega M 106 = 1.000. 000
giga G 109 = 1.000.000.
tera T 1012 = 1.000.000.000.
```

```
peta P 1015 = 1.000.000.000.000.
exa E 1018 = 1.000.000.000.000.000.
zetta Z 1021 = 1.000.000.000. 000.000.000.
yotta Y 1024 = 1.000.000.000.000.000.000.000.
```
```
6
```
#### múltiples en binario

◉Cuando se crearon los múltiplos de las unidadesen binario se adaptaron
a su sistema de numeración:
**nombre**
unidad

```
símbolo valor en el SI
20 = 1
kilo k 210 = 1.
mega M 220 = 1.024 · k
giga G 230 = 1.024 · M
tera T 240 = 1.024 · G
```

```
peta P 250 = 1.024 · T
exa E 260 = 1.024 · P
zetta Z 270 = 1.024 · e
yotta y 280 = 1.024 · Z
Bronto B 290 = 1.024 · y
```
◉Qué posible **confusión** encuentra entre el SistemaInternacional y el binario?

```
7
```
#### Sistema Internacional vs Binario

##### ◉Fíjense a la siguiente tabla:

```
Nombre Símbolo Potencias binarias y valores decimales Valores en el SI Hexa. Nombre Diferencia
```
```
unidad 20 = 1100 = 1160 un(o)0%KiloK 210 = 1024103 = 100016 2,5mil2%MegaM^220 =^1048576106000000165 Millón5%GigaG2 30 = 1
```

```
073 741 824 10 millardo 7% Tera T2 40 = 1 099 511 627 776billón 10%
```
```
Peta P2 50 = 1 125 899 906 842billard 13%
```
```
Exa E2 60 = 1 152 921 504 606
```
```
Zetter Z^270 = 1180
```
```
591 620 717 411 3 03 424 10
Trillón 15%
```
```
10 21 = 1 000 000 000 000
trillardo 18%
```
```
8
```
#### Sistema Internacional vs Binario (II)

##### ◉el uso del Sistema binario creó confusión 1024noes 1000

##### ◉Los prefijos del Sistema binario utilizan potenciasde 2,mientras

##### que el SI utiliza potencias de 10.

```
▪Los fabricantes de discos duros utilizan el sistemadecimal, pero el
ordenador calcula la capacidad mediante el Sistema Binario. Usamos
la siguiente fórmula para calcular la capacidad en Binario:
```

```
⚫ N es la capacidad del fabricante
⚫ y es el prefijo equivalente en decimal
⚫ x es el prefijo equivalente en binario
```
##### ◉Qué capacidad, en Sistema Binario, tiene un disco duro de

##### 120 GB según su fabricante?

```
9
```
#### Sistema Internacional vs Binario (III)

##### ◉ SOLUCIÓN a la confusión:se introducen nuevos prefijos

```
Nombre Símbolo Sistema significada
```
```
bit bit 0 ó 1
```
```
kibibit Kibito CEI 1.024 bits
```
```
kilobit kbit SI 1.000 bits
```

```
mebibit Mibit CEI 1.024 kibibits
```
```
Megabit Mbit SI 1.000 kilobits
```
```
Gibibit Gibit CEI 1.024 mebibits
```
```
Gigabit Gbit SI 1.000 megabits
```
```
Tebibit Tibit CEI 1.024 gibibits
10
```
#### Introducción a los sistemas operativos

##### ◉Ordenador: máquina compleja:

```
▪Uno o más procesadores
▪Discos y dispositivos de almacenamiento
▪Tarjetas de comunicaciones
▪Periféricos
▪...
```

##### ◉Un usuario debería de conocer los detalles técnicos para

##### controlar a la perfección los dispositivos→ solución

##### imposible.

##### ◉Hay que buscar una solución a este problema de manera que

##### un usuario cualquiera pueda utilizar fácilmente lamáquina.

#### Sistema operativo

##### ◉ Capa de software que aísla el hardware de los usuarios.

```
Hardware
```
```
Sistema Operativo
Software
```

##### ◉El sistema operativo tiene 3 objetivos principales:

```
▪ Comodidad: hace que el ordenador sea más fácil deutilizar▪
Eficiencia: permite que los recursos del sistema seutilicen de forma más
eficiente
▪ Capacidad de evolución: está construido de formaque permita un
desarrollo continuo (actualizaciones, correcciones, nuevos servicios,
...)
```
```
12
```
#### funciones del sistema operativo

##### ◉las funciones principales que debe realizar un sistema

##### operativo son las siguientes:

```
▪Gestión de usuarios
▪Gestión de procesos
▪gestión de memoria
▪gestión de archivos
```

```
▪gestión de los dispositivos de entrada y salida
```
##### ◉El núcleo (kernel) del sistema operativo administratodas

##### las funciones antes mencionadas.

```
13
```
#### Perspectiva histórica de los sistemas operativos

##### ◉Las causas principales de la evolución de los sistemas

##### operativos han sido:

```
▪Las actualizaciones y los nuevos tipos de hardware
▪Las demandas de nuevos servicios
▪La necesidad de resolver varios tipos de errores
```

##### ◉Los sistemas operativos, igual que el hardware, han

##### sufrido cambios a través del tiempo.

```
14
```
#### Tendencias actuales

##### ◉Multiproceso:

```
▪Sistemas con varios procesadores→el sistema operativose encarga de
administrar los procesadores para repartir el trabajo de forma
equilibrada
```

##### ◉Sistemas más tolerantes a fallos

```
▪Sistemas de envío de errores para facilitar la tareade corrección.
```
##### ◉Sistemas abiertos → estandarización en las

##### comunicaciones, interfaces de usuario y aplicaciones

##### ◉Interfaces de usuario más amigables

##### ◉Sistemas operativos ligeros

```
15
```
#### Tipos de sistemas operativos

##### ◉Podemos clasificar los sistemas operativos según varios

##### criterios:

```
▪Según la utilización de recursos
```

```
▪Según la interactividad
▪Según el número de usuarios
▪Según el número de procesadores
▪Según la distribución de tareas del sistema
▪Según su estructura
```
```
16
```
#### Según la utilización de recursos

##### ◉número de programas que se quiere ejecutar simultáneamente:

```
▪ Sistemas monoprogramats / monotasca: sólo admitenun programa al
```

```
sistema. El programa es cargado en memoria y es allí hasta que acaba
de ser ejecutado. Durante este periodo no se puede ejecutar ningún
otro programa.
▪ Sistemas multiprogramados / multitarea: pueden admitiruno o
más programas de uno o más usuarios simultáneamente.
```
```
17
```
#### Según la interactividad

###### ◉Tipo de trabajo al que son destinados los sistemas:

```
▪ Sistemas de procesamiento por lotes (batch): mecanismomás tradicional y
antiguo para ejecutar tareas. En el proceso por lotes, cada trabajo efectúa
una serie de pasos secuenciales relacionados. NO interactúancon usuario,
```

```
muy importante una planificación cuidadosa.Se utilizan a
Supercomputadores y también a niveles más bajos.
▪ Sistemas de tiempo compartido (time sharing): sistemasque aceptan que
varios programas compitan por los recursos del sistema. Esto implica que la
CPU es asignada durante un periodo de tiempo limitado, llamado
quantum. Así, cuando un programa deja de ejecutarse,libera la CPU. Los
más utilizados !!
▪ Sistemas de tiempo real (real time): sistemas multiprogramadose
interactivos más exigentes, basados en una respuestarápida sobre los
sistemas que se quiere controlar a partir de las informaciones recibidas. Son
muy complejos. Utiliza algoritmos basados en prioridades.Sino responde
adecuadamente en un tiempo establecido, se dice que el sistema ha fallado.
Se utilizan para control aéreo, bolsa de valores, control de trenes, etc. Ex:
VxWorks, Solaris, Lyns OS y Spectra
```
```
18
```
#### Según el número de usuarios

##### ◉Número de usuarios que pueden acceder al sistema: ▪ Sistemas

```
monousuario: sólo permiten en un determinado momentola conexión
```

```
de un único usuario a la vez en el sistema. Utilizan técnicas de
monoprogramació ejecutando un único programa o pueden ser sistemas
multiprogramados, que facilitan al usuario la ejecución de varios
programas a la vez.
⚫tomaremos el sistema operativo DOS / Windows comocaso de estudio
de esta tecnología.
▪ Sistemas multiusuario: utilizan técnicas de multiprogramacióny
ofrecen la posibilidad de que varios usuarios accedan a la vez al
sistema, y se puede utilizar también tiempo real y tiempo
compartido.
⚫tomaremos el sistema operativo Unix / Linux comocaso de estudio
de esta tecnología.
```
```
19
```
#### Según el número de procesadores

##### ◉Cantidad de procesadores de los que dispone el ordenador:


```
▪ Sistemas monoprocesador: el ordenador dispone de una única CPU y
por lo tanto todos los programas se ejecutarán en la misma CPU.
▪ Sistemas multiprocesadores: el ordenador disponede varias CPU, esto
permite que un mismo trabajo o diferentes trabajos se ejecuten en
diferentes CPU.
```
```
20
```
#### Según la distribución de tareas del sistema

##### ◉El trabajo se reparte entre varios procesadores conectados en


##### red:

```
▪ Sistemas centralizados: una máquina realiza todaslas tareas del
sistema operativo (mainframe). Los usuarios únicamentedisponían
de un terminal tonto (antiguamente no disponían nide memoria ni
de procesador, actualmente sí, pueden hacer más tareas).
```
```
▪ Sistemas distribuidos: engloba y gestiona varios sistemas
interconectados con una red que son capaces de cooperar y
comunicarse gracias a esta red y al software que la gestiona.
⚫Cada procesador tiene su propia memoria local, nocomparten
reloj.
⚫La comunicación entre los procesadores es a travésde líneas de
comunicación.⚫Puede haber procesadores de diferentestamaños y
funciones.
⚫Ventajas:compartición de recursos, aceleración decálculos,
fiabilidad (backups), etc.
```
```
21
```
#### Sistemas Distribuidos vs Sistemas en Red


##### ◉No se debe confundir el

##### sistema

##### distribuido con el sistema en

##### red:

```
▪En un sistema operativo en red,
los ordenadores están
interconectados. Cada
ordenador tiene
su propio software y
hardware.
```
```
▪En un sistema operativo
distribuido,
el software distribuye las
tareas en la red,y los usuarios
no se enteran donde se realizan
las tareas.
```

```
22
```
#### Sistemas operativos monousuario

##### ◉Los sistemas operativos monousuario:

```
▪Sólo permiten la conexión de un único usuario ala vez al
sistema.▪ Pueden ser:
⚫ Monoprogramats: un único programa ejecutándose al
mismo tiempo.⚫ multiprogramados: más de un programa
ejecutándose al mismo tiempo.
```
##### ◉En este apartado veremos el sistema operativo DOS como

##### ejemplo de sistema operativo monousuario.

##### ◉El DOS es el origen de la familia de sistemas Windows.

#### Inconvenientes del DOS


##### ◉No tiene interfaz gráfica.

##### ◉Es incapaz de detectar hardware (noexistía plug and play). ▪

```
Hay configurarlo manualmente.
```
##### ◉No es multiusuario.

##### ◉No es multitarea.

##### ◉No podía trabajar con discos muy grandes:

```
▪Originalmente no podía trabajar con más de 64 KBde RAM ▪A partir
de la versión 7.1 ya soportaba sistemas de ficheros FAT32 (4GB de
limitación).
```
```
24
```
#### Sistemas operativos multiusuario


##### ◉Los sistemas operativos multiusuario:

```
▪Permiten la conexión de más de un usuario al sistemaal mismo tiempo.
```
##### ◉En este apartado daremos los conocimientos y bases del

##### sistema operativo Unix.

```
▪Sistema operativo multiusuario más representativo.
▪Es un sistema libre→ lo podemos estudiar.
```
```
25
```
#### Características del sistema operativo Unix (1)


##### ◉Unix es flexible, fiable y fácil de usar:

```
▪Es multiusuario.
▪Es multitarea:
⚫Puede haber más de un programa ejecutándose al mismotiempo,
utilizando el sistema de tiempo compartido.
▪ Independencia de los dispositivos:
⚫Los dispositivos no son más que archivos dentrodel sistema.
⚫Se pueden incorporar los nuevos dispositivos: cualquiercantidad y
cualquier tipo.
▪ Memoria virtual:
⚫Cada usuario dispone de toda la memoria del sistemapara
ejecutar aplicaciones.
```
```
26
```
#### Características del sistema operativo Unix (2)


```
▪ Sistema de archivos jerárquico:
⚫Utiliza un árbol con todos los archivos.
⚫Tiene una raíz única ya partir de ahí cuelga todoel sistema de
archivos.▪ Comunicaciones y capacidades de red:
⚫Está preparado para conectarse con cualquier máquinadel
mundo.⚫Utiliza el protocolo TCP / IP.
▪ Sistema de seguridad:
⚫Contraseñas para cada usuario.
▪Portabilidad:
⚫Soporta varios tipos de ordenadores, no dependedel hardware.
```
```
27
```
#### Componentes del sistema Unix


##### ◉ Núcleo del sistema (KERNEL): ofrece sus servicios y el acceso a

##### dispositivos mediante llamadas al sistema y llamadas a funciones.

▪Pero, mientras los programas acceden directamentea estas llamadas al

sistema oa función, **_para que el usuario pueda accedera los servicios del
sistema se necesita un programa que haga de intermediario entre el usuario_**

##### (mediante el terminal) y el Kernel. Este programaes el SHELL.◉ Sistema

##### de ficheros:gestión de la información.

##### ◉ Intérprete de comandos (SHELL): interfaz de comunicación con

##### el sistema.

```
▪ Gráficos (GUI):elementos gráficos a través de loscuales se realizan
acciones.▪ Texto: comunicación mediante comandos (shell).Existen
varios tipos de shell.
```
```
28
```
#### Proceso de arranque del sistema Unix


##### ◉ Prerrequisito: hay que disponen de una cuenta en el

##### sistema.◉ Prerrequisito: es necesario que el servidor esté en

##### marcha (caso clienteservidor).

##### ◉Se puede hacer de forma gráfica o de texto:

##### supongamos entorno texto.

##### 1.Conexión: entrada al sistema. Usuario + contraseña:

```
a)Administrador: le aparece el símbolo #.
b)Usuario: le aparece el símbolo $.
```
##### 2.Desconexión: salida del sistema. Cierre de sesión: ▪ NUNCA

```
SE PUEDE TERMINAR UNA SESIÓN apagado DIRECTAMENTE. ▪
Para terminar sesión: logout, exit o <CTRL> + D
▪ Para apagar el sistema: shutdown, halt (= reboot, =poweroff).⚫
Acepta varias opciones para el cierre:
⬥ shutdown -h now (cierra inmediato), shutdown -y-g0 (cierra sin
confirmación, inmediato).
```
```
29
```

#### runlevel (1)

◉Los sistemas Linux pueden tener diversas configuracioneso
estados.◉Estos estados se conocen como runlevels.
▪Escribimos **runlevel** para saber en qué runlevel nosencontramos.
▪Para cambiar de runlevel, hacemos **init N** o **telinitN** (N es el runlevel).
**runlevel**
0

```
función
Hace que el sistema se detenga
1, s, S Lleva el sistema al modo monousuario, utilizado para encontrar
errores.
2 Modo multiusuario, pero sin soporte de red.
3 Modo estándar de texto: multiusuario con soporte de red.
4 No definido.
5 Modo estándar de interfaz gráfica.
6 Reiniciar el sistema
7..9 No definidos en la versión Unix estándar.
```
```
▪ un sistema Linux NO se arranca o se para, sino quesimplemente se cambia su
nivel de ejecución
```

```
30
```
#### runlevel (2)

##### ◉Debian y Ubuntu utilizan systemd en lugar de init,

##### introducen el concepto de target ':

```
runlevel
0
```
```
función
poweroff.target (Hace que el sistema se detenga)
1, s, S rescue.target (Puerta el sistema al modo monousuario,utilizado para
encontrar errores)
2 -4 multi-user.targe t (modo multiusuario)
5 graphical.target (modo Gráfico multiusuario)
6 reboot.target (Reiniciar el sistema)
7..9 No definidos en la versión Unix estándar.
```
##### ◉ Consultamos nivel ejecución: 'runlevel' o 'who

##### -r' ◉ Establecemos nivel de ejecución

##### predeterminado:


##### $ sudo systemctl set-defaultmulti-user.target

##### ◉Para más información: man systemctl

```
31
```
#### Terminales virtuales

##### ◉Linux dispone de hasta 4 terminales virtuales.

##### ◉Para iniciar sesión en un terminal virtual hay quehacer

##### <CTRL> + <ALT> + <Fn> → donde Fn es la tecla F3..F6.

```
▪Para volver al entorno gráfico haremos <CTRL> +<ALT> + F2 o F1
```

```
32
```
#### Bibliografía y recursos utilizados

◉Estruch, J. Esteve; Carpintero, M. Ángel (2008). _Sistemas_ Operativos.Instituto Abierto de Cataluña.
◉Raya, Laura; Martín, Alejandro; Rodrigo, Víctor(2003). Sistemas Informáticos Monousuario y
Multiusuario. RA-MA


33


