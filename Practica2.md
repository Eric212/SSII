# Sistemas Informáticos 20/21
## Práctica 2
### Fecha máxima de entrega:GB 21/10/2020
##### 1.Define las diferencias entre estructura funcional y estructura física de un computador.
La diferencia entre estructura funcional y estructura fisica, es que la estructura funcional es la definición de como el ordenador consigue los datos y los procesa mientras que estructura fisica define todo los componentes fisicos que integran un ordenador
##### 2.¿Para qué sirve un driver o controlador? Pon tres ejemplos.
Un driver o controlador, es un programa que hace de interprete entre los perifericos y el sistema operativo.
##### 3.¿Qué  es  la  UEFI?  ¿Cuál  crees  que  fue  el  motivo  que  propició  su  aparición?  ¿Qué ventajas e inconvenientes aporta frente a la BIOS? 
- La UEFI es un tipo de memoria EPROM que se alimenta mediante una pila para que no pierda su contenido, esta memoria integra un menu que contiene y nos permite modificar configuracion basica de los componentes del ordenador.
- El motivo fue la evolucion de las CPU, puesto a que la configuracion que ofrecia su antecesora era muy limitada para lo que la nueva generación requeria.
- Ventajas:
    - Ofrece retrocompatibilidad
    - Soporte al nuevo tipo de estandar de particionado (GPT)
    - Es independiete a la arquitectura y controladores
    - Es un pre-Sistema opertivo, que llega hasta ofrecer funcionalidad de red
- Desventajas:
    - Aveces tanta informacion ofusca la objetividad del usuario, y dificulta la busqueda de parametros
##### 4.Explica las diferencias entre SATA y SCSI. Investiga si SCSI sigue teniendo aplicaciones hoy en día, explicando cuáles son y por qué sigue siendo interesante en el caso de que las tenga.
La gran diferencia entre SATA y la tecnologia original de SCSI es la velocidad, pues la máxima velocidad que se podia alcanzar en la tecnologia original de SCSI era de 80 MB/s, frente a los 150 MB/s que presentaba SATA en su primera versión la cual se mejoro hasta 600 MB/s con su version 3.
SCSI sufrio una adaptacion que se denomino SCSI (SAS), que cambia de una interfaz paralela a una en serie, como serian los SATA, pero sigue utilizando los comandos SCSI para la interaccion entre dispositivos SAS, esta nueva tecnologia nos permite alcanzar velocidades maximas de 22.5 GB/S.
Esta nueva tecnologia da cabida a que sea una opcion muy optima en sistemas de almacenamiento versatiles y de gran escalabilidad.
##### 5.Especifica todos los componentes hardware necesarios para montar una torre que será empleada   para   ejecutar   el   software   AutoCAD   2021.   Debes   razonar   todos   los componentes  que  selecciones  atendiendo  a  los  criterios  de  eficacia  y  economía.  Esta torre  estará  conectada  a  una  red  10  Gbps  y  dispondrá  de  dos  monitores  de  25”  4K. Manejará  archivos  de  entre  2  y  6GB,  por  lo  tanto  debe  de  permitir  manejar  el multitasking  con  soltura  entre  las  aplicaciones  de  Microsoft  Office  365  instaladas onpremise   así   como   Microsoft   Business   Central   también   instalado   onpremise   y AutoCAD.  El  sistema  operativo  será  Windows  10  Pro.  Presenta  un  presupuesto  de  la torre junto con su descripción razonada de componentes.
<img src="https://github.com/Eric212/SSII/blob/master/cpu.png"/>
- He elegido este procesador por sus 8 nucleos y 16 hilos los cuales ayudaran a balancear la carga de trabajo del multitasking, y por su alta frecuencia de 3.9GHz con un turbo de 4.5GHz pues AutoCAD recomienda unos 3GHz o mas, y tenemos que preveer que ademas del consumo de los programas hara falta un minimo para el funcionamiento del sistema.
<img src="https://github.com/Eric212/SSII/blob/master/ram.png"/>
- He elegido esta RAM, pues para modelado 3D es necesario una gran cantidad de RAM, y con 32GB el sistema tendra suficiente para todos los programas ademas del sistema en si, ademas de sus 3200Mhz para poder manejar datos a altas velocidades y por su latencia CL14 que nos permite aumentar el rendimiento pues el tiempo de acceso a los datos menor.
<img src="https://github.com/Eric212/SSII/blob/master/placa.png"/>
- He elegido esta placa por su capacidad de dos unidades de almacenamiento M.2, por su compatibilidad con memorias RAM de alta frecuencia.
<img src="https://github.com/Eric212/SSII/blob/master/liquida.png"/>
- He elegido esta refrigeracion liquida, puesto que mantiene unas temperatura mas constantes y puede ser mas eficiente que una refrigeracion por aire, y el precio es muy equivalente al de una buena refrigeracion por aire.
<img src="https://github.com/Eric212/SSII/blob/master/m.principal.png"/>
- He elegido este modulo M.2 de 512 GB porque los programas de modelado 3D necesitan una alta tasa de lectura y escritura, este modulo cuenta con una velocidad de escritura de hasta 2.700 MB/s y de lectura de hasta 3.500 MB/s.
<img src="https://github.com/Eric212/SSII/blob/master/m.secundaria.png"/>
- He elegido este disco duro de 4 TB por su alta capacidad.
<img src="https://github.com/Eric212/SSII/blob/master/grafica.png"/>
- He elegido esta grafica porque tiene suficiente potencia para mover graficos 4k, y con 6 de memoria GDRR6 suficiente para todos los programas y el sistema operativo, ademas de un acho de banda de 336 Gb/s mas que suficiente para poder trabajar con AutoCAD.
<img src="https://github.com/Eric212/SSII/blob/master/10GB.png"/>
<img src="https://github.com/Eric212/SSII/blob/master/caja.png"/>
- He elegido esta caja porque dispone de filtro antipolvo, incluye usb 3.0, y dispone de espacio para ampliar almacenamiento.
<img src="https://github.com/Eric212/SSII/blob/master/fuente.png"/>
- He cogido esta fuente de alimentación porque todo el equipo necesita alrededor de 356 W de potencia, por esa razón he cogido una fuente de alimentación con mas portencia para evitar problemas por falta de suministro elecrtico, pues aveces los equipos pueden tener picos por encima de su consumo habitual y si la fuente es muy justa puede fallar, y en caso de no fallar siempre estaria estresada y tendria un tiempo de vida inferior por estar siemrpe forzandola al máximo

### Total 1.604,77€
