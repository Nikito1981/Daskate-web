Presentacion final de mi proyecto 

Hola , soy Nicolas Pandolfelli y voy a hablar acerca de mi proyecto. Para comenzar, la decision de realizar la pagina de una banda tiene que ver 
con que soy músico y la idea de realizar este curso se vio unida a mi participacion musical junto a esta banda. No tenia mucha idea acerca de como 
realizar un sitio web y me dieron ganas no solo de aprender, sino tambien de poder buscar una alternativa laboral para el futuro. Quizas mi eleccion 
fue muy distinta a la del resto de mis compañeros pero en cuestion del aprendizaje recibido creo haber aplicado casi en su totalidad todo el conocimiento
recibido en este curso. 

Sobre mi proyecto, con dificultades y mucha frustracion por momentos, he conseguido a esta altura tener cierto conocimiento sobre la logica de como armar un
un sitio web con las herramientas aprendidas. 

Cuando comenzamos el curso realmente no tenia mucha nocion acerca de como se comenzaba a plantear la idea de proyecto y comenzando con los wireframes 
decidi realizar 5 paginas en mi sitio web. Cuando realice los wireframes tuve cierta obsesion por rellenarlos con lo que luego usaria como el contenido. 
Entendi que el wireframe es algo mucho mas simple una vez que ya los habia preparado. A continuacion dejo los links de los primeros bocetos de mi sitio 
para escritorio y para dispositivos mobile.

Home
https://whimsical.com/index-html-RNhjWgsDYp2HNTjk4GbTct
Historia
https://whimsical.com/historia-html-3DsJaJGVYY6Y47hhfCp7v6
Musica
https://whimsical.com/musica-html-UJnFdffJCmSw3Td9fLDsXd
Videos
https://whimsical.com/videos-html-3cLiUwpU4X92MfcNT7tDX5
Merch
https://whimsical.com/merch-html-EvzHSpaB3D8A229AM3NyH6
Contacto
https://whimsical.com/contacto-RNJ1U3by3ErjHQdVBLNxNV

Wireframes Mobile
Home
https://whimsical.com/home-mobile-ThQ4HVTEUawKsb7b96aunt
Historia
https://whimsical.com/historia-mobile-LWgJWGmAigLiq5mrkvbphq
Musica
https://whimsical.com/musica-mobile-29iwb2wgzpVXbR5ovyZaJc
Videos
https://whimsical.com/videos-mobile-7eeMZyCMmACPSdphg3oPXD
Merch
https://whimsical.com/merch-mobile-PUKrsczaP4n9C4QmAwaAZJ
Contacto
https://whimsical.com/contacto-mobile-G9AWhECSKQmLebYdxniivg

A medida que fuimos incorporando nuevas herramientas como FLEX y GRIDS hasta llegar a BOOTSTRAP he ido modificando mis bocetos iniciales por lo que el 
resultado final termino siendo muy diferente a la idea inicial. 
Para empezar decidi tomar una fuente madre (Friz Quadrata) la cual descargué y converti a una extension .woff. Para ello utilice la propiedad @font-face
y realice la configuracion para que sea mi fuente predeterminada.

Para mi Home page utilice Mobile first y realice los media queries para que sean adaptables a dispositos en 768px y 400px. Tomando como referencia mi 
wireframe, decidi aplicar una imagen de fondo Background-image y construir un grid para luego poder ubicar el contenido segun mi preferencia. Sobre el
contenido , construí una tabla acerca de los shows de la banda y aplique un boton con un vinculo "Comprar tickets". Luego sobre el margen derecho el 
contenedor FLEX tiene vinculos para escuchar canciones y utilice iconos SVG directamente linkeados de internet. Tanto para el contenedor table como para
el contenedor con links utilice FLEX para darle la alineacion correspondiente. 

Acerca de mi barra de navegacion utilice una plantilla de BOOSTRAP y fui modificandola no solo en su estilo sino tambien agregando los SVG para los 
vinculos a las redes sociales. Tuve problemas luego de aplicar SASS y la nav no quedo como inicialmente la habia pensado. No pude resolver el porqué 
de esa modificación, pero estoy conforme de todas formas con el resultado final. En la pagina Index use la propiedad position fixed para que la nav 
acompañe el scroll down. Aplique un hover sobre los vinculos y en todas las paginas menos STORE las propiedades de la nav son las mismas y gracias a 
BS la nav en responsive funciona con el boton hamburguesa correctamente excepto en la pagina VIDEOS en donde el boton hamburguesa una vez abierto queda fijo. Eso tampoco lo pude resolver. En la pagina Store al tener un fondo blanco mofidique los
colores tanto de los vinculos como de los SVG y utilice mismo logo pero con otro color. 

En la pagina Historia decidi aplicar texto tomando en cuenta la jerarquia de las etiquetas. Aplique una imagen de fondo sobre el texto y luego utilizando un GRID decidi 
jugar con las imagenes desde el CCS y las aplique como el background de cada contenedor div. En cada @media agregue las mismas imagenes en distinta resolucion
para no tener que modificar luego el tamaño del background. Las imagenes fueron convertidas la extension .webp para que no resulten tan pesadas al momento de 
cargar el sitio. 

Para la pagina Musica tambien utilice GRID desde mobile First y FLEX para que las imagenes en modo escritorio esten en linea (row - space-evenly). Tambien 
utilice los SVG para los vinculos a las plataformas musicales. 

En la pagina Videos tambien utilzando GRID con sus breakpoints introduci vinculos Iframe de videos de Youtube de la banda utilice 2 tamaños distintos para 
Escritorio y tablet (width:60%) y para Mobile (width:90%) ya que si dejaba siempre el mismo tamaño los vinculos en modo mobile se achicaban demasiado. 

En la pagina STORE decidi utilizar BS para aplicar la grilla y ubicar el contenido sin usar media queries. Si bien mi tienda no es muy sofisticada utilicé
varios recursos de estilo aprendidos en clase y use FLEX para acomodar el contenido que luego, tomando en cuenta la grilla de 12 columnas, fui adaptando a 
la pantalla escritorio . Utilice imputs buttons y vinculos para darle la dinamica necesaria que una Tienda necesita. 

Por ultimo en la pagina CONTACTO tambien utilice BS para realizar la grilla con el formulario de contacto y tambien un vinculo para el Sello discografico. 
Aplique un vinculo sobre la palabra "desuscribirte" y tambien reemplace el boton de Enviar por un vinculo. 

Tomando en cuenta las buenas practicas creé una pagina Error404 para utilizarla en los vinculos que no tenian un vinculo determinado.
Utilice meta description en cada pagina para describir el contenido en la busqueda en los navegadores. En la pagina index tambien aplique los meta
author y copyright. 

Si bien la mayoria de los vinculos estan linkeados a todo el contenido que la banda ya posee en internet, hubo otros vinculos que los linkeé a la pagina error404 ya que ese contenido tiene otras implicancias. 

Luego hice uso de GIT creando mi resositorio y realizando commits para guardar los cambios que fui realizando. El paso siguiente fue subir mi repositorio a GITHUB y realizando el deploy de mi sitio en Github. A continuacion dejo los links:

https://github.com/Nikito1981/Daskate-web.git 

https://nikito1981.github.io/Daskate-web/

Luego realice la aplicacion de SASS utilizando NODE, y debo decir que fue lo que mas me costó. 
Creacion de main.css el cual reemplace en todas las paginas por mi archivo style.css 
Creacion de main.scss para los partials y la configuracion de la fuente.
Creacion de partials (vars, mixins, commons, nav, tienda, contacto, medias y footer).
Creacion de _nav.scss para la Anidacion de la botonera 
Creacion de distintas variables de color , tamaño de fuente, sizing y estilos. 
Creacion de extends y mixins 
Creacion del archivo gitignore para ocultar infomacion no necesaria en el repositorio. 

Por ultimo, utilice el servidor gratuito de Netlify 












