# Escena interactiva de Killer Klowns From Outer Space (1988)
## Autor: Rocio Acuña Sanchez
Este mini juego interactivo desarrollado en p5.js donde el jugador debe eliminar a un payaso antes de que se acabe el tiempo (20 segundos).
El objetivo es dispararle únicamente en la cabeza mientras el personaje se mueve constantemente por la pantalla.

El proyecto utiliza imágenes, sonido y video para crear una experiencia inmersiva inspirada en el diseño de videojuegos de terror y supervivencia.

Descripción objetiva
¿Qué es el proyecto?

Es un videojuego interactivo desarrollado en p5.js.

**¿Qué se ve en pantalla?**
- Pantalla de inicio.
- Fondo del juego.
- Payaso en movimiento.
- Mira controlada por el mouse.
- Temporizador.
- Pantalla de Game Over.
- Video de victoria.
- Pantalla final con "YOU WIN".
  
**Elementos visuales**
- Imagen de inicio.
- Imagen de fondo.
- Imagen del payaso.
- Imagen de mira.
- Estrellas animadas.
- Texto animado.
- Video final.

**Inputs**
- Movimiento del mouse.
- Click izquierdo del mouse.
  
**Outputs**
 Movimiento del payaso.
- Movimiento de la mira.
- Sonidos.
- Video de victoria.
- Cambio entre pantallas.
- Temporizador.
  
**Descripción conceptual**

Crear una experiencia donde el jugador deba reaccionar rápidamente para eliminar un objetivo antes de que termine el tiempo, utilizando una estética inspirada en el terror y los videojuegos arcade.

**Corriente o referente**

Diseño de videojuegos.

**Referentes visuales**
Juegos arcade.
Juegos de terror.
Estética de circos oscuros.
Interfaces minimalistas de videojuegos.

**Principio de diseño explorado**

Interactividad mediante estados, retroalimentación audiovisual y respuesta inmediata a las acciones del usuario.

##Sistema computacional##

**Inputs**
Posición del mouse.
Click del mouse.
Tiempo transcurrido.

**Procesos**
Movimiento del payaso.
Detección de impactos.
Cálculo del tiempo.
Reproducción de sonidos.
Reproducción del video.
Cambio entre estados.

**Estados**
Pantalla de inicio.
Juego.
Pantalla de victoria.
Pantalla de derrota.

**Eventos**
Click para comenzar.
Disparo.
Impacto en la cabeza.
Fin del tiempo.
Fin del video.
Botón "Jugar de nuevo".

**Outputs**
Cambio de imágenes.
Animaciones.
Sonidos.
Video.
Mensajes de victoria y derrota.

## Explicación de la interacción##

El usuario inicia el juego con un clic.

Luego controla una mira utilizando el mouse y debe disparar únicamente a la cabeza del payaso antes de que el temporizador llegue a cero.

Si acierta, se reproduce un video de victoria y posteriormente aparece la pantalla final con un mensaje de "YOU WIN".

Si el tiempo termina antes de lograr el objetivo, aparece la pantalla de "GAME OVER".

## Recursos multimedia##
**Imágenes**
Pantalla de inicio.
Fondo del juego.
Fondo de victoria.
Payaso.
Mira.

Función:
Construyen la identidad visual del juego.

**Sonidos**
Música de fondo.
Sonido del disparo.

Función:
Entregar retroalimentación auditiva e incrementar la tensión.

**Video**
Animación de victoria.

Función:
Recompensar al jugador cuando gana.

## Registro visual##
**Referentes**

(Inserta aquí imágenes de referencia.)

**Bocetos**

(Agrega tus bocetos.)

**Iteraciones**

(Coloca capturas de distintas versiones del proyecto.)

**Capturas del proceso**

(Agrega capturas del desarrollo.)

## Reflexión final##

Durante el desarrollo aprendí a utilizar variables, funciones, estados, eventos, multimedia y estructuras propias de p5.js para construir un sistema interactivo más complejo.

Mi principal dificultad fue integrar correctamente el video con los distintos estados del juego y coordinar la interacción entre imágenes, sonidos y temporizador.

Este proyecto me permitió comprender mejor cómo organizar un programa utilizando funciones y cómo construir una experiencia interactiva completa.

## Enlaces ##

**Proyecto p5.js (ejecutable):**

(Pega aquí el link)

**Código editable:**

(Pega aquí el link)

Repositorio GitHub:

(Pega aquí el link)
