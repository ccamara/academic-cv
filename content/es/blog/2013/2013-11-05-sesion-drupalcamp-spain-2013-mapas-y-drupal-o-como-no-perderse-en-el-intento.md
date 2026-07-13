---
title: "Sesi\xF3n DrupalCamp Spain 2013: \"Mapas y drupal, o c\xF3mo no perderse en el intento\""
summary: ""
date: 2013-11-05
draft: false

# Featured image for cards/social
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: Credit or context (Markdown supported)

cover:
  image: "https://images.unsplash.com/photo-1557682250-33bd709cbe85?q=80&w=1600"
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "✨"

# Authors are matched to profiles in content/authors/
authors:
  - me

tags:
  - drupal
  - drupalcamp
  - mapas
  - Tecnología

content_meta:
  trending: false
---

<!-- Tip: open with the why, then show results, code, and next steps. -->

Durante los días 26 y 27 de octubre tuvo lugar en Cáceres la <a href="http://2013.drupalcamp.es/" class="ext" target="_blank">DrupalCamp Spain 2013</a> y allí nos desplazamos todo el equipo de <a href="http://ymbra.com" class="ext" target="_blank">Ymbra</a>. Para quien no lo conozca, se trata del encuentro anual por excelencia de la comunidad drupalera española en el que se abordan temas sobre temas relacionados con drupal (cómo no), gestión de proyectos, sistemas, workflows... y en general aspectos relacionados con el mundo del desarrollo web a través de&nbsp;<a href="http://2013.drupalcamp.es/calendario" class="ext" target="_blank">sesiones/comunicaciones</a> de 45 minutos cada una (¡en esta edición hubo 44!), talleres de trabajo, <a href="http://<https://en.wikipedia.org/wiki/Birds_of_a_Feather_%28computing%29" class="ext" target="_blank">BoFs</a>, networking y cena. A diferencia de lo que hice en <a href="/node/301">esta entrada sobre los DrupalDeveloperDays de Barcelona</a> , en esta ocasión no hablaré tanto del evento en sí o de las sesiones a las que asistí (espero poder hacerlo más tarde), sino de la sesión que presenté: <a href="http://2013.drupalcamp.es/mapas-y-drupal-o-como-no-perderse-en-el-intento" class="ext" target="_blank">Mapas y Drupal, o como no perderse en el intento</a>, en la que trato de dar una visión general de las opciones que tiene drupal para trabajar con mapas y presento y comparo tres soluciones distintas.</p><p><iframe src="https://prezi.com/embed/-t-vbxr_jzz5/?bgcolor=ffffff&amp;lock_to_path=0&amp;autoplay=0&amp;autohide_ctrls=0&amp;features=undefined&amp;disabled_features=undefined" width="100%" height="400px" frameborder="0"></iframe></p><p>Hace tiempo que estamos acostumbrados a ver mapas en la web. Tanto es así que es cada vez más habitual ver aplicaciones web o móviles en las que la geolocalización o los mapas juegan un papel importante. Drupal no es una excepción y es posible realizar mapas como <a href="http://theintertwine.org/explore" class="ext" target="_blank">http://theintertwine.org/explore</a>, <a href="http://geluidvannederland.nl" class="ext" target="_blank">geluidvannederland.nl</a> o <a href="http://xi.bienalarquitectura.es/es/proyectos" class="ext" target="_blank">http://xi.bienalarquitectura.es/es/proyectos</a> por poner unos pocos ejemplos. Sin embargo, no es menos cierto que conseguirlo no es algo trivial y quien haya intentado alguna vez trabajar en ello se habrá podido sentir abrumado por la gran cantidad de módulos existentes (a día de hoy existen más de 90 módulos que se ocupan de algún aspecto relacionado con localización o mapas, algunos de ellos excluyentes entre sí), configuraciones necesarias o conceptos tales como proyecciones, capas base, mapas, geocodificación, GIS... No solo eso, sino que además el panorama ha cambiado mucho en los últimos meses (por no hablar de cómo ha cambiado desde&nbsp; que hice <a href="/node/286">ArchTLAS</a> o la web de la <a href="/node/229">XI Bienal Española de Arquitectura y Urbanismo</a> en drupal 6). Y la sesión va precisamente de eso: de tratar de poner orden a todo el caos para tener un drupal 7 con una solución de mapas bastante completa y funcional.</p><p>En la sesión se presentan los conceptos básicos que conforman un mapa en general para posteriormente dar una clasificación comentada de los módulos existentes más utilizados o más interesantes para geolocalizar y mostrar varias entidades en un mapas que permita entender hasta qué punto pueden combinarse para ofrecer soluciones completas o por el contrario son excluyentes. La sesión se complementará con la demostración práctica de utilización de tres soluciones que muestran mapas con leaflet, openlayers y getlocations.</p><p>Un aspecto que me gustaría destacar es la existencia de <a href="https://github.com/ccamara/dc-maps" class="ext" target="_blank">este repositorio en github</a> pensado para poner práctica los conceptos de la presentación. En el repositorio he incluido todos los módulos necesarios y para hacer más fácil su utilización los he agrupado y configurado en cuatro features:</p><ul><li><strong>mapping demo:</strong> controla las dependencias de módulos compartidos (libraries, views...). Es requerida por el resto de features.</li><li><strong>leaflet_demo_dc_spain: </strong>contiene los tipos de contenido, dependencias y configuraciones de views y mapas utilizando leaflet.</li><li><strong>openlayers_demo_dc_spain: </strong>contiene los tipos de contenido, dependencias y configuraciones de views y mapas utilizando openlayers.</li><li><strong>getlocations_demo_dc_spain:</strong> contiene los tipos de contenido, dependencias y configuraciones de views y mapas utilizando getlocations.</li></ul><p>Así pues, quien quiera experimentar y poner en práctica los conocimientos aprendidos solo tiene que clonar el repositorio, instalarlo y activar la feature que corresponda.</p>
