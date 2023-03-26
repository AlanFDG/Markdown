# RIRC-V 2023 hoy en dia
Se detallan los estudios previos (monografías, tesis, trabajos de ascenso universitario, etc.) de universidades locales, nacionales o internacionales en torno al tema del RISC-V en la actualidad.

## Historia
Durante el 2010, la Universidad de Berkeley se propuso dejar de depender de una ISA comercial para crear la suya propia, con ello nació el proyecto RISC-V, pensado para crear un conjunto de registros e instrucciones que no dependiera de una gran multinacional.

El proyecto duró cuatro años, y en 2015 crearon la RISC-V Foundation para controlar la evolución de la ISA que habían desarrollado inicialmente para los proyectos de su departamento de informática, la cual es la que dirige como evoluciona este estándar de hardware libre, especialmente la especificación base y ciertas extensiones.

> Uno de los términos que ha aparecido junto a conceptos como ARM, x86 y todo lo relacionado con los conjuntos de registros e instrucciones de una CPU, también conocida como ISA, es RISC-V. Pero ¿qué significan estas siglas y por qué están en la boca de mucha gente últimamente? Os vamos a sacar de dudas acerca de lo que significan y cómo afectan al mundo del hardware que utilizamos a diario.

#### El concepto de software libre se basa en los siguientes cuatro principios:
* La libertad de ejecutar el programa como se desee
* La libertad de estudiar el código fuente y modificarlo
* La libertad de redistribuir copias si así lo desea: los requisitos básicos
<p align="center">
  <img src="https://hardzone.es/app/uploads-hardzone.es/2020/10/Procesadores.jpg">
</p>

## Características de RISC-V
#### La ISA RISC-V tiene cuatro versiones base distintas:

* **RV32i:** 47 instrucciones en total, aritmética de enteros de 32 bits y direccionamiento también de 32 bits.
* **RV32E:** Igual que el anterior, pero con solo 16 registros al eliminar los registros del tipo contador. Está pensada para sistemas embebidos.
* **RV64i:** 59 instrucciones en total, es una evolución del RV32i que añade soporte cálculo de enteros y direccionamiento de 64 bits.
* **RV128i:** Es una extensión del RV64i, esta vez añadiendo instrucciones y direccionamiento de 128 bits.

### Por otro lado, se pueden añadir diferentes extensiones:

* **M:** 8 instrucciones adicionales que le otorgan al procesador RISC-V la capacidad de multiplicar y dividir enteros.
* **A:** 11 instrucciones para operaciones atómicas con la memoria.
* **F:** 26 instrucciones, soporte para coma flotante de 32 bits.
* **D:** 26 instrucciones, extensión de F que otorga soporte para coma flotante de 64 bits.
* **Q:** Extensión de D que otorga soporte para coma flotante de 128 bits.
* **C:** 46 instrucciones que permiten trabajar con datos comprimidos en enteros de 16 bits.

![](https://hardzone.es/app/uploads-hardzone.es/2020/11/Formato_Instrucciones_RISC-V.jpg)

>Esta características ha hecho además que RISC-V llegue a utilizarse en diferentes ámbitos distintos, especialmente en el mundo de los aceleradores o coprocesadores, gracias al hecho que los ingenieros pueden crear sus propias instrucciones, lo cual hace ideal a RISC-V para diferentes tipo de tareas.

## RISC-V como CPU
![](https://hardzone.es/app/uploads-hardzone.es/2020/11/Super_Computadura_Cientifica.jpg)
Aunque todos los programas hablen binario en realidad no hablan todos el mismo lenguaje y cada uno de ellos interpretará el código binario de una manera u otra. Es por ese motivo que un programa compilado para ARM no va a poder ejecutarse en x86 y viceversa. Pues bien, RISC-V es uno de esos lenguajes por lo que tiene sus propias normas en lo que a la forma en la que tienen que estar escritas las instrucciones de sus programas.

Si hablamos del software utilizado tanto en dispositivos PC como en dispositivos PostPC, nos encontramos que en el primer caso todas las aplicaciones de PC funcionan únicamente en procesadores con ISA x86, mientras que con el segundo caso ocurre lo mismo, pero con ARM. Esto hace que cualquier procesador con otra ISA que no sean esas dos, como es el caso de RISC-V, lo tenga muy difícil para poder hacerse un hueco en dichos mercados, por no decir completamente imposible.
> Pero hay mercados concretos en los que el hardware se utiliza para tareas concretas y por tanto muy especializadas.

# RISC-V: así es el chip del que todo el mundo habla
## RISC-V: la carrera por desarrollar un chip Open Source

![](https://www.muycomputerpro.com/wp-content/uploads/2020/09/SiFive-CPU-Feature.jpg)
> En pleno siglo XXI, los desarrolladores de hardware se siguen enfrentando al mismo problema: el coste. Tanto los chips x86 como los diseños de ARM suponen un coste no solo de fabricación, sino especialmente de licencias.

>En su núcleo del RISC-V actual hay un array de 32 registros que contienen el estado de funcionamiento del procesador, los datos que se operan en cada momento y la información de mantenimiento. Este array es lo suficientemente grande como para minimizar la necesidad de acceder a la memoria externa para muchas tareas básicas de la CPU, lo que reduce el uso de energía y aumenta la velocidad. En estos momentos los diseños de RISC-V se están ofreciendo en sus Versiones de 32, 64 y 128 bits.

> Pero para RISC-V como para GNU/Linux y el software libre al principio, esto no es más que una carrera de fondo que acaba de empezar. Una además, que si no se tuercen demasiado las cosas y cuenta con los apoyos adecuados (véase la UE, ahora que ARM ya no es europea o China, teniendo en cuenta su batalla comercial con Estados Unidos) puede llegar a ganar…porque RISC-V es inmune a los bloqueos políticos.

## Diferencias entre RISC y RISC-V
* **RISC:** Sus siglas en ingles "Reduced intruction set computing" y describe cualquier arquitectura informática que ejecute una gran cantidad de instrucciones simples.
* **RISC-V:** Es una arquitectura **RISC** específica y la quinta generación de **RISC** desarrollada en la **Universidad de California, Berkeley**.
 
<!-- Etiqueta para los enlaces -->
# Referencias
* ExplainingComputers. (19/03/2023). RISC-V 2023 Update: From Embedded Computing to Data Center & Desktop. Recuperado en: https://www.youtube.com/watch?v=AJVSZEX6d9M (Consultado el: 22/03/2023).

* Roca J. (09/11/2020). RISC-V, la ISA para procesadores sin una multinacional detrás. Recuperado en:  
https://hardzone.es/reportajes/que-es/risc-v/ (Consultado el: 22/03/2023).

* De Juana R. (20/10/2023). RISC-V: así es el chip del que todo el mundo habla. Recuperado en:
https://www.muycomputerpro.com/2020/09/28/risc-v-asi-es-el-chip-del-que-todo-el-mundo-habla(Consultado el: 24/03/2023).
