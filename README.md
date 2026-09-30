Decision Plan v5.9.7
- Corrige Clonar Plan: conserva las selecciones FINAL:<id> en cada opción.
- También conserva PLAN:<id> y END; sólo remapea IDs de decisiones internas del plan clonado.
- Clonado reestructurado: primero hace copia profunda del objeto completo del plan y luego remapea únicamente IDs internos.
- Esto hace que campos agregados posteriormente al modelo del plan se copien por defecto, evitando que nuevas propiedades se pierdan por una lista manual desactualizada.
- Renueva IDs de decisiones, opciones, ítems y deepLinks internos.
