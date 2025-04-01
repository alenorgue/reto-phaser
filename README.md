# Reto Phaser 3

Os han contratado a tí y a tu equipo para modificar un juego creado con la biblioteca [Phaser3](https://phaser.io/) de JavaScript

Teneis acceso al código a través de este [enlace](https://labs.phaser.io/edit.html?src=src/games/firstgame/part9.js&v=3.55.2)
Cuando le daís al botón RUN CODE; el juego se ejecuta a la derecha.

Familiarizate un poco con el código del juego y luego implementa los siguientes requisitos:

## Requisitos

Para cada requisito del 1 al 4, tan solo hay que cambiar
una línea de código por requisito.

1. El tamaño de la puntuación quiero que sea de un
tamaño mucho más grande.
2. El color del texto SCORE debe ser diferente a negro, el que sea, pero que quede bien con el azul de fondo. BONUS: Concretamente, al cliente le haría gracia que pusieramos el amarillo Bumblebee
3. Las estrellas deben otorgar solo UN punto cada vez
que las recojamos.
4. Queremos que el personaje aparezca ahora en la parte
derecha de la pantalla.
5. Contesta:
   1. ¿Cuál es la función que se ejecuta cuando colisiona el persona y una estrella?  
     collectStar (player, star)
   2. ¿Cuál es la función que ejecuta el programa para _desactivar_ o hacer desaparecer una estrella?
   star.disableBody(true, true);
6. (difícil). Consulta la documentación de Phaser3; y 
averigua como hacer que el personaje se pueda mover
también a izquierda y derecha con las letras A y D; 
respectivamente. También debería poder saltar con la letra W.

[Vídeo funcionalidades deseadas](https://ttprivatenew.s3.amazonaws.com/pulse/oscarm/attachments/18806197/TinyTake13-01-2022-11-15-50.mp4)

## Motivación

En vuestro desarrollo profesional os vaís a tener que entender y trabajar con herramientas con poco margen de tiempo. Es necesario coger soltura en detectar estructura de datos conocidos, nombres de funciones y variables sugerentes; o saber explorar la documentación de una biblioteca para poder llevar a cabo el trabajo.

¡Buena Suerte!

![phaser](https://phaser.io/images/img.png)
