Decision Plan v5.12.0
- Tags independientes para clasificar ítems en el momento en que son otorgados.
- ABM de tags: crear, renombrar y eliminar.
- Cada asignación de ítem desde una opción de decisión o Sí/No/Subir de una Idea guarda itemId + tagId.
- Un mismo ítem puede otorgarse con tags distintos en contextos distintos.
- Pantallas de ítems agrupan por el tag del otorgamiento; sin tag se muestra como “Sin tag”.
- Migración conservadora desde v5.11.0: los antiguos Tipos se convierten en tags y se aplican a asignaciones existentes.
- Eliminar un tag no elimina ítems; las asignaciones quedan sin tag.
- Se preservan backup cifrado, puntajes, Ideas, Finalizaciones y compatibilidad de datos.
