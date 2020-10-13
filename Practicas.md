# Sistemas Informáticos 20/21
### Práctica 1:
##### 1.Define “sistema informático”
Es la simbiosis de todos los elementos físicos y lógicos para realizar calculos a gran velocidad y precisión.
##### 2.Realiza un esquema gráfico de la arquitectura Von Neumann identificando y justificando los posibles cuellos de botella
<img src="https://wizbyte.files.wordpress.com/2014/07/vonneumann2.jpg"/>
El canal de transmisión de los datos compartido entre CPU y memoria genera un cuello de botella de von Neumann, un rendimiento limitado (tasa de transferencia de datos) entre la CPU y la memoria en comparación con la cantidad de memoria.
##### 3.Indica los pasos que sigue el ordenador para realizar una suma describiendo la función de cada componente de la arquitectura Von Neumann.
Primero introduciriamos los operandos por el periferico (teclado), la unidad E/S interpretaria las pulsaciones y las transformaria en datos que la unidad de control pudiera entender.
Estos datos se alamcenaran en la memoria principal, estos datos contendran tanto los datos como las instrucciones.
La unidad de control extraera la siguiente instrucción de la memoria principal, entonces la unidad de control cambia el registro contador de programa con la dirección de la siguiente instrucción a realizar.
La unidad de control revisa que tipo de instrucción és y donde se encuentra los datos en la memória principal.
Despues sacara los datos de la posición especifica de memória, despues la unidad de control enviara estos datos a la unidad aritmeticologica junto con la operacion y se ejecutara, y para finalizar se ejecutara la instrucción.
##### 4.Explica con tus propias palabras el concepto de jerarquía de memoria y justifica su necesidad.
Es una organización basada en una piramide donde se organiza la memória de más rápida a más lenta en orden ascendente, las memórias mas lentas son de mayor capacidad que las rapidas y mas baratas tambien.

Esta jerarquia es necesaria por temas economicos mas que nada pues las memorias mas rápidas tienes un valor muy superior a las mas lentas, y no seria viable por costes un ordenador.
##### 5.Calcula el tamaño total en bytes de un disco duro con 8 cabezales, 1024 cilindros, 256 sectores por pista y 512 bytes por sector.
Capacidad= 1024 x 8 x 256 x 512 = 1073741824 B
##### 6.Indica las principales diferencias entre las interfaces ATA y SATA.
Los cables con estandar ATA seguian una jerarquía MASTER/SLAVE por lo cual su velocidad se veia afectada si el MASTER tenia unas velocidades inferior al SLAVE o bien si se requeria acceso al MASTER y al SLAVE a la vez, mientras que los cables SATA funcionan en paralelo y no comparten el bus.

Los cables ATA solo pueden trabajar a un maximo de 166M/s, mientras que los cables SATA pueden trabajar a un máximo de 600M/s
##### 7.Indica las diferencias entre acceso secuencial y acceso directo
En el acceso secuencial la memoria se organiza en unidades de datos llamados registros.El acceso debe realizarse con una secuencia lineal específica, en el acceso directo tiene asociado un mecanismo de lectura/escritura, los bloques individuales  o  registros  tienen  una dirección única basada en su dirección física.
##### 8.¿Cuál será la latencia media de un disco duro de 5400 RPM?
(5400/60) x 500 = 5.5 milisengundos
##### 9.Investiga en Internet sobre la Ley de Moore y resume con tus propias palabras en qué consiste.
Consiste en una ley que predice que con la evolución de la tecnologia se deberia poder reducir el tamaño de los transistores y asi cada 2 años.
##### 10.Dado el siguiente número hexadecimal “CAFE” obtén su representación en:
1. Binario.
1100101011111110
2. Octal.
145376
##### 11.Busca 5 microprocesadores se estén utilizando actualmente en los ordenadores personales de sobremesa y en los portátiles e indica las siguientes características:
1. Velocidad de proceso
2. Tipo de encapsulado
3. Socket
- Intel i9 9900K
  - Frecuencia del procesador: 3,6 GHz
  - Socket de procesador: LGA 1151 (Zócalo H4)
- Intel Core i7-9700K
  - CPU Socket LGA 1151
  - Base Clock Speed 3.6 GHz
- Intel Core i5-9600K
  - CPU Socket LGA 1151
  - Base Clock Speed 3.7 GHz
- Intel Core i3-9300
  - Frecuencia del procesador: 3,7 GHz
  - Socket de procesador: LGA 1151 (Zócalo H4)
- Intel Pentium Gold G5420
  - Frecuencia del procesador: 3,8 GHz
  - Socket de procesador: LGA 1151 (Zócalo H4)