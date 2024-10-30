```json
{
	"title": "Transportes de objetos",
	"icon": "oritech:item_filter_block",
	"category": "oritech:logistics",
	"associated_items": ["oritech:item_pipe", "oritech:item_filter_block"]
}
```

Oritech incluye tuberías de transporte de objetos y bloques de filtros de objetos para cubrir tus necesidades logísticas de objetos. Las tuberías de objetos se conectan a sí mismas y a todos los inventarios colindantes.

;;;;;

A diferencia de otras tuberías, las tuberías de objetos no tienen un inventario. Esto significa que otros bloques (como una tolva) no pueden insertar objetos en la red de tuberías por sí solos. En su lugar, una tubería de objetos se puede configurar para extraer de un inventario cercano. Para hacerlo, simplemente haz clic derecho en un bloque de tubería (que esté conectado a algo). Si tienes múltiples inventarios conectados al mismo bloque de tubería, notarás que todas las conexiones cambian al modo de extracción. Este es una

;;;;;

limitación actual de las tuberías de Oritech. Si configurara un bloque de tubería para extraer, intentará extraer
de todos los bloques que estén conectados a este bloque de tubería. Así que para transportar realmente algo, necesitarás una red de tuberías que consista de al menos 2 bloques.

Los objetos extraídos se pondrán en el **inventario más cercano** disponible más abajo en la red.

;;;;;

El rango máximo de transferencia es de 64 bloques. Cualquier red más larga que eso necesita ser dividida.

Las tuberías siempre extraerán del primer espacio no vacío en un inventario. Si el objeto no se puede colocar en un inventario de la red de tuberías, bloqueará la tubería para que no extraiga de ese inventario.

;;;;;

**Filtros de objetos**
<block;oritech:item_filter_block>
Para filtrar qué objetos van a dónde, puedes utilizar filtros de objetos. Son bloques que puedes colocar al lado del inventario objetivo. Tiene 5 lados de entrada,
y siempre sale al lado que está mirando.
Acepta objetos que coinciden con el filtro establecido mediante la interfaz de usuario, y los devuelve automáticamente al inventario objetivo.

;;;;;

Sin embargo, no extraerá automáticamente objetos de los inventarios vecinos.
