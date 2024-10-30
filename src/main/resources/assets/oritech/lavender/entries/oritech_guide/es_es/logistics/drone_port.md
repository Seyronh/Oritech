```json
{
	"title": "Puerto de Drones",
	"icon": "oritech:drone_port_block",
	"category": "oritech:logistics"
}
```

<block;oritech:drone_port_block>

El puerto de drones te permite transportar objetos a grandes distancias usando drones voladores. Requiere que un puerto de drones esté construido y alimentado con energía tanto en la posición de despegue como en la de aterrizaje.

;;;;;

Una vez construido, necesitas asignar el puerto objetivo usando un objeto designador de objetivos. Vínculalo al puerto de drones objetivo haciendo shift+clic derecho en el puerto objetivo. Luego, en el puerto desde el que deseas enviar objetos, abre la interfaz de usuario y coloca el designador en la ranura especial para objetos.

El puerto objetivo necesita estar al menos a 50 bloques de distancia. El área en la que se encuentra también necesita estar cargada en el chunk.

;;;;;

Un puerto de drones solo puede enviar objetos a un puerto objetivo específico, pero un puerto puede recibir objetos de múltiples puertos. Sin embargo, cada dron tarda unos segundos en aterrizar, por lo que si los objetos llegan con demasiada frecuencia, un puerto receptor puede sobrecargarse cuando es objetivo de múltiples puertos.

El tiempo que tarda en entregar objetos es constante, sin importar cuán lejos tenga que volar el dron. Sin embargo, el costo de energía aumenta con la distancia.

;;;;;

La raíz cuadrada de la distancia se utiliza en el cálculo del uso de energía.
