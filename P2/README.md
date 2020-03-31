# DIU - Práctica 2

#### Jose Luis Gallego Peña

## A. Feedback Capture Grid

En la malla receptora de información (feedback capture grid) está representada la información obtenida de los usuarios de la práctica 1 y de mi propia experiencia, con el objetivo de abordar el diseño de la nueva aplicación.

Los cuatro apartados son:

- **Interesante/Relevante**, que indica los aspectos positivos que existen actualmente en el sitio analizado.
- **Críticas constructivas**, que indica los aspectos negativos que existen actualmente en el sitio analizado.
- **Preguntas a partir de la experiencia**, preguntas tienen las personas ficticias (y que pueden ser o no ser realizables) a partir de lo visto en los mapas de experiencia de usuario de la práctica 1.
- **Nuevas ideas**, ideas que sirven para mejorar el sitio a partir de la experiencia como desarrollador.

![](./feedbackcapturegrid.png)

La nueva aplicación a desarrollar consiste en una aplicación de economía colaborativa de compartir piso, basada en *Badi*, pero con varias mejoras que mejoren la usabilidad y den más posibilidades a la aplicación. 

La aplicación hará de intermediaria entre los inquilinos y los propietarios de los alojamientos. Los usuarios pueden poner en alquiler su alojamiento, indicando sus características, para que otros usuarios le contacten y acaben viviendo juntos. Además, contiene un sistema de notificaciones, indicando información por parte de la aplicación o avisos sobre el estado de los anuncios del usuario o mensajes en el foro, y un sistema de mensajes por el cual los usuarios pueden contactarse.

Los usuarios también pueden buscar tanto alojamiento como compañero de alojamiento en un buscador con varias opciones de filtro en base a las características predefinidas que pueden ponerse tanto en el alojamiento como en el perfil del usuario. 

Cada usuario tiene su perfil, en el cual podrá configurar sus datos más importantes y además sus características en cuanto a personalidad y gustos, para facilitar la experiencia de usuario y, entre otras cosas, poder buscar el compañero de piso que más se ajuste a los gustos y necesidades de cada uno. Además, el usuario puede decidir si quiere que su perfil sea público o no, para que otros usuarios puedan buscarle y proponerle compartir alojamiento.

Además de esto, se añaden las siguientes nuevas ideas:

- Un sistema de puntos que el usuario puede ir ganando por pasar tiempo en la página, de forma gratuita, para así premiar que el usuario pase tiempo usando el servicio. Podrá emplear estos puntos en hacer que sus anuncios suban en importancia en el buscador y así poder encontrar interesados más rápido.
- Añadir una nueva función que amplie la experiencia social. En función de las características de las personas en sus perfiles, se ampliarán los servicios añadiendo un foro en el cual compartir experiencias en alojamientos que hayan sido gestionados por la aplicación, para así crear una comunidad de usuarios que compartan sus experiencias y puedan finalmente conocerse y querer compartir alojamiento.
- Añadir un nuevo sistema de propuestas de alojamiento, que recomiende al usuario sitios de alojamiento y perfiles de personas afines a las características de su perfil.
- Compañero ideal: el usuario puede decidir si hacer público su perfil y que otras personas puedan buscarla en el buscador para poder contactar con este.

La gran mayoría de partes de la aplicación tendrán un botón de ayuda, que les redirigirá a la página de ayuda correspondiente.

El objetivo general de la nueva propuesta es que se centre más en las personas, teniendo la posibilidad de rellenar un perfil de usuario con varias características de la persona, para luego al filtrar las búsquedas, existan más posibilidades y poder buscar por tipo de persona.

Se pretende por tanto aumentar el "engagement" y el "retention" (que el usuario use mucho y con frecuencia el sistema, que lo necesite), pero que a la vez el usuario no pierda el tiempo, que visite con frecuencia el sitio pero para hacer justo todo lo que necesita sin perder el tiempo, estando satisfecho con el resultado ("happiness").

##       B. User/Task Matrix

Para identificar las tareas de la nueva propuesta de aplicación y su importancia se hará una matriz de tareas y usuarios (User/Task Matrix). En las filas se representan las tareas y en las columnas los grupos de usuarios que se pueden encontrar en la aplicación. En cada caso se representa la frecuencia de uso (Baja - B/Media - M/Alta - A) de esa tarea por parte del usuario. 

Las tareas en negrita son las que se consideran más críticas e importantes en la aplicación. Se tendrá más cuidado a la hora de diseñarlas en la propuesta final.

Se han ordenado las tareas de mayor a menor siguiendo el siguiente criterio de puntuación: B = 1 punto, M = 2 puntos y A = 3 puntos. Con esto se pretende distinguir fácilmente las tareas más importantes y más usadas de las que menos en un simple vistazo.

| Tareas/Usuarios                                              | Usuarios registrados | Usuarios no registrados | Administrador | Puntuación |
| ------------------------------------------------------------ | -------------------- | ----------------------- | ------------- | ---------- |
| **Buscar/Visitar un anuncio de habitación**                  | A                    | A                       |               | 6          |
| **Usar el chat de atención al cliente**                      | L                    | L                       | A             | 5          |
| **Buscar/Visitar otros perfiles**                            | A                    | L                       |               | 4          |
| **Contactar con un usuario**                                 | A                    |                         | L             | 4          |
| Recibir propuestas personalizadas de habitaciones y usuarios | A                    |                         |               | 3          |
| Comentar/Consultar el foro de experiencias                   | A                    |                         |               | 3          |
| Consultar la ayuda                                           | L                    | M                       |               | 3          |
| Consultar las notificaciones                                 | A                    |                         |               | 3          |
| Moderar el foro                                              |                      |                         | A             | 3          |
| Añadir notificaciones                                        |                      |                         | A             | 3          |
| Consultar mis anuncios                                       | A                    |                         |               | 3          |
| Cambiar ajustes de la aplicación                             | L                    | L                       | L             | 3          |
| **Modificar el anuncio de habitación**                       | M                    |                         |               | 2          |
| Valorar un anuncio de habitación                             | M                    |                         |               | 2          |
| Valorar a un usuario                                         | M                    |                         |               | 2          |
| Usar/consultar puntos de fidelidad                           | M                    |                         |               | 2          |
| Consultar mis favoritos                                      | M                    |                         |               | 2          |
| **Crearse un perfil**                                        |                      | L                       |               | 1          |
| Modificar el perfil                                          | L                    |                         |               | 1          |
| **Crear un anuncio de habitación**                           | L                    |                         |               | 1          |
| **Hacer público el perfil**                                  | L                    |                         |               | 1          |

Se han definido tres tipos de usuarios, que son los más comunes en cualquier página: usuarios registrados, usuarios no registrados y administradores.

Todas las tareas relacionadas con las dos funciones principales de la aplicación, buscar habitación y alquilar habitación, son las que se han indicado como más importantes, ya que son imprescindibles para el funcionamiento normal de la aplicación.

## C. Information Architecture: Sitemap/Labelling

Mediante las técnicas de arquitectura de la información (Sitemap y Labelling) creamos la organización y estructura de los contenidos de una aplicación, que nos sirve para entender dónde estamos como usuarios y dónde está la información desde donde estamos. 

En el sitemap vemos representada la estructura de la página en un mapa, mientras que en el labelling describimos la función de todas aquellas etiquetas que aparecen en el mapa, con su traducción al inglés y, si tiene, el icono asociado a esa etiqueta.

El labelling está adaptado a las normas de escritura de la web, es decir, usa lenguaje simple y claro, fácil de encontrar y fácil de saber a dónde nos lleva, para facilitar a los usuarios que cumplan rápidamente sus objetivos. Las etiquetas accesibles desde la página principal son simples de entender, están a primera vista y realizan las funciones principales de la aplicación. Su objetivo principal es unificar la forma en la que se dice algo en el entorno de la aplicación.

![](./sitemap.png)

| Etiqueta                    | Descripción                                                  |
| --------------------------- | ------------------------------------------------------------ |
| Página principal            | Página principal de la aplicación, accesible al iniciar la aplicación. Contiene el menú inferior, el menú lateral, las opciones de publicar habitación y experiencia en compañia, y recomendaciones personalizadas. |
| Publicar habitación         | Rellena un formulario con los distintos datos de la aplicación que quieres publicar. |
| Modificar habitación        | Permite modificar todos los datos de la habitación que has publicado. |
| Hacer público el perfil     | El usuario hace público su perfil para que otros usuarios le puedan buscar y contactar. |
| Buscar                      | Buscar alojamiento o personas que buscan alojamiento, según distintos parámetros, principalmente localización. |
| Filtrar búsqueda            | El usuario filtra la búsqueda tanto de usuarios como de habitaciones según unos parámetros establecidos. |
| Habitación                  | Anuncio de una habitación, con sus fotos, características y enlaces a los perfiles de compañeros y propietarios que forman parte de él. |
| Reservar habitación         | El usuario decide reservar una habitación y esperará a que el propietario le informe. |
| Perfil usuario              | Perfil de otro usuario de la web, con su foto, caracterísitcas y contacto. No puede modificarse. |
| Contactar con usuario       | El usuario decide contactar con otro usuario, abriendo un chat de mensajes. |
| Mi Perfil                   | Tu perfil, con su foto, características y contacto. Puede modificarse. |
| Modificar perfil            | Permite modificar todos los datos de tu perfil.              |
| Mis Notificaciones          | Notificaciones del sistema o para cuando alguien interactua de alguna manera (valorando, comentando, etc) alguno de tus anuncios o foros. |
| Mis Mensajes                | Mensajes del usuario con otros usuarios.                     |
| Mis Favoritos               | Anuncios y perfiles que has marcado como favoritos, para acceder a ellos más fácilmente. |
| Añadir anuncio a favoritos  | Añade un anuncio a tu lista de favoritos.                    |
| Añadir usuario a favoritos  | Añade un usuario a tu lista de favoritos.                    |
| Foro de experiencias        | Foro en el que los distintos usuarios pueden compartir sus experiencias y debatir sobre cualquier tema, para así formar comunidad. |
| Tema foro                   | Cada uno de los temas de los que está compuesto el foro. Contiene los mensajes de este. |
| Enviar comentario tema foro | Enviar un comentario a un tema en un foro, que mostrará tu nombre y el mensaje asociado. |
| Crear tema foro             | Crea un tema en el foro, con un título, mensaje y nombre de tu perfil asociados. |
| Mis anuncios                | Lista de los anuncios de habitaciones o de experiencia de compañero que has publicado. |
| Ayuda                       | Sección con un chat de atención al cliente, una lista de preguntas frecuentes (FAQ) y contacto por si tienes algun problema. |
| Chat ayuda                  | Chat en tiempo real con el servicio de atención al cliente.  |
| Enviar mensaje chat ayuda   | Enviar al servicio de atención al cliente el mensaje que has escrito. |
| Valorar anuncio/usuario     | El usuario da una valoración de entre 0 y 5 estrellas al anuncio o usuario. |
| Acerca De                   | Información sobre la aplicación y copyright.                 |
| Ajustes de la aplicación    | Diversos parámetros que el usuario puede configurar en la aplicación: activar/desactivar notificaciones, modo nocturno y cerrar sesión. |

## E. Wireframes

![](w1.jpg)

![](w2.jpg)