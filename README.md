# Solemne-02-Pensamiento-Computacional
Creado por: Rocio Acuña
# Bouncing in Space

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



![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/Captura%20de%20pantalla%20(61).png?raw=true)
![imagen]() 

**REFERENCIA**

![imagen](https://github.com/rocioacuna-svg/Solemne-02-Pensamiento-Computacional-/blob/main/images/referenciagame.jpg?raw=true)

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

Que queria lograr: 
- Un juego donde se pierde y se gana y que salieran imagenes cuando pasaran esas cosas si o si. (tuve que buscar videos en redes sociales de como utilizar algunos codigos que no habiamos visto y ayuda de la ia para aplicalo bien, pero igual me saltaron demasiados errorews y hasta se quedo pegada la pagina una vez 😅.)
Que aprendi:
- Creo que ahora soy mas rapida en cuanto al razonamiento, osea cuando me salta un error lo logro identificar rapido y cuando quiero poner algo nuevo pienso un rato en como podria hacerlo y me funciona, bueno no perfectamente a la primera pero si 😁.
Que no me salio: 
- Cosas que no me salieron fueron pocas porque busque en tdodos lados lo que queria hacer hasta que lo encomtraba y mi ultima opcion era la ia pero algo que queria era hacer como un boton de inicio o reiniciar y busque y habia poca info y no entendi 😔.

**ERRORES que encontre y solucione**

Mientras probaba el  juego encontré un problema en la lógica de rebote de la pelota. La pelota siempre seguía el mismo recorrido y terminaba rebotando en los mismos lugares, por lo que después de jugar varias veces era fácil predecir dónde iba a caer y ganar siempre.

El problema era la velocidad horizontal (speedX) nunca cambiaba al rebotar con la barra. El código solamente invertía la velocidad vertical (speedY), lo que hacía que la trayectoria fuera la misma.

Para solucionarlo, agregué un cambio en la velocidad horizontal usando random(). De esta manera, cada vez que la pelota rebota en la barra, el ángulo cambia y el movimiento se vuelve más dinámico e impredecible.
Con esto el juego se volvió más interactivo, menos predecible y con una dificultad más equilibrada para el jugador.


## Diagrama de flujo 
[link](https://canva.link/z1aolwiapoe7gfa)
