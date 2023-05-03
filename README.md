# Practica3 Videojuego Multijugador
Los archivos de Python salaV5.py y playerV5.py consisten en un videojuego multijugador distribuido hecho con las librerías pygame y Multiprocessing.

SOBRE EL VIDEOJUEGO:
- Es un juego de dos jugadores.
- Cada uno controla una nave que se mueve pulsando las flechas del teclado.
- Consiste en impactar al contrincante con una bala que es disparada con la tecla 'espacio' en la dirección en la que te estás moviendo.
- Cada vez que un jugador impacta al otro, las posiciones se reinician y sube en una unidad el marcador del jugador correspondiente.
- Termina cuando uno de los dos jugadores logra 4 impactos.

SOBRE LOS ARCHIVOS:
- salaV5.py se debe ejecutar en una terminal que hará de sala. Esta realizará todas las operaciones aritméticas en función de los eventos que le lleguen de los otros jugadores. De esta forma, la sala lleva toda la información importante acerca del juego.

- playerV5.py se ejecuta en la terminal del jugador y toma como argumento la dirección ip de la sala para poder conectarse a ella. Cuando solo se ha conectado un jugador, le aparece una pantalla de carga que pone: 'Esperando al contrincante'. Cuando se conecta el otro jugador el juego comienza inmediatamente. Este programa se encarga de recibir la informaci
