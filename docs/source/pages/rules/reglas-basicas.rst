Reglas Básicas
==============

En esta sección se describen las reglas básicas de 2d6Mundos, que son las que se aplican en todos los juegos de rol que utilizan este sistema. El DJ debe estar familiarizado con el reglamento. El resto de los jugadores pueden conocerlas o no; siguiendo las directivas del DJ cuando sea necesario.

Personajes
----------

Los Personajes están definidos por sus **Trasfondos** (algunos los llaman "**Clases**"), y el nivel en cada uno de ellos (por ejemplo, "*Cazarrecompensas 2*", "*Hacker 1*", "*Guerrero 3*", etc.). 
Los niveles en cada Trasfondo van de 1 a 5, y los personajes pueden tener múltiples Trasfondos en diferentes niveles.

.. csv-table:: 
   :align: center

   "NIVEL 1", "NIVEL 2", "NIVEL 3", "NIVEL 4", "NIVEL 5"
   "AFICIONADO", "ENTRENADO", "EXPERTO", "VETERANO", "MAESTRO"

Los personajes nuevos comunmente comienzan con tres niveles en uno, dos o tres Trasfondos, a elección del jugador [#]_.

.. [#] Esto quiere decir que puedes distribuir esos tres niveles como quieras, por ejemplo: "*Cazarrecompensas 2* y *Hacker 1*", o "*Cazarrecompensas 3*", o "*Cazarrecompensas 1*, *Hacker 1* y *Espía 1*", etc.

Cada sección de **Mundo** lista una serie de Trasfondos sugeridos para ese tipo de ambientación. Consulta con el DJ para saber cuáles de esos Trasfondos están disponibles en tu juego, y si hay otros Trasfondos adicionales que puedas elegir o incluso inventar.

Resolución de acciones
----------------------

Cuando un personaje intenta realizar una acción y el DJ determina que es riesgosa y tiene una posibilidad de fallar [#]_, el jugador **tira 2d6** y **suma el nivel de cualquier Trasfondo** [#]_ que sea relevante para esa acción, **± cualquier otro Modificador** que altere sus chances.

.. [#] alternativamente, el DJ puede determinar que la acción es **imposible** (fallaría automáticamente; el personaje debe intentar algo distinto) o **automática** (tendría éxito automáticamente; no hace falta tirar los dados).

.. [#] Si el **Trasfondo** no es del todo relevante para la acción, se aplica solo la mitad de su nivel (redondeado hacia abajo).

.. math::

   \text{Resultado} = 2d6 + \text{Niveles de Trasfondos Relevantes } \pm \text{ Modificadores}

Si el resultado iguala o supera la **Dificultad** establecida por el DJ, la acción es un **Éxito**. Si el resultado es menor que la **Dificultad**, la acción es un **Fallo**.

Dificultad
^^^^^^^^^^

El DJ determina la **Dificultad** de cada acción según su criterio, dependiendo de lo difícil que sea, y de las circunstancias del contexto. La Dificultad se expresa como un número entero, y comúnmente **el valor predeterminado es 8** [#]_.

.. [#] Ten en cuenta que las "probabilidades con un +0" consideran a un personaje que ni siquiera tiene un nivel 1 ("aficionado") en un Trasfondo relevante para la acción (o un personaje con niveles en Trasfondos relevantes pero que está sufriendo penalizaciones por Condiciones que cancelan sus modificadores hasta volver a +0). Esto significa que alguien sin ningún tipo de entrenamiento ni conocimiento (o alguien que sufre desventajas contextuales) que intenta una acción de dificultad Difícil (8) tendrá más chances de fallar que de lograrlo (42% de chances), lo cual es lógico. Esto fomentará a los jugadores a maximizar sus chances, intentando cosas en las que sus personajes están entrenados, o buscando formas de obtener Modificadores positivos a través de objetos, equipo, habilidades especiales, ayuda de aliados, etc. 

.. csv-table:: 
   :widths: 10, 20, 70
   :header: "DIFICULTAD", "DESCRIPCIÓN", "PROBABILIDAD"

   "4", "Trivial", "92% de chance con un +0"
   "5", "Muy Fácil", "83% de chance con un +0"
   "6", "Fácil", "73% de chance con un +0"
   "7", "Moderado", "58% de chance con un +0"
   "**8**", "**Difícil**", "**42% de chance con un +0**"
   "9", "Muy Difícil", "28% de chance con un +0"
   "10", "Extremo", "17% de chance con un +0"
   "11", "Improbable", "8% de chance con un +0"
   "12", "Casi Imposible", "2% de chance con un +0"

Modificadores
^^^^^^^^^^^^^

Los **Modificadores** se suman o restan al resultado de los dados, y pueden representar cualquier circunstancia que altere las chances de éxito de una acción. 

* **Circunstancial**: puede ser por contexto de la situación, o por la ayuda de un aliado, o por una complicación de un contrincante, o por una **Condición** relevante que sufre el personaje, etc. Usualmente es un ±1 o ±2. Si la acción se efectúa contra otro personaje, sus Trasfondos relevantes podrían aplicar como Modificadores negativos a la misma.
* **Objetos/Equipo**: Usualmente los objetos o equipo del personaje dan "*permiso narrativo*" [#]_, pero cuando el DJ considere que otorgan una ventaja significativa (en contraste con no poseer el objeto para la acción), pueden otorgar un Modificador positivo: +1 si el objeto o herramienta es común o apto para la situación; +2 si el objeto o herramienta es especial o ideal para la situación. 
* **Habilidades Especiales**: Usualmente las habilidades especiales de los personajes otorgan "*permiso narrativo*", aunque a criterio del DJ pueden considerarse como un *Modificador Circunstancial* (+1 o +2). 

.. [#] "Permiso narrativo" se refiere a que el personaje puede hacer algo que de otra manera no podría. Por ejemplo, un personaje que tiene un hacha puede intentar talar un árbol, mientras que un personaje sin hacha no podría hacerlo. En este caso, el hacha le da *permiso narrativo* para intentar la acción, pero no le otorga un Modificador positivo a la tirada. En otro ejemplo, un personaje con una Habilidad Especial "*volar*" tiene *permiso narrativo* para alcanzar lugares que un personaje sin esa habilidad no podría.

Efecto
^^^^^^

Cuan por encima o por debajo de la Dificultad se encuentra el resultado de la tirada, determina el **Efecto** de la acción, o el tipo de Éxito o Fallo.

.. csv-table:: 
   :header: "ÉXITO", "FALLO"

   "Excede la Dificultad por 1 ó 2: **ÉXITO NORMAL**", "Fallar por 1 ó 2: **FALLO NORMAL**"
   "Excede la Dificultad por 3 a 5: **ÉXITO ROTUNDO**", "Fallar por 3 a 5: **FALLO ROTUNDO**"
   "Excede la Dificultad por 6 o más: **ÉXITO ÉPICO**", "Fallar por 6 o más: **FALLO ÉPICO**"


Condiciones
-----------

las **Condiciones** son estados o circunstancias negativas que afectan a un personaje, en forma de palabras o frases cortas como "*brazo roto*", "*avergonzado*", "*envenenado*", "*cansado*", "*desorientado*", "*en pánico*", etc.

Pueden ser de tipo **Leve**, **Moderada** o **Severa**. Un personaje puede tener solo una de cada tipo. Si fuese a recibir una nueva Condición de un tipo que ya tiene, **debe obtener una de un tipo superior**. Si no puede, porque ya tiene Condiciones de todos los tipos superiores, entonces queda "**DERROTADO**" [#]_. 

.. [#] Un personaje **DERROTADO** queda incapacitado o fuera de la acción, y a merced de sus enemigos o aliados, dependiendo del contexto (inconsciente, ido, desencajado, catatónico, deprimido, etc.). 

Cuando se recibe una **Condición**, el DJ determina su descripción basándose en el contexto que la causó, y la gravedad de la misma. Por ejemplo, si un personaje recibe una **Condición Leve** por ser golpeado por un enemigo, el DJ podría describirla como "*raspón*" u "*hombro magullado*"; pero si ese personaje ya tenía una **Condición Leve** y la nueva que está sufriendo se incrementa a una **Condición Moderada**, podría describirla como "*corte profundo*" u "*hombro dislocado*". 

Cada **Condición** otorga un **Modificador negativo de -1** a las acciones del personaje donde sea relevante. Este modificador es acumulable (pudiendo otorgar -3 a un personaje que tiene una Condición de cada tipo).

* Las Condiciones **Leves** representan molestias o inconvenientes menores, como "*cansado*", "*avergonzado*", "*desorientado*", etc. Tardan minutos o horas en curarse.
* Las Condiciones **Moderadas** representan problemas o dificultades significativas, como "*intoxicado*", "*herido*", "*en pánico*", etc. Tardan horas o días en curarse.
* Las Condiciones **Severas** representan situaciones críticas o extremas, como "*pierna rota*", "*paralizado*", "*envenenado mortal*", etc. Tardan semanas o meses en curarse.

Curación y Recuperación
^^^^^^^^^^^^^^^^^^^^^^^

Las **Condiciones** se curan de manera *diegética*, es decir, a través de acciones o eventos dentro de la narrativa del juego, como descansar, recibir atención médica, superar un desafío personal, etc. Una vez se han tomado las medidas necesarias para curar una Condición durante el tiempo determinado por el DJ, el personaje se recupera de la misma: la borra de su hoja de personaje y pierde su Modificador negativo.

Aplicando y Recibiendo Condiciones
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Cuando se aplica o se recibe una Condición, el tipo (o gravedad) de la misma depende del **Efecto** de la tirada.

* Por defecto, con un **ÉXITO o FALLO NORMAL** se aplica o recibe una **Condición Leve**.
* Con un **ÉXITO o FALLO ROTUNDO** se aplica o recibe una **Condición Moderada**.
* Con un **ÉXITO o FALLO ÉPICO** se aplica o recibe una **Condición Severa**.


Experiencia y Subida de nivel
-----------------------------

Al final de una aventura, o cuando se cumple una hazaña significativa, cada personaje implicado **gana 1 Punto de Experiencia (PX)**.

Para **Subir de Nivel** en un Trasfondo, el jugador debe gastar una cantidad de PX de su personaje iguales al nuevo nivel que desea alcanzar. Por ejemplo, para ganar un nuevo Trasfondo en nivel 1, se gastaría 1 PX. Para subir de nivel 2 a nivel 3 en un Trasfondo, el jugador debe gastar 3 PX; para subir de nivel 3 a nivel 4, debe gastar 4 PX; y así sucesivamente [#]_. 

.. [#] Para subir de nivel en un Trasfondo, el jugador debe gastar PX en orden ascendente y secuencial. Por ejemplo, para subir de nivel 1 a nivel 3 en un Trasfondo, el jugador debe primero gastar 2 PX para subir a nivel 2, y luego gastar 3 PX para subir a nivel 3, totalizando 5 PX. No se puede saltar niveles al subir de nivel en un Trasfondo.

-----

Estas son las reglas básicas de 2d6Mundos. Las mismas deberían ser suficientes para jugar una buena partida de rol en cualquier mundo de fantasía o ficción. Consulta las reglas opcionales para agregar más complejidad y variedad a tu juego, y los preceptos para conocer las directrices de comportamiento dentro del grupo de juego. Finalmente, cada sección de Mundo tiene sus propias listas de Trasfondos y equipo, excepciones y reglas adicionales, que le dan sabor y personalidad a cada ambientación. ¡Explora los mundos y diviértete jugando!