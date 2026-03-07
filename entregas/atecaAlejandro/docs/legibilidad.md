# Justificaciones

|Categoría||Justificación||
|-|-|-|-|
|**Nombrado**|Ejemplo +| Cumple perfectamente con el principio de revelar la intención. En un simulador de clima, un nombre genérico como posicionRayo sería aceptable, pero landing (aterrizaje) aporta un nivel de precisión semántica que elimina cualquier duda sobre qué representa ese número en el eje X del edificio. |https://github.com/alejandroateca/23-24-prg1/blob/ce17d4b2a0c38069e08202c551ea1ace9ab1db5e/entregas/alejandroAteca/examenParcial/examenEdificio.java#L14|
||Ejemplo -|El uso de sufijos como P o A en atributos de clase (ej. nombreP en Profesor) viola el principio de evitar codificaciones redundantes. Dado que el contexto de la clase ya define la identidad del objeto.|https://github.com/alejandroateca/23-24-prg2-ep/pull/1
||Ejemplo -|Nombre desinformativo / Palabra vacía: La variable actual viola el principio de "Revelar la intención". Es un nombre genérico que no describe el contenido semántico del dato, sino simplemente su estado temporal.|https://github.com/alejandroateca/24-25-EDA1/pull/1
|**Comentarios**|Ejemplo +|
||Ejemplo -|Comentario redundante: El texto se limita a parafrasear literalmente lo que el código ya expresa.|https://github.com/alejandroateca/24-25-EDA1/pull/2
||Ejemplo -||PR corrección
|**Formato**|Ejemplo +|
||Ejemplo -| El formateo de la variable windowState mediante un operador ternario anidado rompe el principio de comunicación y jerarquía. El código debe leerse como prosa; al comprimir cuatro estados lógicos en una sola línea densa, se sacrifica la claridad por la brevedad.|https://github.com/alejandroateca/23-24-prg1/pull/2
||Ejemplo -| Violación de Densidad Vertical y Afinidad: Los saltos de línea aleatorios entre casos destruían la agrupación visual.|https://github.com/alejandroateca/24-25-EDA1/pull/2
|**Estándares**|Ejemplo +|
||Ejemplo -|la nomenclatura estándar de Java. Las clases deben empezar siempre por mayúscula. (Masías se tuvo que tirar de los pelos ese día). Además, incluir la palabra "examen" es ruido de contexto externo que no describe la solución técnica pero esto lo pasaremos por el contexto de la evaluación.|https://github.com/alejandroateca/23-24-prg1/pull/2
||Ejemplo -||PR corrección
|**Consistencia**|Ejemplo +|
||Ejemplo -|Inconsistencia de comportamiento: La clase Cola añade elementos al final (FIFO), pero Playlist y Album los insertan al principio (LIFO). Sino que rompe la lógica del dominio: una playlist del mundo real no invierte el orden de las canciones añadidas.|https://github.com/alejandroateca/24-25-EDA1/pull/2
||Ejemplo -| Inconsistencia de nivel de abstracción: Tres clases distintas implementan exactamente la misma lógica de bajo nivel para iterar sobre nodos enlazados.|https://github.com/alejandroateca/24-25-EDA1/pull/2
|**Código muerto**|Ejemplo +|
||Ejemplo -|En la versión original, la variable se inicializaba innecesariamente como una cadena vacía ("") fuera del bucle, valor que nunca era leído. Al mover la declaración de fragmentoEvaluado al interior del bloque for, se elimina ese "ruido" visual|https://github.com/alejandroateca/24-25-EDA1/pull/1
|**DRY**|Ejemplo +| 
||Ejemplo -|Al repetir siete bloques idénticos de lógica (impresión, captura y acumulación). Esto genera fragilidad: cualquier cambio en la interfaz de usuario o en el flujo de entrada requiere modificaciones múltiples. El efecto en la mantenibilidad es un aumento innecesario del esfuerzo de actualización y del riesgo de introducir errores al hacer las repeticiones.|https://github.com/alejandroateca/23-24-prg1/pull/1
|**YAGNI**|Ejemplo +|
||Ejemplo -| Se implementó el método previendo que sería útil, pero la clase cliente (SistemaReproduccion) jamás lo invoca; gestiona los estados vacíos comprobando devoluciones null o usando size().|https://github.com/alejandroateca/24-25-EDA1/pull/2




