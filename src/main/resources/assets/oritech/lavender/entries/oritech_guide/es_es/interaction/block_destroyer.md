```json
{
	"title": "Destructor de bloques",
	"icon": "oritech:destroyer_block",
	"category": "oritech:interaction",
	"associated_items": ["oritech:destroyer_block"],
	"ordinal": 3
}
```

<block;oritech:destroyer_block[machine_assembled=true]>

El destructor de bloques se utiliza para, como ya habrás adivinado, destruir bloques. Es un [multi-bloque](^oritech:processing/multiblocks) que opera en una [estructura de máquina](^oritech:interaction:machine_frames), y tiene como objetivo la capa de bloques directamente debajo de la estructura.

;;;;;

El tiempo y la energía necesarios para romper un bloque se basan en la dureza del bloque. El destructor de bloques intenta destruir todos los bloques que se encuentren debajo. Para permitir el uso para granjas, se puede instalar el complemento de filtro de cultivos.
Esto hará que el destructor de bloques omita todos los cultivos que no estén listos.

<block;oritech:crop_filter_addon>

;;;;;

Al agregar complementos de cantera, el destructor de bloques también se puede utilizar como una cantera. Cada complemento de cantera multiplica el rango por 8.

Esto significa que un complemento le da un rango de 8, 2 complementos le dan un rango de 64 y 3 complementos le dan un rango de 512.

<block;oritech:quarry_addon>
