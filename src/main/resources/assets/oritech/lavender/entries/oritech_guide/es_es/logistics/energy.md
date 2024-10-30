```json
{
	"title": "Energía",
	"icon": "oritech:energy_pipe",
	"category": "oritech:logistics",
	"associated_items": [
		"oritech:energy_pipe",
		"oritech:small_storage_block",
		"oritech:large_storage_block"
	]
}
```

Oritech utiliza {gold}**RF**{} para alimentar todas sus máquinas. Utiliza la API Reborn Energy para hacerlo. Esto significa que Oritech es compatible con todos los mods que usan el sistema de energía de Tech Reborn, que actualmente incluye básicamente todos los mods de energía de fabric.

Solo hay 1 nivel de cable disponible, capaz de transferir hasta {gold}10k RF/t{}.

;;;;;

Los generadores siempre generarán energía, y todas las demás máquinas aceptan energía desde todos los lados (y no la volverán a emitir). Los cables en sí mismos almacenan hasta {gold}10k RF{} en cada conexión de máquina, si no pueden emitir la energía.

;;;;;

Para almacenar y acumular energía, puedes usar bloques de almacenamiento de energía. Están disponibles en 2 tamaños y se pueden expandir masivamente usando complementos. Los bloques de almacenamiento de energía aceptan energía desde todos los lados con un puerto {green}verde{}, y solo pueden emitir al único puerto {red}rojo{}. Una señal de redstone desactivará toda la salida de energía.

<block;oritech:small_storage_block>

;;;;;

La energía también se puede transferir de forma inalámbrica utilizando un láser endérico. Ver [Láser Endérico](^oritech:interaction/enderic_laser)

![Láser Endérico](oritech:textures/book/enderic_laser.png,fit)
