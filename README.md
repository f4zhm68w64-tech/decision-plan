Decision Plan v5.9.9
- Los planes restringidos por puntaje ya no interrumpen un flujo PLAN: con alerta.
- Disponibilidad incorpora “Si no cumple el puntaje, continuar en”.
- El fallback puede apuntar a otro plan o a una decisión del propio plan restringido; FIN estándar queda disponible.
- Si el fallback es otro plan también restringido y no elegible, se resuelve su propio fallback.
- Mantiene compatibilidad: restricciones existentes sin fallback se interpretan como FIN estándar.
