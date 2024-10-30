```json
{
	"title": "Redstone",
	"icon": "oritech:energy_pipe",
	"category": "oritech:interaction",
	"associated_items": ["oritech:machine_redstone_addon", "minecraft:redstone"]
}
```

Algunas máquinas de Oritech pueden interactuar directamente con la redstone, como el tanque portátil y el almacenamiento de energía portátil. El contenido de los tanques portátiles se puede medir utilizando un comparador, y la salida de los almacenamientos de energía portátiles se puede desactivar con una señal de redstone. Para todos los demás bloques, se requiere un "Redstone Addon Controller".

;;;;;

El controlador de addon de redstone se puede adjuntar como cualquier otro addon y se puede configurar a través de la interfaz de usuario. Cuando está configurado, los datos se pueden leer utilizando un comparador. La señal del comparador se emitirá desde el addon, no desde la máquina en sí. La máquina también se puede desactivar con una señal de redstone al addon.
