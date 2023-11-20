[grupo tice](https://www.grupo-tice.com/funcion-de-parada-de-emergencia-modulo-de-seguridad/)

¿Sabes lo que es la función de parada de emergencia?
La función de parada de emergencia se debe diseñar de manera que después de actuar sobre el órgano de accionamiento de parada de emergencia, se detengan los movimientos peligrosos de la máquina. Estamos dentro del ámbito de la Seguridad Industrial y en este campo en Grupo TICE somos expertos. De acuerdo con esto, lo primero que se debe hacer es determinar un correcto nivel de prestaciones de parada de emergencia, el cual quedará definido en función de la gravedad de una hipotética lesión (y sus consecuencias) y la frecuencia con la que se puede dar dicha situación peligrosa, entre otras variables. 

Por lo tanto, y como decimos, un eventual accidente puede provocar un daño personal muy severo, con resultado incluso de muerte, por lo que es inasumible que la activación de una parada de emergencia falle.

Es por esto que, en ocasiones, no baste con el simple corte del/los relé/s que accionan la máquina. 

Por ejemplo, un relé estándar puede fallar por diferentes causas, provocando la fijación de los contactos e impidiendo que abra el circuito en caso de una emergencia. 

![dibujo parada emergencia](https://www.grupo-tice.com/wp-content/uploads/2022/06/image2-600x443.png)

## conexionado del modulo
En primer lugar, nos detenemos en el conexionado de la seta. Si observamos con atención, vemos que el fabricante nos exige que la seta debe tener de 4 puntos de conexión NC (normalmente cerrado) que deberán estar ligados entre sí, o lo que es lo mismo, ambos deberán abrirse al mismo tiempo en el momento del accionamiento, de lo contrario, el módulo no cerrará alguno de los contactos que están puestos en serie (K1’’ y K2’’).

Otro dato que llama la atención es que el fabricante utiliza un pulsador con bloqueo.

Veamos cómo se comporta el circuito en el momento que accionamos la parada de emergencia y veremos si es necesario que la seta permanezca bloqueada manteniendo el circuito abierto hasta que se desbloqueé.
![modulo omrom](https://www.grupo-tice.com/wp-content/uploads/2022/06/image4-600x517.png)
Mientras S1 no se accione, las bobinas K1 y K2 (bobina redundante) se mantienen activas (en corto) cerrando los contactos K1’’ y K2’’ y manteniendo tensión en KM1 y KM2.
También se quedan en abierto los contactos KM1’ y KM2’ en el bucle de realimentación. Note que están en serie con S2 (rearme). Luego veremos en profundidad su comportamiento.

Observe que los diodos que están en paralelo junto a las bobinas K1 y K2 han desaparecido. Se ha hecho así para facilitar su interpretación. El diodo permanece en corte, por lo que al diodo Zener tampoco le llega corriente. Los fotodiodos (leds) se quedan polarizados en directa y permanecen iluminados.

Cuando pulsamos la seta de emergencia, el circuito que alimenta las bobinas de K1 y K2 entra en corte y no circula corriente (recuerde que son normalmente abierto, su estado natural si no se les aplica tensión), al igual que el resto de contactos, que vuelven también a su estado natural.

Aunque desenclaváramos y volviera a entrar en contacto S1, devolviendo la continuidad al circuito, las bobina K1 no se activaría, por lo que el contacto K1’’ tampoco. La explicación está en el transistor puesto en serie (a) que entra en conducción (dado que el circuito de control está alimentado por K2’) para que la corriente tome ese camino de “puente” (la corriente toma el camino más fácil), evitando la alimentación de ésta.

Se deberá pulsar el rearme (poniendo tensión en el bucle de realimentación provocando que K1’, K2’, KM1’ y KM2’ se abran) para que al BJT no le llegue corriente de base, entre en corte y devuelva la tensión a K1. A partir de ese momento, los contactos NA/NC vuelven a su estado en tensión (cerrándose y abriéndose respectivamente) y dejando el circuito listo para que un botón de “puesta en marcha” cierre el circuito, mande tensión a los contactos auxiliares de KM1 y KM2 y ponga en marcha el motor.

---

## articulo paradas de emergencia

[previpedia](https://previpedia.es/index.php/Parada_de_emergencia)

![boton parada de emergencia](https://upload.wikimedia.org/wikipedia/commons/f/f9/Not-Aus_Bet%C3%A4tiger.jpg)

## Requisitos de la función de parada de emergencia

Figura 1. Símbolo para la parada de emergencia
Debe estar disponible y ser operativa permanentemente.
Debe ser prioritaria a todas las demás funciones y operaciones de la máquina.
Estará diseñada de manera que la decisión de activarla no requiera del trabajador ninguna reflexión acerca de los efectos resultantes.
No debe perjudicar a ninguno de los medios diseñados para liberar a las personas atrapadas.
La activación del dispositivo de parada de emergencia producirá la detención de operaciones y movimientos peligrosos de la máquina sin generar peligros suplementarios y sin necesidad de intervención suplementaria de ninguna persona.
Ninguna orden de puesta en marcha (voluntaria, involuntaria o inesperada) será efectiva en las operaciones que hayan sido detenidas mediante la parada de emergencia hasta que dicha función haya sido rearmada manualmente.
Si los dispositivos de parada de emergencia pueden ser desconectados o desactivados de algún modo (p.e., mediante una consignación parcial), hay que tomar las precauciones necesarias para evitar la confusión entre dispositivos activos e inactivos.
La función de parada de emergencia no debe perjudicar la eficacia de los dispositivos de protección de la máquina ni de ningún dispositivo que desempeñe funciones de seguridad.
Cuando se proporcionan etiquetas, se debe usar el símbolo mostrado en la Figura 1.

## Categorías de paradas de emergencia
* Categoría 0: la parada se produce por la interrupción inmediata de la alimentación de energía del (de los) accionador (es), o bien por desconexión mecánica (desembrague) entre los elementos peligrosos y su (s) accionador (es) y, si es necesario, frenado.
* Categoría 1: los accionadores se mantienen alimentados hasta que la máquina está detenida.
* Categoría 2: conforme a la norma UNE–EN 60204–1). Se denomina “parada operacional” y se aplica, por ejemplo, cuando la presencia de energía es necesaria para mantener elementos en posición, como sucede en el caso de los robots, o de máquinas–herramienta con control numérico.

---
## PARADA DE EMERGENCIA
Pero vayamos al producto en sí: la mayoría de la gente probablemente ha visto alguna vez una parada de emergencia o una desconexión de emergencia. Aún más probablemente habrán prescindido de los términos interruptor y pulsador en el lenguaje cotidiano. Al fin y al cabo, se suele hablar de parada o desconexión de emergencia. Ambos términos se utilizan a menudo como sinónimos. El que esto sea correcto o no lo aclararemos más adelante. Sin embargo, lo que es absolutamente seguro es el tipo de conmutación real del interruptor de enclavamiento. Así pues, el mecanismo funciona de tal manera que el operario pulsa el interruptor para enclavarlo. Esto cierra un circuito y se realiza la acción deseada. Estos interruptores son obligatorios para las instalaciones y máquinas de acuerdo con la norma industrial alemana EN ISO 13850, de la que hablaremos con más detalle más adelante. En el entorno industrial, la seguridad de los empleados puede garantizarse de este modo.

Parada de emergencia, detención de emergencia o desconexión de emergencia

Como se ha mencionado anteriormente, toda máquina necesita al menos uno, si no varios, dispositivos de mando de parada de emergencia. Ahora surge inevitablemente la pregunta de si esto implica también los actuadores de parada de emergencia. Para ello consultamos la Directiva de Máquinas 2006/42/CE, más concretamente el Anexo I, Apartado 1.2.4.3 «Parada en caso de emergencia». Allí sólo se menciona la parada de emergencia para evitar un peligro inminente. Por lo tanto, debe haber una diferencia entre parada de emergencia, desconexión de emergencia y detención de emergencia. Y la hay. En resumen: los actuadores de parada de emergencia detienen la máquina mientras que la desconexión de emergencia corta el suministro de energía. ¿Y los actuadores de detención de emergencia? Las opiniones difieren en este punto. No existe una definición clara en el sector. A veces, la detención de emergencia se utiliza como término genérico para los otros dos tipos, y a veces como sinónimo de uno de los dos. Por este motivo, no utilizaremos este término en adelante para evitar cualquier confusión. Diversas normas y la Directiva de Máquinas ya mencionada ofrecen más detalles sobre la distinción.

EN 13850 y EN 60204 – categorías de detención 

La norma EN ISO 13850 es una norma armonizada relativa a la seguridad de las máquinas y en particular proporciona directrices de configuración de paradas de emergencia en relación a las máquinas correspondientes. Junto con la norma EN 60204, es uno de los principios más importantes en materia de actuadores de emergencia. La norma EN 13850 define, entre otras cosas, las distintas categorías de detención.

Categoría de detención 0  

Cuando se acciona, el suministro de energía a los elementos de accionamiento se desconecta inmediatamente, es decir, el actuador actúa como un contacto de ruptura del circuito. La desconexión de emergencia se encuentra en esta categoría. Por lo tanto, la máquina no se pone primero en estado de seguridad, sino que sigue funcionando mecánicamente durante un tiempo determinado. Por lo tanto, sigue existiendo cierto peligro potencial incluso después del accionamiento. 

Categoría de detención 1  

El actuador, en este caso la parada de emergencia de la máquina, pone primero la máquina o la instalación en un estado seguro y no peligroso. Sólo entonces se desconecta el suministro de energía en la dirección de los elementos de accionamiento. La función de parada de emergencia pertenece a esta categoría.

Categoría de detención 2 

Aquí, la categoría 0 se invierte, por así decirlo: el suministro de energía se mantiene, pero la máquina se coloca en un estado seguro. Este tipo de detención no está permitido para los actuadores de parada de emergencia y, por lo tanto, no se utiliza.

En el anexo Seguridad de las máquinas de la norma EN 60204-1, en el apartado Equipo eléctrico de las máquinas, Parte 1, encontramos otras notas sobre la diferencia entre los actuadores: la reacción tras el accionamiento del interruptor es decisiva. Por un lado está la parada de emergencia, que detiene los movimientos de la máquina con peligro potencial en caso de emergencia; por otro lado, está la desconexión de emergencia, que desconecta la energía de todo el sistema en caso de emergencia. La Directiva de Máquinas 2006/42/CE añade al respecto que los actuadores de parada de emergencia deben detener el proceso peligroso lo más rápidamente posible y, al mismo tiempo, activar determinados movimientos de seguridad en ciertos casos. El que hayamos de utilizar actuadores de parada de emergencia o interruptores de parada de emergencia para la seguridad de la maquinaria tiene una respuesta clara: la parada de emergencia suele ser la opción más segura.

Rotulación y selección de colores para los dispositivos de mando de emergencia

De acuerdo con la norma DIN EN ISO 13850 Seguridad de las máquinas, principios de configuración de paradas de emergencia, existen especificaciones claras en cuanto a la rotulación y los colores de los dispositivos de mando de parada de emergencia. Deben ser claramente reconocibles, fácilmente visibles y rápidamente localizables, así lo subraya la Directiva de Máquinas 2006/42/CE. Por esta razón, al elemento u órgano de accionamiento siempre se le asigna el color rojo de seguridad y al fondo el amarillo para el contraste. Hay que evitar las rotulaciones, ya que, según la evaluación de riesgos, debe actuarse rápidamente en caso de emergencia y la información adicional pudiera entorpecer o impedir el acto reflejo, lo que puede suponer un peligro para el hombre y la máquina.


[paradas de emergencia 2](https://www.rafi-group.com/es/parada-de-emergencia/)