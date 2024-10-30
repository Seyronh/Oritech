```json
{
	"title": "Láser  endérico",
	"icon": "oritech:laser_arm_block",
	"category": "oritech:interaction",
	"associated_items": [
		"oritech:laser_arm_block",
		"oritech:fluxite",
		"minecraft:amethyst_cluster",
		"minecraft:amethyst_shard"
	],
	"ordinal": 6
}
```

![láser endérico](oritech:textures/book/enderic_laser.png,fit)

El láser endérico utiliza

;;;;;
grandes cantidades de energía para disparar un haz láser en una dirección específica.

En la mayoría de los casos, esto resulta en la destrucción del bloque.
Los bloques caídos se colocan en el inventario. Cualquier bloque que no quepa en el inventario se perderá, por lo que es posible que desees utilizar un [tubo de objetos](^oritech:logistics/item_transport) para seguir recibiendo objetos.

;;;;;

**Control**

Para establecer la dirección objetivo del láser, selecciona un objetivo con el objeto [designador de objetivos](^oritech:tools/target_designator). Luego, haz shift+clic derecho en el bloque **inferior** del láser para asignar el objetivo. El láser seguirá disparando en la dirección objetivo siempre que haya algo a lo que apuntar.

_Nota que solo estás estableciendo la dirección objetivo. Esto significa que el láser también destruirá bloques antes y después del objetivo_.
Una señal de redstone desactiva el láser.

El alcance máximo es 64.

;;;;;

**Recolección de fluxita**

Las enormes cantidades de energía del láser endérico causan que los bloques de amatista crezcan y se transformen en fluxita cuando son destruidos.
<block;minecraft:amethyst_cluster>

También aceleran el crecimiento de amatistas cuando se apuntan directamente a la amatista en crecimiento.

;;;;;

**Transferencia de energía**

Cuando el láser endérico está apuntando a un bloque que puede almacenar energía (por ejemplo, cualquier máquina), llenará el almacenamiento de energía de la máquina.
El láser ignora todos los límites de entrada y salida, y puede llenar el almacenamiento de energía de máquinas que no aceptan energía de cables directamente.

;;;;;

**Complemento de Cazador**

Cuando el láser endérico tiene un complemento de cazador, apuntará a mobs en lugar de bloques. Las mejoras de complementos siguen funcionando al cazar mobs: el complemento de rendimiento hará que los mobs suelten más botín, más complementos cazadores extenderán el rango de escaneo objetivo, los complementos de velocidad aumentarán el daño causado (y reducirán la eficiencia energética), y el filtro de cultivos evitará matar animales bebés.

;;;;;

Si llevas puesta una [exo coraza](^oritech:tools/exo_armor) entonces el láser endérico te la recargará.

**Objetivos de Cazador**

Utiliza un [designador de objetivos](^oritech:tools/target_designator) en el láser endérico para cambiar los modos de objetivo. El predeterminado es atacar monstruos únicamente, pero también puedes hacer que ataque animales o incluso a mercaderes errantes. Ten cuidado al usarlo y al establecer el objetivo, ya que puedes acabar matando cosas que no deseas matar.

;;;;;

**Más detalles**

El haz del láser se dirige a cualquier bloque, pero pasa a través del vidrio (y amatistas no crecidas). Los complementos de cantera aumentarán el ancho del área excavada.

El láser en sí mismo solo tiene una ranura de complementos disponible en la parte inferior. Los complementos solo afectarán a la velocidad y eficiencia de la rotura de bloques, la transferencia de energía solo se puede beneficiar de mejoras de velocidad.

Un bloque objetivo parará el láser de ir más allá, mientras se esta destruyendo.
