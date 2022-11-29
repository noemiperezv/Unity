# Creación de Video Juego
![Logo](https://cdn-3.expansion.mx/dims4/default/5fd17a8/2147483647/strip/true/crop/3864x2576+0+0/resize/1200x800!/format/webp/quality/90/?url=https%3A%2F%2Fcdn-3.expansion.mx%2F33%2F38%2F425ea19f487680315036da9ef5f3%2Fistock-1334436084.jpg)
    Short description
    <br>
    <a href="https://reponame/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://reponame/issues/new?template=feature.md&labels=feature">Request feature</a>
  </p>
</p>


## Contenido

- [Introducción](#introducción)
- [Código Fuente](#código-fuente)
- [Planificación](#planificación)
- [Autores](#autores)
- [Copyright](#copyright)


## Introducción

- Nombre del proyecto: 
  Monty
- Objetivo: 
  Controlar el jugador para encontrar el queso que le fue robado, haciendolo en el tiempo establecido, y con la puntuación en números positivos.
- Plataforma: 
  PC, Género: Aventura, Clasificación: Todos, Personajes: Jugador y enemigos , Escenario: un laberinto.
- Historia:
  Algunos bandidos han robado el queso de la rata Monty, y lo han colocado en un lugar aleatorio en la escena del juego. Por lo que ahora debe emprender un viaje a través de un bosque para poder encontrarlo. En el camino encontrara algunos enemigos que le restaran vidas, o algunos poderes que le ayudaran a derrotar a sus enemigos.
- Personajes:
  La rata Monty
  <br>
  ![image](https://user-images.githubusercontent.com/66137245/199128891-421db1be-36d5-4492-aaa3-0bb907518a18.png)
  <br>
  5 enemigos(3 humanos y 2 animales).
  <br>
  ![image](https://user-images.githubusercontent.com/66137245/199129569-196b1b33-fa37-4fa9-b98c-54dbb0733159.png)
  ![image](https://user-images.githubusercontent.com/66137245/200083332-fca042da-2f2c-4e59-b92a-b519e4c0f46d.png)
  ![image](https://user-images.githubusercontent.com/66137245/199129589-4e96ed75-ad74-45a0-8a02-4239eb7bce3f.png)
  <br>
  ![image](https://user-images.githubusercontent.com/66137245/199129094-2089627d-c12e-4f89-9b09-13695b03d628.png)
  ![image](https://user-images.githubusercontent.com/66137245/199129282-43fd8e4e-60b2-40db-b49e-723bbd17b74a.png)
- Escenario:
  <br>
  ![image](https://user-images.githubusercontent.com/66137245/200076125-32f4fd6b-36b7-47ca-ac35-140fc9e65e5d.png)
- Reglas de Juego:
  El jugador inicia con 3 vidas, una puntuación en 0, y 5 minutos para completar el recorrido.
  El jugador puede moverse hacia adelante, hacia los lados, y saltar. 
  Durante el recorrido encontrará algunos obstaculos que le restaran puntuación o enemigos que se moveran en la escena de juego para intentar detenerlo.
  En la escena de juego se encuentran recompenzas para sumar su puntuación y 2 vidas más para ayudarlo a llegar a su objetivo.
  El juego termina si su puntuación llega a números negativos es decir es menor a 0, también puede terminar si se queda sin vidas, lo mismo que si se termina el tiempo.
  Gana el juego cuando logra llegar al final del camino y encuenra su queso.
- Niveles: El juego cuenta de dos niveles, en el primero, el jugador inicia desde el punto de entrada y debe encontrar la meta (el queso), una vez que logre     encontrarla terminará el primer nivel como ganador, y podra acceder al siguiente nivel. En el que hara un recorrido similar al del primer nivel, pero con menos tiempo, y los enemigos apareceran con más frecuencia.
<br>
- Pantallas de Juego
  Pantalla de inicio.
  <br>
  
  ![image](https://user-images.githubusercontent.com/66137245/200076375-52297fde-14c0-49d2-b946-72cb1ba6a9fc.png)
  <br>
  Pantalla de juego en curso.
  <br>
  ![Juego en curso](https://user-images.githubusercontent.com/66137245/200076462-bc331d94-d21d-4cfb-9819-9dd5b67af905.png)
  <br>
  Pantalla de juego terminado.
  <br>
  ![Game over](https://user-images.githubusercontent.com/66137245/200076497-115c79a8-9245-4dd5-8543-f4dd80fb6b49.png)
  Pantalla de juego ganado.
  <br>
  ![Juego ganado](https://user-images.githubusercontent.com/66137245/200076636-c6b6aa76-963b-4773-a4e4-79f5917c9454.png)
  <br>
- Plan de creación de VideoJuego.
<table>
  <tr>
    <th>Acción</th>
    <th>Descripción</th>
    <th>Fecha estimada</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Diseñar el personaje, el escenario, y los objetos que aparecerán en el juego.</td>
    <td>31/10/2022 <br>  04/11/2022</td>
  </tr>
  
  <tr>
    <td>2</td>
    <td>Seleccionar los efectos especiales con los que contará.</td>
    <td>07/11/2022 <br> 9/11/2022</td>
  </tr>
  
  <tr>
    <td>3</td>
    <td>Seleccionar los efectos de sonido y melodías necesarias. </td>
    <td>10/11/2022 <br> 14/11/2022</td>
  </tr>
  
  <tr>
    <td>4</td>
    <td>Programar los distintos niveles.</td>
    <td>15/11/2022 <br> 21/11/2022</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Realizar pruebas.</td>
    <td>22/11/2022 <br> 25/11/2022</td>
  </tr>
</table>

## Código videojuego
  * > [Version 1.0](https://drive.google.com/file/d/1Ahoftp3AxscHc8ZBUi-HtnEzQX9Iryoi/view?usp=sharing)
  * > [Version 1.1](https://drive.google.com/file/d/1Fjty5NPvg2nWTbYGQ2t3Hpz5zmTFfy1H/view?usp=sharing)
  * > [Version 1.2](https://drive.google.com/file/d/1rz8IqVnvVNN7xRzCB7AKwRdhrS41hpRD/view?usp=sharing)
## Descripción de la versión 1.0:
* Elementos visibles en el juego.
  * Contiene escenario de juego.
  * Incluye jugador.
* Elementos en carpeta prefabs:
  * 5 enemigos (Cada uno tiene la animación de correr por defecto).
  * Elementos que seran las recompenzas para el jugador.
  * Elementos que dañaran al jugador o restaran puntuación.
  * Elemento que servira para agregar una nueva vida al jugador.
  * Elemento que servira como el objetivo de búsqueda del jugador.
* Elementos en la carpeta scripts:
  * Archivo para controlar al jugador (actualmente solo puede moverse hacia adelante y girar hacia los lados, también se maneja la transición entre la animación de inactivo a caminando).
  * Archivo para controlar el movimiento de la cámara (sigue al jugador).
* Elementos en la carpeta Particles:
  * Efecto de explosión para cuando el jugador entre en contacto con los elementos que lo dañan.
  * Efecto de particulas para cuando el jugador obtiene una vida.
  * Efecto de particulas para cuando el jugador  obtiene una recompenza.
* Elementos en la carpeta Controllers:
  * Controlador de animaciones para cada uno de los personajes: el jugador y 5 enemigos. 
## Descripción de la versión 1.1:
* Elementos en la carpeta PhysicsMaterials
  * Material "Bouncy".
* Elementos en la carpeta Scripts:
  * Archivo "SpawnManager" para generar distintos enemigos cada 30 segundos.
  * Archivo "Enemy" para controlar las acciones de los enemigos.
* Elementos en la carpeta sounds:
  * Sonido para los saltos.
  * Sonido para obtener recompenzas.
  * Sonido para explosión. 
 ## Descripción de la versión 1.2
 * Elementos en la carpeta Scripts:
   * Cambios en "Spawn Manager": Se generan los diversos componentes del juego para el nivel 1 se crean 25 enemigos, y 30 para el nivel 2, en cada nivel se genera también el objetivo meta(un queso), 100 elementos al azar (incluye recompensas y bobmas), así como 2 vidas al iniciar el juego.
   * Cambios en "Enemy": los enemigos aún tienen como enemigo perseguir al jugador, pero inician deambulando por el área de juego, y en cuanto detectan al jugador empiezan a seguirlo.
   * Archivo "TimeController" y "TimeControllerLevel2", para establecer un temporizador con el tiempo de cada nivel (5 minutos para el primero, 3 minutos para el segundo).
   * Archivo "RotateCamara", para controlar mejor la posición de la cámara, ya que permite moverse en dirección al personaje.
 *  Elementos en la carpeta Sprites:
    * Se incluyen las imagenes utilizadas dentro del juego (un reloj para el temporizador, una estrella para la puntuación, y corazones para las vidas).
 *  Cambios en la carpeta Characters/Enemies:
    * Se agregan dos animaciones más para cada uno de los 5 enemigos (estado quieto, y caminar para deambular en el terreno de juego).
 *  Cambios en la carpeta Controllers:
    * En cada uno de los controladores para el enemigo se incluyen las animaciones de estar quieto y caminar, también se determina cuando se usaran dependiendo de unas condiciones.  
 *  Elementos en el componente Canvas:
    * Panel para la puntuación (incluye imagen y texto con la puntuación).
    * Panel para el temporizador (incluye imagen y texto con el tiempo restante).
    * Panel para las vidas del jugador (incluye imagenes dependiendo del número de vidas con las que cuente).
    * Panel de inicio para poder comenzar el juego.
    * Panel de game over que muestra un mensaje con la causa por la que perdio el juego, y un botón para reiniciar el juego.
    * Panel de juego ganado, que muestra un mensaje de felicitación para el jugador, y  un botón para pasar el segundo nivel.

## Código Fuente

* Lección 1
  * > [Tutorial](Lesson1_NoemiPerezVega.unitypackage)
  * > [Laboratorio](https://utnorteguanajuato-my.sharepoint.com/:w:/g/personal/1219100448_alumnos_utng_edu_mx/EYtTqyXOCDJBl8ZUBck7pVUBuoRCYa-Q3mI48r5w0a9jDw?e=9u3hHG)
  * > [Desafío](Lesson1_Challenge_NoemiPerezVega.unitypackage)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370204-14da8e45-a5bb-4bec-8fd9-7b84b2ddb03a.png)
  ![image](https://user-images.githubusercontent.com/66137245/197370220-febc5774-c0d2-4820-bb45-f6f16f826ca6.png)

* Lección 2
  * > [Tutorial](Lesson2_NoemiPerezVega.unitypackage)
  * > [Laboratorio](Noemi_V0.1.unitypackage)
  * > [Desafío](Lesson2_Challenge_NoemiPerezVega.unitypackage)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370289-fa174849-fad3-4029-a434-f8206ec9b47c.png)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370320-907ac1a0-2408-4f0d-a541-6a274db51294.png)
* Lección 3
  * > [Tutorial](Lesson3_NoemiPerezVega.unitypackage)
  * > [Laboratorio](Noemi_V0.2.unitypackage)
  * > [Desafío](Lesson3_Challenge_NoemiPerezVega.unitypackage)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370342-6c028702-0ea9-4f41-a9ae-9c904e6e7c00.png)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370348-e7eb79dc-65ff-4c02-ae36-ce3b97a6af45.png)
* Lección 4
  * > [Tutorial](Lesson4_NoemiPerezVega.unitypackage)
  * > [Laboratorio](Noemi_V0.3.unitypackage)
  * > [Desafío](Lesson4_Challenge_NoemiPerezVega.unitypackage)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370370-a52253f3-3c66-4508-a492-3b82f84823f0.png)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370403-260e2951-cd04-4948-b28c-1547ace51888.png)

* Lección 5
  * > [Tutorial](Lesson5_NoemiPerezVega.unitypackage)
  * > [Laboratorio](Noemi_V0.4.unitypackage)
  * > [Desafío](Lesson5_Challenge_NoemiPerezVega.unitypackage)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370432-ad549299-2cbf-4937-ad76-3cff0491d585.png)
  * > ![Prueba](https://user-images.githubusercontent.com/66137245/197370439-165ee79e-9575-45c6-a34d-2aa788ef96fe.png)

* VideoJuego

## Videos con los desafíos
* [Desafío Lección 1](https://drive.google.com/file/d/1ZHnoSGtU3S0NPdcOWW8Xum5z54WF241f/view?usp=sharing)
* [Desafío Lección 2](https://drive.google.com/file/d/1NK674gLV-O9OeeBq-mEn3ZBUzEs7oQMQ/view?usp=sharing)
* [Desafío Lección 3](https://drive.google.com/file/d/18tQyiLbeGR3mvkBTiD9ekWdwwWxYZ650/view?usp=sharing)
* [Desafío Lección 4](https://drive.google.com/file/d/1A1QYEyKSAtMGpyE-sEquWI1XcE80ln64/view?usp=sharing)
* [Desafío Lección 5](https://drive.google.com/file/d/1JXOQaLyrolYFdfKHLsWIu5T-Zhuar_cz/view?usp=sharing)

## Planificación
![image](https://user-images.githubusercontent.com/66137245/200086361-d0251781-d2cb-4cd6-b329-37eac59517b5.png)
[Link de la planeación](https://sharing.clickup.com/31602085/g/h/y4dd5-105/0fb24b13d2b9a81)
## Autores
Noemi Perez Vega
Carolina Ramos Velázquez

## Copyright
Derechos Reservados 2022
