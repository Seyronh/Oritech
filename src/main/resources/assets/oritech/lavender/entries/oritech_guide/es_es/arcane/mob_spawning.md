```json
{
	"title": "Generación de mobs",
	"icon": "oritech:spawner_controller_block",
	"category": "oritech:arcane",
	"associated_items": [
		"oritech:spawner_controller_block",
		"oritech:spawner_cage_block"
	]
}
```

<block;oritech:spawner_controller_block>

Los mobs pueden generarse combinando un controlador de generador con una jaula de generador debajo. Dependiendo del tamaño del ente generado, se requiere un tamaño de jaula diferente.
El tipo de mob generado se determina por

;;;;;

el primer mob que camine sobre el controlador, y solo puede ser cambiado reemplazando el controlador. El controlador recogerá
almas y las usara para generar el mob configurado. El costo de almas depende de la vida del mob generado. Solo generara mobs si hay una superficie vacía disponible cerca. Cuando se configura un tipo de mob (o al hacer clic derecho si no es válido), el generador destacara qué tamaño de jaula de generador se requiere debajo. También puedes hacer clic derecho en el generador para

;;;;;

obtener algúna información sobre el estado operativo actual.
