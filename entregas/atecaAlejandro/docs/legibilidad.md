# Justificaciones

|Categoría||Justificación||
|-|-|-|-|
|**Nombrado**|Ejemplo +| Cumple perfectamente con el principio de revelar la intención. En un simulador de clima, un nombre genérico como posicionRayo sería aceptable, pero landing (aterrizaje) aporta un nivel de precisión semántica que elimina cualquier duda sobre qué representa ese número en el eje X del edificio. |https://github.com/alejandroateca/23-24-prg1/blob/ce17d4b2a0c38069e08202c551ea1ace9ab1db5e/entregas/alejandroAteca/examenParcial/examenEdificio.java#L14|
||Ejemplo -||PR corrección
||Ejemplo -||PR corrección
|**Comentarios**|Ejemplo +|
||Ejemplo -||PR corrección
||Ejemplo -||PR corrección
|**Formato**|Ejemplo +|
||Ejemplo -| El formateo de la variable windowState mediante un operador ternario anidado rompe el principio de comunicación y jerarquía. El código debe leerse como prosa; al comprimir cuatro estados lógicos en una sola línea densa, se sacrifica la claridad por la brevedad.|https://github.com/alejandroateca/23-24-prg1/pull/2
||Ejemplo -||PR corrección
|**Estándares**|Ejemplo +|
||Ejemplo -|la nomenclatura estándar de Java. Las clases deben empezar siempre por mayúscula. (Masías se tuvo que tirar de los pelos ese día). Además, incluir la palabra "examen" es ruido de contexto externo que no describe la solución técnica pero esto lo pasaremos por el contexto de la evaluación.|https://github.com/alejandroateca/23-24-prg1/pull/2
||Ejemplo -||PR corrección
|**Consistencia**|Ejemplo +|
||Ejemplo -||PR corrección
||Ejemplo -||PR corrección
|**Código muerto**|Ejemplo +|
||Ejemplo -||PR corrección
|**DRY**|Ejemplo +| 
||Ejemplo -|Al repetir siete bloques idénticos de lógica (impresión, captura y acumulación). Esto genera fragilidad: cualquier cambio en la interfaz de usuario o en el flujo de entrada requiere modificaciones múltiples. El efecto en la mantenibilidad es un aumento innecesario del esfuerzo de actualización y del riesgo de introducir errores al hacer las repeticiones.|https://github.com/alejandroateca/23-24-prg1/pull/1
|**YAGNI**|Ejemplo +|
||Ejemplo -||PR corrección




