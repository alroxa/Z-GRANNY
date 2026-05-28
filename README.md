## Z-GRANNY

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# 1 Datos 



**Titulo** : Z-GRANNY

**Web:**   https://albert0r0cha.itch.io/z-granny

**Autor:**  Alberto Rocha Campillo 


**Resumen** : Tu abuela te envía una carta para que vayas a visitarla. Es la primera vez que vas a verla y te invaden los nervios, porque claro, estamos en el año 2092 y las cosas ya no son como antes. Una herencia, un gato IA y muchas plumas... ¿qué es lo peor que puede pasar?

**Estilo/género:**  Juego

**Logotipo** : 
![img](IMG_4098.PNG)

**Resolución:** 1152x648px responsivo

**Probado en:**   Google Chrome

**Tamaño proyecto:** 136MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 27/05/2026

**Medios** (donde se tiene presencia relacionada):

- Github: https://alroxa.github.io/Z-GRANNY/#/
- Itch.io: https://albert0r0cha.itch.io/z-granny
  

![img](IMG_4339.PNG)

# 2. Memoria del proyecto 

### 2.1 Storyboard: 



El juego comienza con un menú con tres botones desplegables: el botón galería (te lleva a la galería con información de los personajes), el de créditos (te lleva a una pantalla con los créditos) y el botón de play. Al pulsarlo se reproduce un vídeo en el que ves cómo recibes la carta y vas en bus a ver a tu abuela. Termina la intro y te encuentras en el pasillo, donde te puedes mover hacia izquierda y derecha e interactuar con los muebles y las puertas cerradas. La última puerta te lleva a la habitación de la abuela, donde hablas con ella y te explica que al ganarte la confianza de su gato te dará toda su herencia. Al acabar este dialogo puedes interactuar con los muebles de la habitación y con el personaje de la abuela. Al salir, otra puerta del pasillo estará desbloqueada, y al entrar, podrás hablar con Chati, el gato, y te preguntará si estás listo para iniciar el minijuego. Al aceptar, te lleva a la escena del minijuego, donde debes recoger todas las plumas haciendo clic sobre ellas antes de que pasen 15 segundos. Si fallas, se te lleva de vuelta a la habitación de la abuela y vuelta a empezar. Si ganas, vuelves a hablar con Chati y te salta la imagen final, donde puedes volver al menú principal.



### 2.2. Esquema de navegación 


![img](Storyboard_Z-GRANNY.PNG)







# 3. Metodología

Para hacer este juego, he creado en primer lugar una escena de menú con botones interactivos y animaciones iniciales con animation player. También he incrustado un vídeo, pasándolo antes a archivo OGV. Para las escenas del juego, he creado un player con una cámara que le sigue a izquierda y derecha, y con áreas de colisión e interacción con los objetos interactuables que hay en el fondo. Además, he trabajado con el dialogic, creando estilos personalizados para las burbujas de texto, tanto para los personajes como para los objetos. Por último, el minijuego final lo he creado haciendo una escena aparte con el objeto de la pluma y sus propiedades y animación que debe hacer al clicarse, y luego en la escena minijuego lo he colocaado duplicado muchas veces, y he añadido un Timer.



## Etapa 1: Ideación de proyecto

**Investigación de campo** 

- Cucharacha, LeoGarru https://leogarru.itch.io/cucharacha
- Lookouts https://paranoidhawk.itch.io/lookouts
- Exhibit of Sorrows https://adayofjoy.itch.io/exhibit-of-sorrows


**Motivación de la propuesta** 

La motivación inicial para este proyecto fue hacer un juego cómico, con un estilo de dibujo característico en el que todo estuviese hecho por mí (menos la música, siendo esta de pixabay). 



**Publico / audiencia**

- Orientado a un púlico joven, que ronde desde los 15 a los 25 años. Aunque apto para todo tipo de público.





## Etapa 2: Desarrollo / actividades realizadas

(qué soluciones has planteado y cómo se han resuelto: juego, galería de fotos, grabación de video, etc.)

- En cuanto al juego, como ya he mencionado anteriormente, he querido basarlo en un sistema de movimiento de personaje hacia los lados con interacción con objetos y diálogos.
- Para la creación del vídeo de la intro, primero dibujé todos los elementos en Procreate y luego los animé en CapCut, siendo esta la forma más sencilla y cómoda que encontré para generar movimientos fluidos en un vídeo tan sencillo y corto. 
- En cuanto a las instruciones y ayuda al usuario, hay un par de carteles que se despliegan en momentos del juego, como justo al empezar, que te avisa de los controles para moverte e interactuar con los objetos. Estos carteles con información son básicamente un CanvasLayer con un control, un label y un texture rect.
- El menú y los elementos del mismo como la galería o los créditos son escenas aparte a las que se accede mediante botones. Algunos como los de las flechas para volver al menú principal, o los botones de izquierda y derecha para navegar por la galería están animados. La galería es una sola escena que va cambiando las imagenes (Sprites2D) y el texto (label) que se muestra al pulsar los botones.



## Etapa 3: Problemas identificados

Quizás el principal problema que he tenido en general a la hora de desarrollar este juego ha sido el tiempo y el nulo conocimiento sobre programación que tenía previo a esta asignatura. Al estar en la carrera y tener muchos trabajos que hacer a la vez de todas las materias me ha sido muy difícil sacar todo el tiempo que me hubiese gustado para desarrollar de forma más compleja y extensa el juego, puesto que he acabado cogiéndole gusto, pero entre tener que dibujar yo todo lo que se ve en el juego y programar, me ha llevado demasiado tiempo.
Hay algunos errores visibles, como que al entrar al pasillo por primera vez o a la habitación de la abuela el fondo se ve cómo se recoloca en su sitio rápidamente en el primer segundo, o que el vídeo de la intro tiene muy baja calidad. Al igual que estos, han ido surgiendo mil errores que he intentado solucionar de forma efectiva y de manera que no afecten a la jugabilidad. 



# 4. Conclusiones 

En conclusión, considero que en estos meses, aunque haya sido de forma muy superficial y básica, he aprendido bastante sobre el mundo de la programación y cómo se hacen los videojuegos, que era algo que me generaba mucho interés, y para el tiempo que he tenido y la experiencia que tenía, estoy bastante satisfecho con el resultado, aunque sea un juego bastante corto. De cara a futuro me gustaría seguir explorando este campo para ver hasta dónde puedo llegar.







# 5 Referencias 

**Artículos y blogs** 


**Recursos y materiales audiovisuales:**

* Musica: pixabay.
* Imágenes: todo dibujado por mí.
* Tipografía: Super Bugly y Vintage Vibes (dafont.com).

**Herramientas utilizadas**

- Godot Engine 4.0
- Procreate
- CapCut


https://creativecommons.org/licenses/?lang=es

* logos en https://creativecommons.org/mission/downloads/
  
  <img src="https://licensebuttons.net/l/by-nc-sa/3.0/nl/88x31.png" style="width: 80px"></small>

Mayo 2026
