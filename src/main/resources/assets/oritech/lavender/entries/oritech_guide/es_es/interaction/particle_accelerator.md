```json
{
	"title": "Acelerador de Partículas",
	"icon": "oritech:accelerator_ring",
	"category": "oritech:interaction",
	"associated_items": [
		"oritech:accelerator_ring",
		"oritech:accelerator_motor",
		"oritech:accelerator_controller",
		"oritech:accelerator_sensor",
		"oritech:black_hole_block"
	],
	"ordinal": 6
}
```

<block;oritech:accelerator_ring>

El acelerador de partículas se puede utilizar para, como habrás adivinado, acelerar partículas. La partícula comienza desde el bloque del acelerador de partículas. En él, puedes insertar cualquier elemento que se usará como partícula. Una guía recta

;;;;;

debe colocarse justo detrás del controlador, mirando hacia el lado. Los visuales deben coincidir.

Una vez insertada, la partícula viajará a lo largo de una ruta definida con los anillos guía. Se pueden hacer clic derecho para agregar un giro de 45 grados en un lado. Otro anillo guía necesita estar en el camino de la partícula según lo definido por los anillos guía. Dependiendo de la velocidad, la distancia permitida entre los bloques guía aumenta.

;;;;;

La distancia máxima se calcula con la siguiente fórmula:

> clamp(sqrt(speed), 2, 10)

Esto básicamente significa que a mayor velocidad, la distancia entre los bloques guía puede ser mayor.

;;;;;

**Interruptores de Redstone**

Cuando se da una señal de redstone a un bloque guía no recto, se convertirá en un bloque interruptor.
Cuando está encendido, guiará las partículas en línea recta, y cuando está apagado, las dirigirá en la dirección curva original. Sin embargo, una partícula también puede entrar desde la 'otra' dirección. Esto se visualiza con el tubo de vidrio rojo más pequeño. Seguirá el camino del tubo blanco y puede entrar desde ambos, el tubo rojo y el blanco.

;;;;;

A velocidades más altas, la partícula ya no podrá tomar giros demasiado cerrados. Si el último giro completo de 90 grados está demasiado cerca detrás, saldrá del camino guiado y en su lugar se disparará hacia el mundo. Si la distancia entre los bloques guía es demasiado grande, o no se encuentra el siguiente guía, también se disparará hacia el mundo. La distancia mínima entre giros se calcula de esta manera:

> sqrt(speed) / 3

;;;;;
**Interacciones**

Las entidades golpeadas por la partícula recibirán daño basado en la velocidad actual de la partícula. Al salir del camino guiado, también dañará a las entidades en su camino y destruirá bloques hasta que no quede más momento disponible. Cuando dos partículas colisionan (desde diferentes controladores), pueden crear nuevos elementos.

Cuando pasa a través de un motor de acelerador de partículas, la partícula se acelerará en 1 m/s. Esto requiere que el motor

;;;;;

esté activado. El requisito de potencia aumenta con la velocidad.

Tanto los motores de partículas como los sensores pueden utilizarse como guías rectas.

;;;;;

**Sensores de Velocidad**

La velocidad de las partículas se puede medir con un sensor de partículas. Luego, se puede usar un comparador para obtener una señal de redstone basada en la velocidad de las partículas.
La siguiente tabla muestra la velocidad requerida para cada nivel de redstone:

1. 0
2. 10
3. 50
4. 75
5. 100

;;;;;

6. 150
7. 250
8. 500
9. 750
10. 1000
11. 2500
12. 5000
13. 7500
14. 10000
15. 15000

;;;;;

**Diseño del Acelerador**

Los aceleradores de partículas se pueden construir de varias maneras, dependiendo de sus objetivos. Puedes construir una línea recta de motores para simplemente disparar las partículas hacia algo. Sin embargo,
si deseas alcanzar velocidades más altas, un diseño circular suele ser mucho más eficiente. Cuando intentas alcanzar ciertos elementos, pueden ser necesarios anillos muy grandes. Como las partículas lentas requieren anillos guía cercanos entre sí, a menudo tiene sentido empezar la

;;;;;

partícula en un anillo pequeño y luego utilizar redstone para llevarla a un anillo más grande.

Pueden ser necesarios varios anillos para algunos casos.

;;;;;

**Incursiones Dimensionales**

Cuando ciertos elementos chocan con demasiada energía, se rasga un agujero en el espacio-tiempo, creando una pequeña incursión dimensional. Dado que la cantidad de energía requerida para lograr esto es inmensa, se sabe muy poco sobre estas incursiones y lo que las desencadena. Los investigadores han notado que colisionar cargas de fuego con una energía de colisión superior a 5000J parece acercar el Nether. Las perlas de Ender y más de 10000J parecen

;;;;;

se dice que están intentando lo mismo con la dimensión del Fin.

Hay rumores de científicos que intentan bombardear una de estas incursiones con velocidades que eclipsan los valores más altos medidos. Sin embargo, nadie vivió para contarlo.
