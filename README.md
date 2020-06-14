## Please Be My Valentine

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada



# Datos 



**Titulo** : Please Be My Valentine

**Web:**   https://sandradomz.github.io 

**Autor:**  Sandra Valdivieso Domínguez

**Resumen** : "Please Be My Valentine" es un juego tipo dating simulator en el que nos ponemos en la piel de nuestra protagonista en el día de San Valentín. Hay 3 rutas para escoger, todas ellas esconden secretos que tendrás que desvelar escogiendo las respuestas correctas para avanzar la historia y llegar al final.

**Estilo/género:**  Novela visual/Juego

**Logotipo** : 
![Logo](https://raw.githubusercontent.com/sandradomz/sandradomz.github.io/master/salida/logo.png)


**Resolución:** 800x600px tamaño fijo (No reescalable porque cuenta con elementos hechos con pixel art y deformar el formato puede provocar que los gráficos se vean mal)

**Probado en:**   Google Chrome, Móviles android.

**Tamaño proyecto:** 16.7MB 

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** : 14/05/2020

**Medios** (donde se tiene presencia relacionada):

- Github: https://github.com/SandraDomz/sandradomz.github.io
- Twitter: https://twitter.com/th3dragonmaiden
- Instagram: https://www.instagram.com/thedragonmaiden/
- Youtube. https://www.youtube.com/channel/UCiWZKM9N0gA8izM4iiGwxmw?app=desktop



# 2. Memoria del proyecto 

### 2.1 Storyboard: 
Despues de sucederse las intros y llegar al menú, hay varias opciones para pulsar:
- "Juego". Pulsando este botón comienza la parte más imporante del proyecto, el juego en sí. Se sucede un monólogo de la protagonista y tras él una pantalla en la que puedes mover libremente al personaje con las flechas del teclado hasta dirigirla hacia la puerta. Una vez pulsada la puerta se abrirá una pantalla de selección de ruta, y una vez escogido el personaje deseado comenzará su historia. Todas las rutas son sucesiones de diálogos en diferentes espacios de la protagonista con la chica elegida. De vez en cuando el jugador tendrá que escoger una de las opciones en pantalla para continuar el juego. Si todas se responden correctamente, se llegará al final del juego con una imagen exclusiva. Si solo se responden algunas bien, se llegará al final del juego pero sin imagen exclusiva. Si todas se responden mal, es posible llegar a un Game Over. 
- "Extras". En este botón se puede navegar por dos galerias de imágenes que muestran tanto información sobre los personajes como bocetos exclusivos de el "making of". También se puede visualizar un video en el que muestra como hice los sprites oficiales de los personajes en Procreate a modo de Speedpaint.
- "Créditos". En esta pestaña simplemente se suceden los créditos en scroll de abajo hacia arriba. 

Por último en ajustes, se puede cambiar el volumen de la música.


### 2.2. Esquema de navegación 

Esquema de navegación de la intro hasta el menú.

![Logo](https://raw.githubusercontent.com/sandradomz/sandradomz.github.io/master/salida/esquemanavegacion.jpg)







# 3. Metodología

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo** (propuestas inspiradoras para el proyecto)

- Lovely Hero (juego otome para android) https://play.google.com/store/apps/details?id=com.Visuki.LH&gl=ES (escogido como propuesta visual, por las paletas de colores y las gamas rosadas o con colores pasteles. También sirven de referencia cualquier juego de la misma compañía, Visuki Otomes.)
- Cinderella Phenomenon (Juego otome para PC) https://store.steampowered.com/app/568770/Cinderella_Phenomenon__OtomeVisual_Novel/ (extraido la parte que incluye diferentes rutas que se pueden escoger desde el principio del juego)
- Corazón de melón (Juego otome online) https://www.corazondemelon.es/ (de aquí saqué el tema de desbloquear imágenes exclusivas de cada ruta si escoges las opciones adecuadas)



**Motivación de la propuesta** 

Soy una persona que se considera fanática de los juegos tipo Simulador de Citas o "Otome", que es su término en japonés. Siempre voy buscando juegos nuevos de este estilo porque me gusta mucho jugarlos pero desafortunadamente la mayoría de ellos son juegos muy largos y de pago, lo que me hace que no pueda jugarlos. Por eso he querido crear uno propio además incluyendo tramas LGBT en los personajes (tanto la protagonista como las posibles rutas son chicas) ya que normalmente no lo veo en este tipo de juegos y, como ese aspecto es una parte importante en mi vida, también quería incluirlo en este juego sobre todo para que más gente pueda verse reflejada en la protagonista o en cualquiera de las rutas. 



**Publico / audiencia**

- Orientado a gente joven (de 14-15 años hasta 20-25 años), público LGTB, personas interesadas en el mundo del manga y del anime/videojuegos del estilo Visual Novel o Simulador de citas.





### Etapa 2: Desarrollo / actividades realizadas

- Juego. Para hacer una ruta tuve que hacer cantidad de diálogos (unos 100 por ruta) individualmente. Lo realmente dificil fue hacer la primera, ya que tuve que insertar variables, para que cada respuesta del jugador decidiera el final que sacaría. Todas las respuestas correctas suman +1 a la variable X, y si cuando alcanzas el final la variable es igual a 5, se desbloquea el final bueno. De lo contrario, te quedas en el Game Over. Los finales los programé con una clausula condicional (de if y else). Cuando la primera ruta estuvo hecha, que me tomó un par de días enteros, el resto eran más fáciles, porque ya tenía una plantilla que podia copiar y pegar. Sin emargo a las rutas nuevas les he añadido otro tipo de opción, que es más bien elegir entre dos imágenes que entre dos respuestas. Simplemente para darle algo más de interés al juego.
- Video. Primero quise usar un video enlazado de Youtube (ya que yo tengo un canal allí) y al principio es lo que hice, ya que tanto en Hippani como en google chrome se visualizaba el video perfectamente. Sin embargo al exportarlo al Github me daba error, asi que como no sabía como solucionarlo lo que hice fue insertar el video en el proyecto en vez de usarlo como enlace de youtube. El video pesaba muchísimo así que tuve que comprimirlo varias veces hasta que conseguí que pesara 12 MB. Esto hace que el proyecto pese más, pero como el límite es 50 MB no creo que supusiera ningún problema por ahora. 
- Instrucciones y ayuda al usuario. Mi proyecto no tiene muchas instrucciones como tal ya que me gusta más que el usuario tenga que investigar a ver lo que puede hacer por la interfaz (lo que quiero decir es que no me gusta señalarlo haciendolo evidente, sino que sea el jugador el que tenga que adivinar como avanzar, pero mi interfaz es muy intuitiva así que no es dificil hasta el punto en el que resulte un problema.) Por lo demás, todos los botones tienen sus correspondientes nombres e información como para que el usuario pueda navegar sin dificultad. 
- Menús y elementos de navegación (botones). Al principio hice una interacción y unos botones muy sencillos, así que cuando era la hora de meterle musica y sonidos decedí rehacer esta parte por completo. Rehice tanto el menú como los botones, y para darle más interactividad hice una especie de intros interactivas en las que tienes que ir clickeando con el ratón para avanzar. Cuando pude incorporar los sonidos el proyecto comenzó a tener mejor aspecto y más como un juego de verdad.
- Música y sonidos. No tuve problema con la musica ni con los sonidos más allá de implementar la música de fondo y un problema con una de las exportaciones de prueba. A mi me hubiera gustado que la música de fondo no se repitiera ni comenzara a sonar cada vez que uno va a la pantalla del menú, sino que estuviera puesta indefinidamente hasta que el jugador decidiera silenciarla o bajarle el volumen. Sin emargo y según me he informado en la página de Hippani oficial, eso es imposible de hacer en este programa. Por otro lado en una de las exportaciones sin querer solamente exporté el html sin los medios, lo que causó que todo el proyecto estuviera en silencio pero como ya dije antes, es un problema que tenía fácil solución una vez descubrí el por qué no es escuchaba.



### Etapa 3: Problemas identificados

Una de las cosas ya las he mencionado en el apartado anterior y es la música. Como ya dije, me gustaría que la música no se repitiera desde el principio cada vez que se sale al menú (que es donde esta programada la música para empezar a sonar), ya que eso causa conflictos sobre todo con los conmutadores para silenciar el proyecto (cuando le pulsas se silencia, pero si sales al menú vuelve a sonar la música y el botón de silenciar sigue pulsado, por lo que tienes que pulsar dos veces para volver a silenciar)
Es un problema que creo que no puedo resolver, y quizás por eso es el que más me molesta.
Otra cosa significativa es el programa en sí. Quizás le he pedido mucho con este proyecto, pero esta claro que es un programa que no aguanta grandes cantidades de contenido. De vez en cuando se creaban carpetas en la línea de tiempo solas, en la reproducción del proyecto fallan muchas cosas pero cuando lo exportas te das cuenta de que funcionan bien... En general, eso es todo.



# 4. Conclusiones 

Creo que para ser el primer juego que hago, esta bastante bien. Por supuesto en mi cabeza era más largo, con más escenarios y decisiones pero, es muy dificil hacer algo profesional la primera vez, y además con este programa, que no soporta muy bien el tener mucho contenido dentro. En general, estoy satisfecha y contenta de haber terminado el juego.







# 5 Referencias 

**Artículos y blogs** 

- Crofts, S., Fox, M., Retsema, A. and Williams, B. (2005) *Podcasting: A new technology in search of viable business models*First Monday, 10(9). https://doi.org/10.5210/fm.v10i9.1273. Recuperado el 8 de abril de 2020 de: https://journals.uic.edu/ojs/index.php/fm/article/view/1273/1193

**Recursos y materiales audiovisuales:**

* Musica: freesound.org  
* Imágenes: Sandra Valdivieso Domínguez 
* Tipografía: BitPotionExt by JoebRogers

**Herramientas utilizadas**

- Hippani Animator 5.1
- Filmora9 (edición de video)
- Audacity (edición de audio)



![](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)

https://creativecommons.org/licenses/?lang=es

Mayo 2020







### Comentarios

Ejemplos de otros años: https://github.com/mgea/interart

![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/CC-BY-SA-Andere_Wikis_%28v%29.svg/200px-CC-BY-SA-Andere_Wikis_%28v%29.svg.png)


