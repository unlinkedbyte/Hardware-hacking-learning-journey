## Hardware hacking learning journey

¡Buenas!

Este será un repositorio personal dedicado al aprendizaje y documentación de hardware hacking.

El objetivo será documentar el proceso de aprendizaje mediante objetivos reales, pasando de dispositivos sencillos para practicar reconocimiento, soldadura, desoldadura y extracción de memorias, hasta sistemas embebidos en los que sea posible obtener el firmware y analizar posteriormente sus binarios.

La parte del análisis de firmware se hará en el repositorio de reversing en el apartado dedicado, llamado firmware-analysis al que enlazaré cuando toque. En este repositorio dejaré, aparte de lo mencionado, los métodos una vez las vías comunes no sirvan (ej: glitching, fault injection, side channel attacks).

*nota1: actualmente estoy aprendiendo MIPS para los 4 routers que tengo en los targets actuales, por lo que quizá todo avance algo más lento. Además, tengo que acabar un análisis de firmware que tengo pendiente todavía en el repo de reversing, que lo empecé antes de tener el laboratorio montado.*

*nota2: si estás empezando y quieres ver lo que contiene el laboratorio, está casi todo listado en el writeup de la impresora (tienes el enlace al final), a excepción del bus pirate v6 que está en camino.*

### Targets actuales

* **Router Huawei hg532c versión 1**
* **Gateway DOCSIS 3.0 CG6640E**
* **Router Huawei hg556a (HW: HG56BZRB VER.A)**
* **Router Inteno DG200A-AC + ONT Zhone ZNID-GPON-2301**
* **3 móviles y una tablet** - 2 xiaomi, un samsung y la tablet android. Los 4 diría que son de entre el 2010 y 2020 como mucho, y de uno de los teléfonos tengo la placa base pero el teléfono estaba bastante roto, por lo que quizá al final no sea posible. Este último sería el más moderno de los objetivos aquí mencionados, veremos.
* **Una televisión que todavía está pendiente de confirmar si es smart** - Si al final no lo es, lo quitaré de aquí.
* **Un target que en el primer writeup menciono como sorpresa**

### Objetivos de práctica

Estos no serán objetivos de hardware hacking pero podrían ser útiles para adquirir experiencia con hardware, interfaces, componentes, buses y técnicas de extracción.

* **Ratón logitech Bluetooth**
* **Mando consola**
* **Altavoz Bluetooth**
* **D-Link DES-1005d** - Switch Ethernet
* **Una torre de ordenador HP con windows XP** - Del 2003 aproximadamente.
* **Lector DVD de cámara** - Con sus añitos ya también.

### Writeups

Aquí irán los writeups de cada sesión que decida subir:
* **[Primer writeup impresora HP 2006](./sesion-01-impresora)** - El primer objetivo de prácticas donde he practicado reconocimiento y volcado de la EEPROM
