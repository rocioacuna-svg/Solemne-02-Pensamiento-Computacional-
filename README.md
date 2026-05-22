# Solemne-02-Pensamiento-Computacional

# Bouncing in Space
Creado por : Rocio Acuña 

- Link editable [link](https://editor.p5js.org/rocio.acuna/full/ERDtiFk9w)
- Link Pantalla completa [Link link](https://editor.p5js.org/rocio.acuna/sketches/ERDtiFk9w)

![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/Captura%20de%20pantalla%20(61).png?raw=true)

**REFERENCIA**

![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/referenciagame.jpg?raw=true)

**Descripcion objetiva :**

El proyecto consiste en un minijuego interactivo inspirado en el espacio. El jugador debe controlar una barra utilizando el mouse para evitar que la pelota caiga. Cada vez que la pelota rebota correctamente en la barra, el jugador gana un punto y la pelota cambia de color aleatoriamente.
El objetivo principal es llegar a 10 puntos para desbloquear la pantalla de victoria. Si la pelota cae fuera de la pantalla, aparece la pantalla de “GAME OVER”.

El juego incluye diferentes elementos visuales animados como:

- ovnis
- meteoritos
- alienígenas
- estrellas
- confeti
- imágenes de victoria y derrota

![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/Captura%20de%20pantalla%20(60).png?raw=true)
![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/Captura%20de%20pantalla%20(62).png?raw=true) 


Estos elementos funcionan como distractores visuales para hacer el juego más dinámico y entretenido.

Y unl de los aspectos importantes del juego es que el jugador debe mantenerse atento al color de la pelota, ya que puede confundirse fácilmente con los meteoritos y otros elementos espaciales que se mueven constantemente por la pantalla.

Además, el rebote de la pelota fue modificado para que no siempre siga el mismo recorrido. Gracias al uso de random(), la dirección horizontal cambia después de cada rebote, haciendo que el juego sea menos predecible y más desafiante.

El proyecto utiliza:

variables
condicionales (if)
bucles (for)
funciones propias
random()
map()
interacción con mouse y teclado
output visual dinámico

Todo esto permite crear una experiencia interactiva y reactiva para el jugador.

# Qué quería lograr

Quería crear un juego donde se pudiera perder y ganar, y que aparecieran imágenes cuando pasaran esas cosas sí o sí. Tuve que buscar videos en redes sociales para aprender a usar algunos códigos que no habíamos visto en clases y también usé ayuda de IA para aplicarlos bien. Aun así, me aparecieron muchos errores e incluso una vez la página se quedó pegada 😅.

# Qué aprendí

Creo que ahora soy más rápida en cuanto al razonamiento. Cuando aparece un error, logro identificarlo más rápido y, cuando quiero agregar algo nuevo, pienso un rato en cómo podría hacerlo. No siempre me funciona perfectamente a la primera, pero igual logro resolverlo 😁.

# Qué no me salió

Las cosas que no me salieron fueron pocas, porque busqué en muchos lugares hasta encontrar cómo hacerlas y dejaba la IA como última opción. Algo que sí quería agregar era un botón de inicio o reinicio, pero encontré muy poca información y no logré entender bien cómo hacerlo 😔.

# Errores que encontré y solucioné

Mientras probaba el juego, encontré un problema en la lógica de rebote de la pelota. La pelota siempre seguía el mismo recorrido y terminaba rebotando en los mismos lugares, por lo que, después de jugar varias veces, era fácil predecir dónde iba a caer y ganar siempre.

El problema era que la velocidad horizontal (`speedX`) nunca cambiaba al rebotar con la barra. El código solamente invertía la velocidad vertical (`speedY`), lo que hacía que la trayectoria fuera siempre la misma.

Para solucionarlo, agregué un cambio en la velocidad horizontal usando `random()`. De esta manera, cada vez que la pelota rebota en la barra, el ángulo cambia y el movimiento se vuelve más dinámico e impredecible.

Con esto, el juego se volvió más interactivo, menos predecible y con una dificultad más equilibrada para el jugador.

## Diagrama de flujo 
Simple y justo.
[link](https://canva.link/z1aolwiapoe7gfa)
