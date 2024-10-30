```json
{
	"title": "Energía de Vapor",
	"icon": "oritech:steam_boiler_addon",
	"category": "oritech:processing",
	"associated_items": [
		"oritech:steam_engine_block",
		"oritech:steam_boiler_addon"
	]
}
```

<block;oritech:steam_boiler_addon>
Todos los generadores (excepto el generador básico) pueden ser actualizados para producir vapor. Para hacerlo, agrega un accesorio de caldera de vapor al generador. Cuando se agrega, la máquina no producirá RF directamente.

;;;;;

En su lugar, producirá vapor a una tasa de 2:1. Para producir vapor, se consumirá agua. Los líquidos de agua y vapor pueden ser bombeados dentro y fuera directamente desde el accesorio, pero no desde la máquina en sí misma.

Para usar el vapor, se puede utilizar un motor de vapor para producir RF. El motor de vapor toma vapor como entrada y produce agua como salida. Sin embargo, durante el proceso se perderá alrededor del 20% del agua, así que se necesita un suministro constante de agua para los generadores.

;;;;;

Se pueden encadenar múltiples motores de vapor. Compartirán el almacenamiento de energía, el tanque de agua y el tanque de vapor desde el primer motor en la línea. Trabajan cooperativamente.
La velocidad de un motor de vapor varía en función del vapor almacenado. Más vapor se traducir en más presión, lo que hará que funcione a mayor velocidad.
La velocidad se escala linealmente en función del porcentaje de llenado del tano de vapor, con un múltiplo de 10 cuando el tanque está lleno.

;;;;;

Sin embargo, la eficiencia del motor varía en función de la velocidad. Una mayor eficiencia se traducir en más RF por unidad de vapor producida. La eficiencia de la máquina es mayor cuando opera a una velocidad de alrededor del 700%. Cualquier velocidad menor o mayor que esa resultará en un rendimiento menos ideal. La energía se emitirá desde las ranuras rojas de la máquina. Los puertos de fluidos se marcarán azules.
