```json
{
	"title": "Fluidos",
	"icon": "oritech:fluid_pipe",
	"category": "oritech:logistics",
	"associated_items": ["oritech:fluid_pipe", "oritech:small_tank_block"]
}
```

Las tuberías de fluidos se comportan de manera similar a tuberías de objetos. Sin embargo, tambien tienen un almacenamiento interno pequeño
(en cada conexión). Como las tuberías de objetos, cuando se configuran para extraer, extraen de todos los bloques vecinos. Sin embargo, a diferencia de las tuberías de objetos, los bloques también pueden empujar fluidos hacia una tubería, que la tubería a su vez mueve hacia el siguiente almacenamiento de fluidos disponible.

;;;;;

Para almacenar fluidos, puedes utilizar un depósito de fluidos. Los depósitos de fluidos pequeños almacenan hasta _256_ cubos de fluidos.
Cuando se rompe, el pequeño depósito mantiene todos sus contenidos en el nbt del objeto. La salida de un comparador refleja el estado de llenado del depósito. Los depósitos apilados permiten que el fluido fluya hacia abajo de forma autom tica.

<block;oritech:small_tank_block>
