[El usuario Comunidad][1] borrará automáticamente preguntas viejas o abandonadas en las siguientes circunstancias:

**Si la pregunta tiene más de `30` días de antiguedad y...**

- puntuación de −1 o menor
- no tiene ninguna respuesta
- no está bloqueada

**... o ...**

- la pregunta fue cerrada y migrada hacia otro sitio de la red Stack Exchange.

... será borrada automáticamente. A este tipo de preguntas se las llama "muertas" (`RemoveDeadQuestions`, o `RemoveMigrationStubs` en caso de migración)

**Si la pregunta tiene más de `365` dias de antigüedad y...**

- puntuación de 0, **o** puntuación de 1 y la cuenta del propietario está eliminada.
- no tiene ninguna respuesta
- no está bloqueada
- tiene un número de vistas <= 1,5 veces la edad de pregunta (en días).
- tiene uno o ningún comentario.

... será borrada automáticamente. A este tipo de preguntas se las llama "abandonadas" (`RemoveAbandonedQuestions`).

Estas reglas se ejecutan una vez a la semana en todos los sitios.

**Si la pregunta fue cerrada hace más de `9` días y ...**

- no fue cerrada como duplicada
- puntuación de 0 o menos
- no está bloqueada
- no tiene respuestas con puntuación > 0
- no tiene respuesta aceptada
- no tiene votos de reapertura pendiendtes
- no ha sido editada en los últimos `9` días

... será borradas automáticamente. A este tipo de preguntas se las llama "cerradas y abandonadas" (`RemoveAbandonedClosed`).

Esta regla se ejecuta una al día en todos los sitios.

Véase también la publicación oficial ["¿Cómo funciona la eliminación de publicaciones? ¿Por qué podría eliminarse una publicación y qué implica? ¿Cuál es el criterio para eliminar?"][2].


  [1]: http://meta.stackexchange.com/q/19738
  [2]: https://es.meta.stackoverflow.com/q/1033/83
