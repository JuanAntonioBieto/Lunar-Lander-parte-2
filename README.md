# Lunar-Lander-parte-2

## Esta es la versión minificada.

### RawGit minificado: https://rawgit.com/JuanAntonioBieto/Lunar-Lander-parte-2/minificado/Lander.html

## Modificaciones respecto al original:

En la versión móvil he decidido dejarlo todo centrado en vez de tenerlo en modo para zurdos y diestros, me parece más óptimo de esta manera.

## Esquema general:

## Versión de ordenador:

He dividido la página en tres divs diferentes uno para la parte izquierda de la pantalla, otro para la parte central y el ultimo que abarca la parte derecha.

### Div Izquierdo:

Ocupa el 25% de ancho y el 100% de alto, dentro de este contenedor hay un div que contiene los 4 paneles (altura,velocidad,combustible y calor) , los paneles están unidos por una class con la cual puedo modificar su tamaño, cada uno tiene su propio div y un texto que indica su valor, exceptuando el de calor que ira cambiando de color según la cantidad de combustible que use la nave .

### Div Central:

Ocupa el 50% de ancho y el 100% de alto, dentro de este contenedor solo esta la nave en la parte superior de la pantalla, este div me ayuda a colocar los paneles y los botones.

### Div Derecho:

Ocupa el 25% de ancho y el 100% de alto,hay un div que contiene todos los botones,estos tienen una class con la que modifico su tamaño, aparte cada botón tiene su propio div .Los botones ahora mismo no son funcionales exceptuando el de información que al pulsarlo te llevara a otra página con las instrucciones, para volver a la página anterior tienes que pulsar en las instrucciones (esto es temporal). El botón de pausa en la versión final al pulsarlo se cambiara por el botón de play, el cual por ahora esta en oculto. El botón de power y el de menú están en oculto ya que solo forman parte de la versión móvil.

### Otros

La luna esta fija en la parte baja de la pantalla.

## Versión móvil:

Los divs izquierdo,central y derecho son los mismos que en la versión de ordenador pero con los tamaños ajustados, pero en el divs derecho hay varios cambios, y se añade el botón de power.

### Div Derecho:

Los botones que habían en la versión de móvil han sido cambiados por un solo botón, el de menú, al pulsarlo aparecerán los botones de play,reiniciar y información, ahora mismo estos botones no están en oculto, el botón de información te redirige a la página con las instrucciones, al pulsar en las instrucciones, vuelves a la página anterior.

### Otros

Ahora en la parte de abajo hay un nuevo botón, el de power, que esta superpuesto a la luna. 
