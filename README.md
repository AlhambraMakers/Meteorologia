![Logo Alhambra Makers](https://avatars3.githubusercontent.com/u/27811355?v=3&s=150  "Logo Alhambra Makers")


Estación meteorológica / de calidad del aire / astronómica de Granada Makers
===

Este proyecto (aun en fase de tormenta de ideas) pretende crear una estación de medición de variables meteorológicas (presión, temperatura, humedad, lluvia...), de calidad del aire (partículas, gases...) y astronómicas (calidad del cielo nocturno, movimiento de estrellas / planetas, detección de meteoros).

La idea fundamental no es solo hacer una estación que permita recopilar estos datos (que de estas ya hay muchas libres en Internet), sino en crear un auténtico proyecto de ciencia ciudadana que permita monitorizar estas variables y fenómenos.

Este documento por ahora es una recopilación de ideas / información sin mucha estructura que se irá perfeccionando poco a poco.



¿Qué podemos monitorizar?
---


### Meteorología

+ Temperatura
+ Humedad
+ Presión atmsférica
+ Lluvia
+ Viento (dirección + intensidad)
+ Presencia de nubes
+ Detección de rayos
+ Radiación ultravioleta

### Calidad del aire

+ Partículas
+ Gases

### Astronomía

+ Movimientos celestes (sol, luna, estrellas, planetas)
+ Detección de meteoros / bólidos
+ Detección de radio?





Proyecto de Ciencia Ciudadana
---

El presente proyecto no tiene como fin último el crear un multi sensor, sino crear un verdadero proyecto de ciencia ciudadana en donde los interesados puedan participar en el mismo de varias maneras distintas:

+ Creando los sensores que se desarrollen
+ Instalando los sensores que se desarrollen
+ Manteniendo / revisando los sensores que se desarrollen
+ Manteniendo la infraestructura de datos de los mismos
+ Haciendo informes con los datos obtenidos
+ Revisando los datos obtenidos
+ Haciendo tareas de divulgación relacionadas con el proyecto (creacion de materiales didácticos, dando charlas al respecto, haciendo entrevistas en los medios, montando stands en la noche de los investigadores...)
+ Consiguiendo financiación
+ ...

### Posibles claros interesados

+ Makers
+ Profesores de secundaria
+ Profesores de primaria
+ Encargados de instituciones como bibliotecas
+ Asociaciones de astronomía



### Posibles vías de financiación

+ Colegios / Institutos: AMPAs y demás
+ Junta de Andalucía: Todos los años sacan una convocatoria para actividades de divulgación de la ciencia, etc.
+ Empresas


Infraestructura de datos
---

Cada recolector de datos (con mútliples sensores) mandará cada cierto tiempo su información a un nodo central donde se almacenará. Ese nodo central podrá ser consultado mediante una aplicación web o, si alguien tiene ganas de hacerlo, mediante una app para móvil. El tratamiento de alguna información puede ser complejo (como el de la deteccion de bólidos) por la cantidad de información que se captura / procesa.

Si se usan servicios externos, que sean los más libres posibles / con visos de no desaparecer a la mínima de cambio y reemplazables.


Tecnologías / cacharrines que podemos usar
---

A RELLENAR



Carcasa / Alimentación / Comunicación de los cacharros
---

Aquí tendremos que proponer como hacer una carcasa estanca, como alimentarla (desde enchufe a baterías y placas solares) y como comunicarlas (cableado / WIFI / Bluetooth / Radio).




Otros proyectos libres existentes en los que inspirarse / información
---

Aquí estaría bien no solo poner enlaces a otros proyectos, sino un breve resumen de los mismos.

+ https://github.com/oslugr/contaminAND

+ Hay un proyecto de la OSL de hacer pequeñas estaciones meteorológicas. Puede ser interesante fusionar las ideas / colaborar, etc.


Otras cosas
---

+ Un tema complicado es la estandarización / uniformización de las medidas (los sensores son difíciles de calibrar). De hecho la mayoría de las estaciones no son comparables entre sí sin que un profesional las analice y compruebe que las mediciones siguen una métrica similar. Para cosas "de andar por casa" no tiene importancia, pero si se le quiere sacar el máximo provecho es interesante indagar en el tema.

+ Una idea interesante puede ser que sea módular. Dado que algunos sensores pueden ser caros / complejos, lo mismo se puede desarrollar algo modular, de tal manera que alguien monte solo los sensores que le interesen sin que esto resulte complejo.

+ En ningún caso la financiación debería entenderse como simplemente para fabricar los cacharros y darlos por ahí. La gracia está en que los interesados, con toda la ayuda necesaria puedan desarrollar sus cacharros y conectarlos a la red de datos propouesta, sacar informes, y desarrollar proyectos educativos relacionados. De hecho experiencias pasadas que se ven por ahí de cacharros que "se regalan" (a colegios, etc) al final no se usan o se usan mal. Sin embargo si los HACEN, los usan más y los cuidan mejor (esto es una opinión que puede no ser compartida / borrada / modificada).

+ En relación con el punto anterior, estaría bien aclarar en algún sitio los objetivos concretos que se persiguen en el proyecto.


