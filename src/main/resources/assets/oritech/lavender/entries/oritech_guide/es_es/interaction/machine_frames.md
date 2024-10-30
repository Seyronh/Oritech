```json
{
	"title": "Marcos de Máquinas",
	"icon": "oritech:machine_frame_block",
	"category": "oritech:interaction",
	"associated_items": [
		"oritech:machine_frame_block",
		"oritech:destroyer_block",
		"oritech:placer_block",
		"oritech:fertilizer_block"
	],
	"ordinal": 0
}
```

Los _[colocador de bloques](^oritech:interaction/block_placer), [destructor de bloques](^oritech:interaction/block_destroyer) y [fertilizador](^oritech:interaction/fertilizer)_ operan en una estructura de bastidor que se construye con marcos de máquina. El marco de máquina designa
el área en la que las máquinas operan. Debe ser rectangular y estar vacía en el interior.

Las máquinas siempre se dirigen a los bloques **debajo** del marco.

Cualquier número de máquinas puede operar en el mismo marco de máquina. Para hacerlo, simplemente coloque varias máquinas

;;;;;

en el marco. Las máquinas siempre iteran a través de todos los bloques en el área del marco.

Todas las máquinas que operan en marcos de máquina pueden usar la mayoría de los complementos.

El complemento de velocidad aumenta tanto la velocidad de movimiento como la de operación.

<block;oritech:machine_speed_addon>
