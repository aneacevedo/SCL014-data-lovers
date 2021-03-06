# DATA LOVERS => Pokémon Go: Pokédex

## Índice

* [1. Definición del Producto](#1-definicion-del-producto)
* [2. Perfil del Usuario](#2-perfil-del-usuario)
* [3. Historias de Usuario](#2-historias-de-usuario)
* [4. Prototipos](#3-prototipos)
* [4. Imagen Final del Proyecto](#4-imagen-final-del-proyecto)

***

## 1. DEFINICIÓN DEL PRODUCTO


## 1.1 Finalidad del Producto
"Pokémon Go: Pokédex" nace con la intención de brindar información relevante para los jugadores de Pokémon Go y ayudarles a tomar decisiones respecto a su estrategia de juego, basada en datos duros: información que puedan revisar desde cualquier dispositivo, de fácil lectura e interpretación y que esté a mano de cualquier aficionado al juego.

## 1.2 Origen de Pokémon Go: Pokédex
Previo a la creación del producto, se determinó que cierta data debía estar incluída a como diera lugar, por lo cual el presentar a todos los Pokémon por el orden de la Pokédex nos parecía fundamental (del #001 al #251). Tanto en la serie como en el juego, el orden ha sido un factor determinante a la hora de insertarse en el mundo de Pokémon. Sin importar el nivel de experiencia del jugador, siempre habrá tres pokémones clásicos identificables: Bulbasaur, Charmander y Squirtle, cada uno presentado junto a sus evoluciones, mostrando su imagen, breve descripción, características físicas, tales como peso y estatura, y su tipo (planta, bicho, fuego, agua, tierra, etc.) y este orden es lo que el jugador espera.
Podemos inferir que de toda la data disponible, las siguientes nos permiten ofrecer una experiencia distinta al usuario: tasa de huida base, tasa de captura base, oportunidad de spawn, resistencia base (stamina), poder de combate y salud (máximo).


## 2. PERFIL DEL USUARIO

* **¿Quiénes son los principales usuarios de producto?** 

La recabación de datos se realizó mediante _Google Forms_.
El rango etario de los usuarios que respondieron a nuestra encuesta va de los 19 a los 35 años, de los cuales el 66% está entre los 19 y 25 años.
En su mayoría viven con su familia, son de clase media, dada la situación actual muchos de ellos se encuentran desempleados o estudiando remoto.

![json-interfaz](https://i.imgur.com/SQYg0YR.png)

Son nativos digitales que destinan una parte importante de su tiempo al ocio y, para muchos de ellos, Pokémon Go es un juego que es parte de sus rutinas.
Para hacer una estimación, si un usuario utiliza un incienso para atraer pokémones, el efecto dura 1 hora; si el usuario deja un sebo en una pokeparada, el efecto dura 30 minutos; las incursiones ocurren en momentos específicos del día y requieren pases especiales. En otras palabras, ser jugador de Pokémon Go exige disciplina para poder cumplir misiones, las cuales son premiadas con polvos estelares, pokebolas, bayas, 
pociones, medicina para revivir, huevos, entre otros, lo que motiva al usuario a conectarse incluso varias veces en un solo día: el usuario está pendiente de su progreso en el juego y ***la posibilidad de jugar en comunidad con sus amigos estimula su platea externa, lo cual también ayuda a mejorar su rendimiento en el juego.***

![json-interfaz](https://i.imgur.com/KmQbvi6.png)

* **¿Cuáles son los objetivos de estos usuarios en relación con el producto?**

Queremos que nuestros potenciales usuarios confíen en nuestra aplicación y sientan que junto a ella pueden mejorar su rendimiento en el juego.
La confianza es primordial, considerando que una gran cantidad de aplicaciones relacionadas a Pokémon Go pueden terminar en el baneo de sus cuentas, al hacer uso de data que se considera "tramposa". Para ello, la implementación de la identidad gráfica es primordial.
Nuestro usuario es analítico y quiere hacer comparaciones entre pokémones, desea comprender la jerarquía entre ellos y apreciar sus características, para hacer uso de esa data cuando tenga la posibilidad de ingresar al juego.

* **¿Cuáles son los datos más relevantes que quieren ver en la interfaz y por qué?**

Al momento de jugar Pokémon Go, nos damos cuenta de que en el momento de que un pokémon es capturado se despliega una ficha informativa, siendo aquella que gana en jerarquía **Puntos de Combate**. Esta información está sobre la imagen principal de cada pokémon. En nuestra encuesta, esto se corrobora, ya que es el dato más 
requerido por los jugadores:

![json-interfaz](https://i.imgur.com/NmF2SE5.png)

* **¿Qué tipo de interfaz les gustaría a nuestros usuarios?**

De forma casi unánime, nuestros potenciales usuarios mencionaron que les gustaría una app que utilice los colores y que tenga la identidad gráfica del juego. 
En otras palabras, utilizar una gama de colores que va desde matices de verde al azul petróleo, ya que les da más confianza. 
A continuación dejamos otros datos obtenidos que hemos considerado al momento de prototipar:

![json-interfaz](https://i.imgur.com/5FTcmL6.png)

![json-interfaz](https://i.imgur.com/LOym78I.png)

![json-interfaz](https://i.imgur.com/NWeUBXK.png)


* **¿Cuándo utilizan o utilizarían el producto?**

Nuestros potenciales usuarios harían uso de "Pokémon Go: Pokédex" en tiempos intermedios de ocio con fin de complementar sus conocimientos técnicos de Pokémon, 
pudiendo ordenar la información en orden ascendente o descendente, filtrar por tipo de Pokémon, de modo que los guíe a determinar cuál de sus Pokémon capturados será más útil en una incursión (raid), cuáles les faltan para completar la Pokédex, qué Pokémon resistirá mejor en un gimnasio o en algún encuentro con el equipo Rocket en alguna de las pokeparadas.

* **User Personas**

Luego de las encuestas y poder entrevistar a algunos de los usuarios para conocerlos, pudimos elaborar tres perfiles. Si bien todos ellos poseen niveles altos en el juego, sus motivaciones varían considerablemente.


1. Por un lado tenemos a Benjamín, quien ha estado jugando desde que la aplicación está disponible. Juega todos los días y destina por lo bajo 4 horas diarias a jugar. Siempre está pendiente de los eventos, raids, community days, horas destacadas, entre otros. Es un **jugador competitivo** que está constantemente revisando páginas con información relacionada al juego. Ha generado comunidad gracias al juego, llegando a reunirse hasta con 30 personas para completar alguna misión. Por lo general tiende a reclutar nuevas personas para jugar. Su actual misión en el juego es duplicar los puntos de experiencia que posee en el presente.

![json-interfaz](https://i.imgur.com/LF7VAK4.jpg)


2. Por otro lado tenemos a Claudio, un jugador que también está en el nivel más alto posible en el juego, pero está a varios millones de puntos de experiencia de Benjamín. Juega todos los días, pero su enfoque no es competitivo. Claudio tiene un perfil de **jugador coleccionista**, le gusta atrapar nuevos pokémon en todas sus versiones, y como su propósito es completar la pokédex, está inclinado a buscar información de pokémon variocolor. Claudio es una persona más nostálgica en relación al juego: tuvo la oportunidad de ver la serie en televisión a una muy temprana edad, jugar cartas Pokémon al crecer, y de ahí viene su espíritu de "atraparlos a todos", independiente de otros plus que pueda tener el juego.

![json-interfaz](https://i.imgur.com/0jKlHLw.jpg)

3. Por último tenemos a Denisse, una jugadora que a diferencia de Benjamín y Claudio, lleva dos años menos jugando. Juega menos de 4 veces a la semana, y cuando lo hace es por períodos cortos. El juego capta su atención y la entretiene, pero también suele distraerse con otras cosas. Más que jugar por iniciativa propia, es porque sus amigos lo hacen y el juego es una posibilidad de hacer algo conjunto, por ende es más una **jugadora social**. Le cautiva el diseño de los pokémon y le entretiene ir completando su pokédex. Al ser una jugadora de tipo social, para ella es muy importante que cualquier app relacionada le pueda brindar la opción de volver a conectar con sus amistades.

![json-interfaz](https://i.imgur.com/80i2bz8.jpg)


## 3. HISTORIAS DE USUARIO

A raíz de nuestra investigación, decidimos priorizar las siguientes Historias de Usuario:

**HU1: "Yo como jugador de PG, quiero visualizar los 251 pokémon por el orden designado en la pokédex, para saber cuáles me faltan".**

C.A.:
- [x] El usuario puede ver los 251 pokémon desde el inicio
- [x] Los 251 pokémon están ordenados (primero Kanto, luego Johto)
- [x] Cada pokémon tiene su número, nombre, imagen y tipo identificado en la ficha visible
- [x] El color de fondo de los pokémon corresponde también a la pokédex de la generación a la cual pertenecen

D.T.: 
- [x] Se respeta el diseño de prototipado
- [x] El diseño está hecho con flexbox
- [x] Se está trabajando con selectores de clase en CSS
- [x] Se utiliza html semántico
- [x] Se utiliza html dinámico
- [x] El código ha sido hecho en pair-programming
- [x] El código está utilizando arrays y objects
- [x] Se implementa función para mostrar a los 251 pokémon
- [x] El código está en el repositorio actualizado

**HU2: "Yo como jugador de PG, quiero conocer el poder de combate de un pokémon, para competir en gimnasios e incursiones".**

C.A.:
- [x] Cada Pokémon tiene visible su máximo PC en la ficha
- [x] El usuario puede ordenar los pokémon según su poder de combate (ascendente)
- [x] El usuario puede ordenar los pokémon según su poder de combate (descendente)

D.T.:
- [x] Se respeta el diseño de prototipado
- [x] Se utiliza html semántico
- [x] Se utiliza html dinámico
- [x] Se trabaja en pair-programming
- [x] El código utiliza arrays (sort, reverse) y objects
- [x] El código está actualizado en el repositorio
- [x] Se implementa función para ordenar a los 251 pokémon según PC
- [x] Se recibe feedback de diseño visual por parte de otras duplas

**HU3: "Yo como jugador de PG, quiero clickear en las fichas y que se den vuelta como cartas para ver la información adicional de cada pokémon".**

C.A.:
- [x] Cuando el usuario elige a un Pokémon, la ficha se da vuelta como una carta y muestra información adicional
- [x] La transición del giro de la ficha es suave
- [x] El color del reverso es el mismo que el frontal (correspondiente a cada generación)

D.T.:
- [x] Se respeta el diseño de prototipado
- [x] Se utiliza html semántico
- [x] Se utiliza html dinámico
- [x] Se trabaja en pair-programming
- [x] La transición se crea con CSS en stylesheet
- [x] El código está actualizado en el repositorio
- [x] Se implementa función para obtener la información adicional de cada pokémon

**HU4: "Yo como jugador de PG, quiero saber cuáles son las chances de spawn de un pokémon, para priorizar las capturas".**

C.A.:
- [x] Cuando el usuario elige a un Pokémon, las chances de spawn son mostradas al reverso de la ficha
- [x] La información es entregada de forma clara y concisa

D.T.:
- [x] Se respeta el diseño de prototipado
- [x] Se utiliza html semántico
- [x] Se utiliza html dinámico
- [x] Se trabaja en pair-programming
- [x] El código está actualizado en el repositorio

**HU5: "Yo como jugador de PG, quiero conocer la tasa de captura base de un pokémon, para optimizar mis recursos (pokeballs, bayas, inciensos, etc.)"**

C.A.:
- [x] Cuando el usuario elige a un Pokémon, la tasa de captura base es mostrada al reverso de la ficha
- [x] La información es entregada de forma clara y concisa
 
D.T.:
- [x] Se respeta el diseño de prototipado
- [x] Se utiliza html semántico
- [x] Se utiliza html dinámico
- [x] Se trabaja en pair-programming
- [x] El código está actualizado en el repositorio
- [x] Se realiza test de usabilidad al menos a 3 usuarios
- [x] Se afinan detalles finales

* **Planificación**

Link a Trello: https://trello.com/b/qhvhu0vq/data-lovers

* **Adicional a Historias de Usuario**

1. Para proveer una navegación personalizada, hemos creado una sección de login al momento de ingresar a la aplicación, solicitando un username y password.
2. En el header, el usuario recibe un pequeño texto de bienvenida junto a una sección de geolocalización.
3. Se crearon opciones para que el usuario pueda organizar la Pokédex con los siguientes criterios: A-Z, Z-A, n° menor (primero), n° mayor (primero).
4. Se crean filtros para que el usuario pueda elegir un tipo de Pokémon específico y la Pokédex retorne solo aquellos que cumplan con la condición.
5. El menú desplegable contiene las siguientes secciones: Home, Perfil, Calendario Pokémon, Noticias, Poképedia, FAQ y Cerrar Sesión.

* **Test de Usabilidad**

Los test de usabilidad se realizaron con 3 usuarios y se testearon los diseños tanto para desktop como para mobile.
Se le solicitó a los usuarios realizar las siguientes tareas, a medida que ellos iban haciendo observaciones y describiendo lo que hacían:

1. Ingrese a la aplicación con usuario y password
2. Ordene los pokémon según su PC
3. Ordene a los pokémon alfabéticamente
4. Filtre a los pokémon según su tipo
5. Busque a un pokémon con la barra de búsqueda
6. Busque información adicional de cada pokémon
7. Encuentre el menú de la aplicación
8. Cierre sesión

De dichos test de usabilidad, se desprendió lo siguiente:

![json-interfaz](https://i.imgur.com/8gQq8gU.jpg)

* **S.U.S.**

Luego del testeo de usabilidad, se encuestó a los usuarios para evaluar la aplicación cuantitativamente.
Los usuarios pudieron evaluar con una escala del 1 al 5, siendo 1 Totalmente en Desacuerdo y 5, Totalmente de acuerdo.

* +80: Muy Bueno
* Entre 50 y 80: Regular
* -50: Malo

![json-interfaz](https://i.imgur.com/awaI13O.jpg)


* **Feedback adicional de los usuarios**

Dejamos a continuación algunos de los comentarios adicionales que recibimos de nuestros potenciales usuarios, esto a considerar para futuras mejoras 
al producto final y nuevas historias de usuario:

1. "Esta aplicación la recomendaría a alguien que esté usando por primera vez el juego, porque la información entregada en otros sitios puede resultar muy compleja de analizar y puede saturar o asustar al jugador. Esta app usa los mismos íconos del juego, los mismos colores y eso me gusta. Puede resultar agotadora la navegación si es que quieres encontrar algún pokemon scrolleando desde el celular. Los filtros no se suman entre sí, por lo tanto si quieres encontrar un tipo de pokémon de cierta generación, igual sigue mostrando los de ambas generaciones. Es útil poder filtrar por tipo para determinar qué pokémon sirve para una raid. Me gustó el diseño y la identidad gráfica, es amigable". 
2. "Me gustaría que tuviera filtro o información de pokémon variocolor. Ojalá que tuviera una sección que tuviera las raids del momento. Desde el celular es más difícil verificar que las tarjetas se dan vuelta".
3. "Quizás la aplicación necesite una sección educativa para explicar los tipos de pokémon y su iconografía. Me gustaría que la aplicación tuviera trivias, ránkings, de modo de ir aprendiendo más de Pokémon. Creo que también sería agradable ver alguna galería donde la gente pueda subir fotos de eventos, de sus pokémon, etc. Me gusta que sean las gráficas originales". 


## 4. PROTOTIPOS

### 4.1 Colores y Tipografía

![json-interfaz](https://i.imgur.com/nsI5LNP.jpg)

* **Paleta de Colores:**
En el juego de Pokémon Go las gradientes son parte del diseño y se han incorporado, a su vez, al diseño de la aplicación, tratando de que sean lo más equilibradas posibles para no tensar sobre el uso de este recurso gráfico que suele verse excesivamente saturado en muchas ocasiones.

1. Gradientes azul-verde y verde-aguamarina: Colores que transmitan la idea de crecimiento, fertilidad, generosidad, natural, estabilidad, armonía, calma y confianza.
2. Gradientes con matices de púrpura: Colores que transmitan la idea de imaginativo, creativo, nostálgico.
3. Gris y blanco para los textos: Elegidos por tema de accesibilidad y para contrastar con los colores de fondo o hover.


* **Tipografía:**
Para todo el cuerpo del producto, se trabajó con tipografía Flexo, letra de tipo sans-serif que evoca la sensación de estar viendo un dispositivo digital, lo cual se condice con la idea de que la aplicación funcione finalmente como una Pokédex Personal.


### 4.2 Prototipo de Baja Fidelidad

* **Versión Desktop**

![json-interfaz](https://i.imgur.com/r8NoKx2.jpg)

![json-interfaz](https://i.imgur.com/unwTr39.jpg)

![json-interfaz](https://i.imgur.com/kvzPGrG.jpg)

* **Versión Mobile**

![json-interfaz](https://i.imgur.com/YEuo2pa.jpg)

![json-interfaz](https://i.imgur.com/78NErBq.jpg)

![json-interfaz](https://i.imgur.com/w08CWMG.jpg)


### 4.3 Prototipo de Alta Fidelidad

* **Primera Versión**

Link Figma: https://www.figma.com/proto/rLOtyW2DbAwtncAurx10AJ/PG-desk?node-id=8%3A1&scaling=min-zoom

![json-interfaz](https://imgur.com/6VIcUKv.jpg)

![json-interfaz](https://imgur.com/xqCYf4n.jpg)

![json-interfaz](https://imgur.com/pIZ1PQK.jpg)


* **Segunda Versión**

Link Figma: https://www.figma.com/proto/RvRbVwLNH54JS5b2ORQyw6/Pok%C3%A9mon-Go-Pok%C3%A9dex?node-id=1%3A2&viewport=-1422%2C513%2C0.5&scaling=min-zoom

![json-interfaz](https://i.imgur.com/A8Mg36F.jpg)


## 5. IMAGEN FINAL DEL PROYECTO

**Link a proyecto:** https://catalinavega.github.io/SCL014-data-lovers/

* **Versión Mobile**

![json-interfaz](https://i.imgur.com/JojZxwW.jpg)

![json-interfaz](https://i.imgur.com/st6GuS9.jpg)

* **Versión Tablet**

![json-interfaz](https://i.imgur.com/7dVEzpC.jpg)

* **Versión Desktop**

![json-interfaz](https://i.imgur.com/Jc8cg49.jpg)

![json-interfaz](https://i.imgur.com/l5Srjhs.jpg)


DEVELOPERS: Anelisse Acevedo + Catalina Vega
