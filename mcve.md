Cuando preguntas sobre un problema causado por tu código, recibirás mejores respuestas si provees el código que se puede usar para reproducir el problema.  Ese código debe de ser:

- …Mínimo - usa la menor cantidad posible de código para reproducir el problema
- …Completo - asegurate de proveer todas las partes necesarias para reproducir el problema
- …Verificable - prueba el código que aportas para asegurarte que reproduce el problema

## Mínimo 

Cuanto más código haya, menos probable será que la gente encuentre el problema. Optimiza tu ejemplo de una de estas formas:

1. **Vuelve a empezar de cero.** Crea un nuevo programa, agregando solamente lo que es necesario para ver el problema.  Esto tiende a ser más rápido en sistemas vastos donde ya conoces la fuente del problema.  También es útil si no puedes publicar el código original por razones legales o éticas.
2. **Divide y conquista.** Cuando tienes un poco de código pero la razón del problema no esta clara, empieza a remover un poco de código a la vez hasta que el problema desaparece - entonces añade la ultima parte de nuevo.

## Mínimo *y* legible

Mínimo no implica *breve* - no sacrifiques la comunicación por motivos de brevedad.  Usa nombramientos y hendiduras consistentes y no se te olvide incluir comentarios si necesitas explicar partes del código. La mayoría de los editores de código tienen atajos para formatear - ¡encuéntralos y usalos! Por igual, **no uses tabs** - estos se ven bien en tu editor pero no en Stack Overflow. Aquí, crean un desastre.

## Completo 

Asegurase que toda la información necesaria para reproducir el problema esta incluido.

- Algunos estarán listos para cargar las partes e intentar probar el código antes de aportar sus respuestas o sugerencias.
- El problema puede que no este en la parte que te imaginas pero en vez se esconda en otra. 

Si el problema requiere código del lado de los servidores y archivos de configuraciones XML, inclúyelos también.  Si la página web requiere HTML, Javascript y CSS, incluye lo necesario.  

## Verificable 

Para poder ayudar a solucionar tu problema, otros deberán saber que *existe*:

- **Describe el problema.** “No me funciona“ no es una declaración útil.  Dinos cuál debería ser el comportamiento esperado.  Cuéntanos cual es la redacción exacta del error que se produce y en qué linea se está produciendo.  Pon un resumen breve del problema en el título de tu pregunta.
- **Elimina todas las cuestiones no necesarias al problema.** Si tu pregunta no es acerca de  un error de compilación, asegúrate de que no haya errores de ese tipo.  Usa un programa como [JSLint](http://www.jslint.com/) para validar lenguajes interpretados. Todo el HTML y XML debe ser [verificado](http://validator.w3.org/).  
- **¡Asegúrate de que el ejemplo reporta el problema en la actualidad!** Si solucionaste el problema inadvertidamente mientras preparas el aporte pero no lo pruebas de nuevo, sería bueno saberlo antes de pedir ayuda. 

Para mas ayuda en como depurar tu programa para crear un ejemplo mínimo, [Eric Lippert](http://stackoverflow.com/users/88656/eric-lippert) tiene un muy buen articulo de blog sobre este tema.
