```json
{
	"title": "Complementos",
	"icon": "oritech:machine_extender",
	"category": "oritech:processing",
	"associated_items": [
		"oritech:machine_extender",
		"oritech:capacitor_addon_extender",
		"oritech:machine_speed_addon",
		"oritech:machine_efficiency_addon",
		"oritech:machine_capacitor_addon",
		"oritech:machine_fluid_addon",
		"oritech:machine_yield_addon",
		"oritech:crop_filter_addon",
		"oritech:quarry_addon",
		"oritech:machine_acceptor_addon",
		"oritech:machine_inventory_proxy_addon"
	],
	"ordinal": 2
}
```

Para mejorar las máquinas en oritech, se utilizan complementos. Son bloques que necesitan ser conectados a la máquina en sí o a un extensor de mquina conectado. Los complementos pueden hacer una variedad de cosas, como aumentar la velocidad, la eficiencia energética, dar acceso a ranuras de inventario específicas y mucho más.

;;;;;

Las máquinas solo pueden aceptar complementos en posiciones específicas. Para ver estas, revise la página de la interfaz de usuario "Complementos" o busque estos marcadores en la máquina:
![marcador_máquina](oritech:textures/book/addon_marker.png,fit)

;;;;;

Los complementos se activarán cuando se hace clic derecho en la mquina. Las partes rosadas de un complemento se vuelven azules cuando está en uso. Para ampliar el número de ranuras de complementos disponibles, puedes usar extendores de máquina. Estos son complementos especficos que no influyen directamente en la máquina, pero permiten que los complementos se coloquen en ellos, lo que contara hacia la máquina a la que están conectados.

El número máximo de capas de extendores de máquina que puedes

;;;;;

usar depende de la calidad de la máquina. Si tienes una máquina con una calidad de núcleo de 1, no puedes usar ningún extensor. Cada extensor adicional que
uses **a través** de otro extensor requiere un aumento en la calidad de núcleo de 1.

La calidad de núcleo nunca cuenta directamente la cantidad de extendores de máquina que tienes activos. En su lugar, cuenta a través de cuantos
extensores un complemento tiene que pasar para estar conectado a la mquina. Si este número es mayor que la calidad de núcleo, el complemento

;;;;;

no estará conectado. Vea esta imagen para una pequeña demostración:
![complementos_máquinas](oritech:textures/book/extenders.png,fit)

;;;;;

Como se mencionó anteriormente, solo se cuenta el número de extensores entre una máquina y un complemento. Esto significa que puedes ramificar los extensores y todo funcionará:
![ramificación_complementos](oritech:textures/book/addon_branching.png,fit)
