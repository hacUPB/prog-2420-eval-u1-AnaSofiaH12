[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ZHlrD2sU)
# Hardware y Software
### **•	¿Cuál es la función principal de cada componente investigado?** 
Las computadoras son un sistema informático compuestos por dos figuras fundamentales:

#### **1.Hardware:** Estos elementos son los que podemos tocar con nuestras manos y pueden ser internos o externos:

#### **1.1 Internos:**

**-Placa madre:** Esta es la placa principal, acá se conectan todos los sistemas informáticos de manera directa o indirecta, y también cuenta con un software llamado BIOS. 

**-Procesador:** También conocido como CPU o el cerebro del computador, es el responsable de controlar todo lo que se hace y de realizar cálculos e interpretaciones de datos en el ordenador. 

**-Memoria Interna RAM:** Su función principal es almacenar información, pero de manera rápida y temporal para ser utilizada al momento, a mayor cantidad de RAM más rápido puede funcionar todo. No almacena el programa como tal, pero si la manera de ejecutarlo.

**-Memoria Interna ROM:** Allí se almacena la información de manera permanente, pero el usuario no puede alterar el contenido, solo se podría hacer una lectura del mismo e instalarlo o desinstalarlo. Esta, almacena todo lo relacionado con instrucciones o también denominado BIOS que abarca el cómo funcionan los programas, entre otros.

**-Placa de video:** También conocido como tarjeta gráfica, es un instrumento que está vinculado a la placa madre y permite que el equipo proyecte las imágenes en el monitor, nosotros podemos hacer cambios en la configuración de la imagen, por ejemplo, en el tamaño, la resolución, entre otros.

**-Placa de sonido:** Igual que el anterior, está conectado a la placa madre y su función principal es permitir reproducir sonidos por medio de altavoces o también recibe sonidos a través de micrófonos. 

**-Dispositivo de almacenamiento secundario:** Allí se almacenan datos de manera permanente o hasta que el usuario desee eliminarlos, estos datos el equipo no los necesita de manera instantánea para su funcionamiento, si no que el usuario los manipula directamente como documentos, imágenes, audios, videos, entre más. 

#### **2.1 Externos:**

**-Dispositivos de entrada:** Son piezas que reciben datos sin haber procesado antes, pero que el equipo lo puede procesar a través de softwares, hay dos tipos de dispositivos: el dispositivo de entrada manual y los dispositivos de entrada automática.  
**-Dispositivos de salida:** Al contrario del anterior, estas son piezas que expulsan hacia afuera los datos procesados por el computador, hay dos tipos: de salida temporal, como el monitor que proyecta las imágenes de salida en la pantalla, y de salida permanente como la impresora.
**-Dispositivos periféricos:** son piezas de entrada y salida que no son tan esenciales, ya que el sistema puede funcionar sin ellos.

![](https://i0.wp.com/ytimg.googleusercontent.com/vi/6Q9mhFA-jTY/maxresdefault.jpg?resize=650,400)


**2.Software:** Es la parte no física del computador y son un conjunto de programas, instrucciones y regulaciones informáticas para elaborar ciertas tareas en el computador. 

Hay dos tipos:

**2.1 Software de sistema:** Son programas preinstalados en el ordenador que permiten dar soporte a otros programas instalados por el usuario. 

**2.2 Software de aplicación:** Estos son programas que no son relevantes para el funcionamiento del computador, sino que son instalados por el usuario para cumplir diversas necesidades. 

### **•	¿Cómo interactúa el hardware con el software, cuál es la función de cada uno?**

### **•	¿Cuál es la función de la CPU y cuáles son sus partes más importantes?**
La Unidad central de procesamiento, es el equipo encargado de ejecutar los cálculos matemáticos lógicos de todo el software, allí se procesan todos los datos mandados por el software, gracias a la Unidad Aritmética Lógica y la unidad de control, por esto también es conocida como el cerebro del computador.
La CPU almacena instrucciones en la memoria, decodifica normas de ensamblaje, ejecuta instrucciones, entre otros.
Los principales componentes de la CPU son los siguientes: 

-Unidad de control: Tramita el procesamiento de instrucciones y controla e organiza los datos que están en el ordenador.

-Registros: Son pequeños sitios de almacenamiento de memoria a alta velocidad. Existen varios tipos de registros: registro general que tiene datos operativos, registro de instrucciones y un contador de programas que contiene las direcciones de memoria de lo que va a recuperar 

-ALU: La unidad aritmética lógica ejecuta operaciones básicas y operaciones lógicas sobre los datos. Recibe datos de la CPU, los procesa y luego genera el resultado.

-Unidad de gestión de memoria: La CPU puede tener una interfaz de bus o una unidad de gestión de memoria, estos mecanismos se encargan de las tareas que tienen que ver con la memoria, como la relación entre el RAM Y CPU, también gestiona memorias mucho más pequeñas, entre otros. 

-Reloj: La CPU gracias a la vinculación con una señal de reloj se regulariza y así el reloj genera un ritmo constante a una frecuencia determinada y nos arroja unos ciclos que se sistematizan con las operaciones de la CPU. Esto estipula cuantas instrucciones puede cumplir tu CPU por segundos. 
### **•	¿Qué es la velocidad de la CPU, también conocida como velocidad del reloj?**
-La velocidad reloj evalúa la cantidad de ciclos que ejecuta la CPU por segundos, y su unidad de medida son los GigaHertz (GHz). La CPU cada segundo está procesando diferentes programas sencillos y otros más complicados, entonces un procesador con la frecuencia mayor va a ser mucho más eficiente en la velocidad con la que procesa todo, que uno de frecuencia de menor, se va a tardar mucho más tiempo ejecutando todo. 
### **•	¿Cuál es la secuencia de pasos que ocurre, desde el momento en que presionas el botón de encendido de la computadora, hasta que se muestra el sistema operativo listo para funcionar? Describe todos los elementos involucrados y el paso a paso.**
-El proceso de arranque del equipo es bastante complejo ya que ocurren varias cosas en pocos segundos, a continuación, estos son los pasos que ocurren al encender un computador:
1.	Inicio de la CPU: Primero que todo el Reloj en tiempo real es el que almacena la hora y sirve como una base para contar el tiempo del sistema operativo, también existe el productorr de la señal de reinicio, un oscilador que genera señal para vincular la CPU, la RAM y muchos más elementos. 
A la hora de presionar el encendido, la fuente de alimentación suministra energía y una señal llamada “Power good” comprueba que esta energía si la reciba de manera correcta la CPU, la CPU empieza sus registros, borrando cualquier dato anterior del funcionamiento previo e iniciando todo.
2.	Reset code: Comienza la ejecución de programas almacenados en una memoria, acá se refiere a una dirección especifica que recopila las instrucciones para iniciar una rutina de reinicio para activar componentes del Hardware que complementan la CPU, en cada momento que se realiza una instrucción del programa de arranque, el registro de contador de programa va incrementando la dirección en 1 para seguir con el proceso completo, así se ejecutan toda la secuencia de normas que se deben cumplir. 
3.	Startup Code: se procede a ejecutra otra rutina guardada en la memoria no volátil. Se realiza el “Power on Self Test” para comprobar el estado del hardware. La CPU hace como un autodiagnóstico ya que se inspecciona a sí misma para verificar que todo si está correctamente conectado a él. 
Por ejemplo: se calcula la memoria de a GPU, se comprueban la señal de la pantalla, se ejecutan pruebas en los chips de RAM, se revisa el funcionamiento de todos los botones, el teclado, entre muchos más procedimientos. 
4.	Bootstrap: Esta rutina contiene las instrucciones necesarias para iniciar el sistema operativo a través del gestor de arranque o bootloader. Para Linux, Windows y Mac el proceso es distinto, para proceder con Windows se hace lo siguiente: 
5.	Se carga el gestor de arranque de Windows, denominado WinLoad o Windows Loader y usa la ruta específica BOOTMGR para montar la partición de arranque.
6.	Ahora, el gestor de arranque de Windows cargará dos archivos denominados NTOSKRNL.EXE y HAL.DLL para la gestión de hardware y el kernel.
7.	Después de eso, WinLoad lee los archivos del Registro de Windows y selecciona un perfil de hardware, cargando todos los drivers necesarios.
8.	En este punto se haría cargo del proceso el núcleo o kernel Windows NT. Y se iniciaría el archivo de inicio de sesión WINLOGON.EXE, para mostrar la pantalla de bienvenida de Windows.

### **•	Comenta algo que no sabías y que descubriste en esta actividad.**
Me gusto mucho la actividad, ya que la mayoría de las cosas sinceramente no las conocía muy bien, con este trabajo aprendí que el Hadware tiene elementos internos y externos, que el software tiene dos sistemas y la función principal de cada uno de ellos, también como se relacionan el Hardware y el Software, que es la velocidad del reloj y como funciona en los sistemas y lo que más me sorprendió fue todos los procesos que se emplean cuando “simplemente” voy a prender el equipo. 






![mapa metal](https://github.com/hacUPB/prog-2420-eval-u1-AnaSofiaH12/blob/main/imagenes/image.png)
Fuente: https://concepto.de/componentes-de-una-computadora/#ixzz8gqI8EoBW
