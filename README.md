Decision Plan v5.5.3
Hotfix definitivo de Finalización:
- Restaura sentenceForChoice() y lowerFirst(), funciones eliminadas accidentalmente al introducir la persistencia de sesión.
- results() dependía de esas funciones; por eso al elegir FIN estándar o una Finalización el JavaScript se detenía y la última decisión quedaba en pantalla.
- Mantiene el arreglo del selector de Finalización de v5.5.2.
- Mantiene sesión persistente, Continuar ejecución, PIN y engranaje de Administración.
