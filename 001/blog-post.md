Ultimamente no he escrito mucho acerca de nuevos temas, principalmente debido a que he estado ocupado con trabajo y mi tiempo libre lo uso para mejorar [mi sitio personal][1]; así que decidí que una buena manera de publicar contenido útil sin tener que invertir tanto tiempo a investigar y editar tanto como al hacer un tutorial podría ser documentar mi toma de decisiones al desarrollar algo y así poder ampliar la perspectiva de otros con respecto a la forma en que realizan sus sitios.


## Proyecto

En este post sólo quiero enfocarme en el homepage de este sitio y analizar como fue la toma de decisiones o eventos que me llevaron a elegir tanto el contenido como el diseño del mismo. No entraré en detalles técnicos ya que quiero enfocarme más en entender el "por qué" que el "cómo".


## Motivación del diseño

Algo que he aprendido haciendo diseño web es que el contenido de un sitio siempre debe estar basado principalmente en el objetivo del mismo o lo que se quiere expresar y no simplemente seguir el "estándar" o "lo que está de moda".

Aquí esta una imagen del diseño original para la homepage de mi sitio.

![ORIGINAL_DESIGN]()

No es nada complejo pero a la vez siento que este tipo de diseño con tanto espacio ayuda a definir bien los tipos de contenido a la vez que no satura de información al usuario.

Si bien tal vez es una página demasiado simple, realmente no intento que el usuario pasé mucho tiempo aquí. Esto podría parecer contra-intuitivo pero el motivo por el cuál no quise poner el énfasis en esta página, aún siendo la principal, es debido a que las audiencias a la cual intento llegar con este sitio son dos con objetivos totalmente diferentes.

La audiencia principal en la cual me enfoco son los desarolladores. La razón inicial por la cual comencé un sitio web personal hace más de un año fue para acercar temas actuales e importantes en el desarrollo web a la comunidad en español. Para esta audiencia, tanto la parte del [blog][3] como la de [experimentos][4] son relevantes pero tal vez no estén interesados en mi información personal o mi experiencia previa.

El segundo tipo de audiencia al cual quiero apuntar obviamente siendo este mi sitio de portafolio, es a reclutadores y clientes potenciales. Para ellos es el caso contrario. En la sección de [info][2], en la de [proyectos][5] y en mi [cuenta de github][6] es donde encuentran el contenido que a ellos les interesa principalmente pero lo más probable es que sólo estén de paso y no se den el tiempo de revisar mis experimentos o los artículos que publico en mi blog.

Entonces, teniendo en consideración que ambas audiencias buscan contenido diferente, me pareció incorrecto priorizar una sobre la otra y mostrar una página de entrada que sólo resultara atractiva para una de las dos. Por ello decidí por un diseño simple y sin distracciones que te dirige inmediatamente al contenido que buscas pero al mismo tiempo te informa que además hay otras secciones que te pueden interesar.

## Componentes

Básicamente la página se compone 4 componentes principales:

- Header titular
- Navegación
- Switch de idioma.
- Video de fondo.

Y precisamente en ese orden es la importancia de cada uno de los componentes.

#### Header

Como elemento principal está el header. Obviamente siendo mi sitio personal, quiero hacer notar mi nombre y marca. Por ello el header esta siempre en la parte superior de la pagina y de un color claro que contrasta suficientemente con el fondo como hacerlo notorio. También el posicionamiento del logo a en la parte izquierda del header ayuda a centrar un poco el texto con mi nombre, lo que sirve para hacer aun más énfasis en él.

También, hecho de que la ultima parte del subtitulo cambie dinámicamente cada vez que visitas la página sirve para expresar diferentes facetas de mí sin necesariamente saturar la página de información. También es un buen easter egg.


#### Navegación

La navegación consta de dos partes: El fondo y el contenido. También este es el segundo elemento principal y hacía donde quiero dirigir la atención principalmente. Al ponerle un overlay oscuro al video de fondo para opacarlo y después colocar el fondo de la navegación en blanco crea un contraste bastante marcado que permite dirigir la atención hacia el contenido (los links).

La forma triangular del fondo no tiene ningún significado profundo realmente, sólo fue algo que sentí ganas de hacer y que me agrada el efecto que le da al diseño. Este también fue inesperadamente el problema técnico que más tiempo consumió debido al soporte de navegadores y diferentes resoluciones, pero eso realmente es un tema que merece todo un post aparte.


#### Switch de idioma

Este fue un elemento situacional que agregué después de haber implementado la i18n en el resto del sitio, ya que originalmente no tenía contemplado aplicar distintos idiomas pero mientras desarrollaba la aplicación sentí la necesidad de hacerlo para alcazar una mayor audiencia. Realmente esta no es algo critico para el funcionamiento de la página así que no tiene sentido resaltarlo de más o terminaría desviando la atención de la parte de navegación y el header, que es donde esta lo importante; así que simplemente queda aislado en una esquina sin tanto contraste para no resaltar.


#### Video de fondo

No hay mucho que decir aquí, simplemente quería algo que le diera un toque personal a la página y rompiera con esa sensación de contenido estático. El hecho de que sea una escena de Yuru Yuri, para ser honesto, fue casualidad más que una decisión premeditada (primer webm divertido que encontré revisando 4chan).


## Conclusión

Si algo quisiera que te llevaras de este devlog, no es que tan cool es mi diseño (aunque lo es) o que tanto contiene, sino que tomes en cuenta como tanto la motivación y objetivo del proyecto como el uso que se le da a una página y el tipo de usuario al que tenemos planeado apuntar, deben ser factores que considerar cuando diseñas un sitio pues, como dije al inicio de este post, el contenido de un sitio siempre debe estar basado en el objetivo del mismo o lo que se quiere expresar y no simplemente seguir el "estándar" o "lo que está de moda".


 [1]: https://datyayu.xyz
 [2]: /about
 [3]: /blog
 [4]: /experiments
 [5]: /projects
 [6]: https://github.com/datyayu