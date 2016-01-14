<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orgheadline1">Necesidades técnicas</a></li>
<li><a href="#orgheadline23">La Web como fuente de datos</a>
<ul>
<li><a href="#orgheadline2">Recopilar datos</a></li>
<li><a href="#orgheadline3">Búsqueda avanzada</a></li>
<li><a href="#orgheadline4">Ejemplo con operador <code>site:</code> de Google</a></li>
<li><a href="#orgheadline5">Operador lógico <i>AND</i></a></li>
<li><a href="#orgheadline6">Operador lógico <i>OR</i></a></li>
<li><a href="#orgheadline7">Palabras reservadas</a></li>
<li><a href="#orgheadline8">Búsqueda literal</a></li>
<li><a href="#orgheadline9">Operador menos</a></li>
<li><a href="#orgheadline10">Operador comodín</a></li>
<li><a href="#orgheadline11">Debemos saber que</a></li>
<li><a href="#orgheadline12">Resumen operadores lógicos</a></li>
<li><a href="#orgheadline16">Operadores de tipos de archivo</a>
<ul>
<li><a href="#orgheadline13">Búsqueda en sitio concreto y tipo de archivo concreto</a></li>
<li><a href="#orgheadline14">Búsqueda de literales en tipo de archivo concreto</a></li>
<li><a href="#orgheadline15">Búsqueda de literales en tipo de archivo en sitio concreto</a></li>
</ul>
</li>
<li><a href="#orgheadline21">Operadores de búsqueda</a>
<ul>
<li><a href="#orgheadline17"><code>link:</code></a></li>
<li><a href="#orgheadline18"><code>related:</code></a></li>
<li><a href="#orgheadline19"><code>info:</code></a></li>
<li><a href="#orgheadline20"><code>cache:</code></a></li>
</ul>
</li>
<li><a href="#orgheadline22">Desafíos</a></li>
</ul>
</li>
<li><a href="#orgheadline30">Otras utilidades</a>
<ul>
<li><a href="#orgheadline24">Bit.ly</a></li>
<li><a href="#orgheadline25">Twitter</a></li>
<li><a href="#orgheadline26">La máquina del tiempo de archive.org</a></li>
<li><a href="#orgheadline27">Código fuente HTML</a></li>
<li><a href="#orgheadline28">TinEye</a></li>
<li><a href="#orgheadline29">Otras</a></li>
</ul>
</li>
<li><a href="#orgheadline37">Outwit Hub</a>
<ul>
<li><a href="#orgheadline31">Conceptos Outwit</a></li>
<li><a href="#orgheadline32">Vistas Outwit</a></li>
<li><a href="#orgheadline33">Filtros Outwit</a></li>
<li><a href="#orgheadline34">Navegación Outwit</a></li>
<li><a href="#orgheadline35">Resultados</a></li>
<li><a href="#orgheadline36">Enlaces Outwit</a></li>
</ul>
</li>
<li><a href="#orgheadline38">Import.io</a></li>
<li><a href="#orgheadline39">Kimonolabs</a></li>
<li><a href="#orgheadline42">Inspección técnica de HTML</a>
<ul>
<li><a href="#orgheadline40">Firebug</a></li>
<li><a href="#orgheadline41">Consola</a></li>
</ul>
</li>
<li><a href="#orgheadline47">Google Drive</a>
<ul>
<li><a href="#orgheadline43">ImportHTML()</a></li>
<li><a href="#orgheadline44">ImportXML</a></li>
<li><a href="#orgheadline45">Algunos ejemplos XPath útiles:</a></li>
<li><a href="#orgheadline46">Ejemplo complejo</a></li>
</ul>
</li>
<li><a href="#orgheadline65">PDF</a>
<ul>
<li><a href="#orgheadline48">Interroga a un <i>PDF</i></a></li>
<li><a href="#orgheadline49">Colaboración</a></li>
<li><a href="#orgheadline50">Crowdcrafting: PDF Transcribe</a></li>
<li><a href="#orgheadline51">Probar, probar, probar</a></li>
<li><a href="#orgheadline53">pdftotext, xpdf</a>
<ul>
<li><a href="#orgheadline52">Opciones</a></li>
</ul>
</li>
<li><a href="#orgheadline54">Ghostscript</a></li>
<li><a href="#orgheadline57">PDFtk</a>
<ul>
<li><a href="#orgheadline55">Rotar documentos</a></li>
<li><a href="#orgheadline56">Dividir un PDF en varios</a></li>
</ul>
</li>
<li><a href="#orgheadline58">ImageMagick</a></li>
<li><a href="#orgheadline59">Poppler-utils</a></li>
<li><a href="#orgheadline60">Rmagick</a></li>
<li><a href="#orgheadline61">PDF Split and Merge</a></li>
<li><a href="#orgheadline62">Herramientas Web</a></li>
<li><a href="#orgheadline63">Tika</a></li>
<li><a href="#orgheadline64">Good Tables</a></li>
</ul>
</li>
<li><a href="#orgheadline68">Un caso singular: ProPublica</a>
<ul>
<li><a href="#orgheadline66">El proceso</a></li>
<li><a href="#orgheadline67">PDFTables</a></li>
</ul>
</li>
<li><a href="#orgheadline71">OCR</a>
<ul>
<li><a href="#orgheadline69">Google Drive</a></li>
<li><a href="#orgheadline70">Tesseract-ocr</a></li>
</ul>
</li>
<li><a href="#orgheadline72">Referencias bibliográficas&#xa0;&#xa0;&#xa0;<span class="tag"><span class="OK">OK</span></span></a></li>
<li><a href="#orgheadline73">Manuales</a></li>
</ul>
</div>
</div>

Módulo de periodismo de datos de *scraping* donde aprenderemos cosas directamente relacionadas:

-   Web *scraping*
-   PDF *scraping*
-   Nociones de programación
-   Detectar y estructurar información localizada en web o en otros formatos para poder analizarla e interpretarla.
-   Volcar y formatear datos de diferentes orígenes para poder gestionarlos.

Pero también otras cuestiones directamente relacionadas como:

-   Aprender a instalarnos programas adecuadamente
-   Resolución de problemas
-   Manejo de versiones
-   Github
-   Tecnologías web
-   Empezar a practicar con lenguajes de programación

# Necesidades técnicas<a id="orgheadline1"></a>

-   Navegadores [Firefox](http://getfirefox.com/) (o derivados) y [Chrome](https://www.google.es/chrome/browser/desktop/) (o derivados)
-   Editor de textos con indentado y resaltado de sintaxis, [elige el que más te guste](http://infotics.es/2015/11/11/editor-de-textos/)
-   Extensiones del navegador: [Firebug](http://getfirebug.com/), [Xpath Checker](https://addons.mozilla.org/En-uS/firefox/addon/xpath-checker/), [Tineye](http://www.tineye.com)
-   Cuenta Google Drive.
-   Programas de copia, descarga, spiders o crawling como [httrack](https://www.httrack.com/) o [Downthemall](http://www.downthemall.net/).
-   Programas de web scraping como [Outwit](https://www.outwit.com/), [Import.io](http://import.io) y [kimono](http://kimonolabs.com).
-   Programas de tratamiento de PDF como [xpdf](http://www.foolabs.com/xpdf/).
-   La terminal, también es posible desde Windows con [cygwin](https://www.cygwin.com/)
-   Python, Ruby y R

# La Web como fuente de datos<a id="orgheadline23"></a>

-   La web es un fuente de datos inagotable
-   De hecho, se puede considerar una gran base de datos.
-   Se puede acceder a servicios web anónimos, con perfiles, buscadores generales y específicos.
-   El buscador es un software que recopila e indexa archivos almacenados en servidores web y recupera la información conforme a algunos criterios específicos.

## Recopilar datos<a id="orgheadline2"></a>

-   La manera más sencilla de extraer datos de una página web consiste en seleccionar el texto, copiarlo y pegarlo allí donde queremos luego trabajar con ello.
-   Si se tratan de datos que se encuentran dispuestos en tablas, los podemos copiar y pegar en nuestra aplicación de hoja de cálculo favorito.
-   Es la forma más fácil pero también **manual**.
-   Si queremos **automatizar** esa tarea, o incluso **si no nos deja hacerlo manualmente**, tenemos que optar por otras opciones.
-   Las opciones más fáciles pasan por que los datos estén bien estructurados, un HTML bien formado
-   Se habla de recopilación de datos, *crawling* o *spiding* cuando nos descargamos sitios completos.
-   Se habla de *scraping* cuando rascas de aquí y de allá.

## Búsqueda avanzada<a id="orgheadline3"></a>

-   Se puede utilizar búsqueda avanzada en los principales buscadores
-   *Google*, *Yahoo!*, *duckduckgo*, *Yandex* o *Bing*
-   También están los [operadores de búsqueda](https://support.google.com/websearch/answer/2466433): permiten filtrar las búsquedas.
-   Un listado no oficial lo encontrais en [googleguide](http://www.googleguide.com/advanced_operators_reference.html)

## Ejemplo con operador `site:` de Google<a id="orgheadline4"></a>

-   Los operadores de búsqueda nos permiten acotar y especificar más los resultados.
-   Se puede buscar una palabra específica en un dominio concreto con `site:dominio`
-   Por ejemplo, busquemos la palabra **inmigración** en el sitio de [elpais.com](https://www.google.es/?gfe_rd=cr&ei=QVl-VoOmOtGp8weIvqSwBg#q=site:elpais.com+inmigraci%25C3%25B3n)
-   El resultado no varía en función de nuestro perfil o nuestra navegación ya que es sobre un sitio concreto.
-   Sí que puede variar desde que he realizado la búsqueda hasta que lo buscáis.

La búsqueda devuelve 55200 resultados.

    site:elpais.com inmigración

## Operador lógico *AND*<a id="orgheadline5"></a>

-   Cuando buscamos una palabra buscamos unos caracteres escritos de esa manera determinada.
-   Si buscamos más de una palabra, comienzan a actuar operadores lógicos.
-   Los operadores se utilizan para afinar aun más la búsqueda.
-   El operador por defecto cuando se buscan dos palabras es es `+`, `AND` o `Y`.
-   En Google se utiliza `+`, no los otros.
-   Eso quiere decir que se buscan documentos que contengan esas dos palabras.

La búsqueda de `inmigración ilegal` devuelve los mismos resultados, 6680, que `inmigración + ilegal`

    site:elpais.com inmigración ilegal

## Operador lógico *OR*<a id="orgheadline6"></a>

-   Otro operador muy utilizado es `OR`, `O` o `|`
-   En Google se utilizan `OR` y `|`
-   Busca documentos donde aparecen una u otra palabra.

Si buscamos `inmigración OR ilegal` da los mismos resultados que si buscamos `inmigración | ilegal`, 16700 resultados:

    site:elpais.com inmigración OR ilegal

## Palabras reservadas<a id="orgheadline7"></a>

-   Los operadores lógicos nos introducen en el concepto de las *palabras reservadas*.
-   Las palabras reservadas se dan en todos los lenguajes informáticos y son palabras que utiliza el propio lenguaje.
-   Son palabras o caracteres reservados `AND`, `OR`, `+`, `-`, `|`, etc.
-   Lo cual nos lleva al concepto de *literales*
-   Si queremos utilizar esas palabras reservadas como palabra a buscar, deberemos entrecomillarlas.

Lo cual buscará documentos donde aparezcan las tres palabras: `spain`, `or` y `greece`

    site:theguardian.com spain "or" greece

## Búsqueda literal<a id="orgheadline8"></a>

-   La búsqueda literal sirve para encontrar expresiones específicas.
-   Los literales se denominan también en programación *strings* o *cadenas de caracteres*.
-   Por ejemplo, la búsqueda de `violencia de género en madrid` encuentra 330 resultados porque hay 330 documentos donde aparece esa expresión tal cual.

Si queremos que aparezca `violencia de género` y también `madrid`, pero sin estar juntos en la expresión, devuelve 20200 resultados.

    site:elpais.com "violencia de género" madrid

## Operador menos<a id="orgheadline9"></a>

-   Si el operador `+` se utiliza como sinónimo de `OR`, el operador menos reduce los resultados de la búsqueda.
-   Con el operador `-` elegimos palabras que no queremos que aparezcan acompañadas de otras.
-   Observad que el signo de menos debe estar pegado al texto.
-   Seguimos con el ejemplo anterior y **concatenamos operadores**
-   Cuántas veces aparece "violencia de género" pero no aparece `2014`, `2011` y `2010`, para que no aparezcan las noticias de esos años, aparecen 9 resultados.

Incluso se combina con el operador `site:`:

    "violencia de género en españa" -site:wikipedia.org -2014 -2011 -2010

## Operador comodín<a id="orgheadline10"></a>

-   El asterisco encuentra cualquier cosa en medio de una cadena de caracteres.
-   Si queremos buscar *violencia de género*, *violencia a las mujeres* y *violencia contra las mujeres*, podemos emplear el operador el operador `|`

Y apoyarnos en el operador comodín `*`

    site:elpais.com "violencia * mujeres|género"

## Debemos saber que<a id="orgheadline11"></a>

-   Las búsquedas en estos buscadores no son *case sensitive*, es decir, no distinguen entre minúsculas y mayúsculas.
-   Si buscamos "violencia de género" obtendremos los mismo resultados que si buscamos "VIOLENCIA DE GÉNERO"
-   el uso de estos operadores implica el uso de **expresiones o palabras reservadas**
-   Las palabras reservadas son las que el buscador entiende como propias de su vocabulario.
-   Para utilizar palabras reservadas en la búsqueda debemos entrecomillarlas.
-   Las comillas también se utilizan para buscar literales, expresiones exactas.

## Resumen operadores lógicos<a id="orgheadline12"></a>

-   El operador de restricción `+`, es similar a `AND`
-   El operador de restricción `-`, es similar a `NOT` en otros tipos de búsqueda.
-   El operador `OR`, donde esté cualquiera de los dos términos, o `|`
-   =""=, se entrecomilla el texto exacto que queremos buscar, búsqueda literal.
-   Si no queremos aprender estas reglas, podemos usar el buscador avanzado de Google que ofrece una interfaz gráfica en forma de formulario.

<http://www.google.com/advanced_search>

## Operadores de tipos de archivo<a id="orgheadline16"></a>

-   Otro operador de búsqueda de google es el operador de tipos de archivo.
-   Se puede buscar documentos que estén en un determinado formato de archivo en un sitio determinado
-   O se pueden buscar palabras que estén en un documento con un formato determinado.
-   O concatenar aun más con el operador de sitio y el de tipo de archivo.

### Búsqueda en sitio concreto y tipo de archivo concreto<a id="orgheadline13"></a>

Busca documentos que estén en formato `xls` en `elpais.com`

    filetype:xls site:elpais.com

### Búsqueda de literales en tipo de archivo concreto<a id="orgheadline14"></a>

Busca literales `violencia de género` que estén en un documento con un formato `csv`

    filetype:csv "violencia de género"

### Búsqueda de literales en tipo de archivo en sitio concreto<a id="orgheadline15"></a>

Busca literales `violencia de género` en archivos `csv` en el sitio del `ine.es`

    filetype:csv site:ine.es "violencia de género"

## Operadores de búsqueda<a id="orgheadline21"></a>

-   El listado completo de operadores de búsqueda disponible se encuentra en [Google](https://support.google.com/websearch/answer/2466433?hl=en).

### `link:`<a id="orgheadline17"></a>

`link:` encuentra páginas que enlazan a cierta página.

    link:okfn.es

### `related:`<a id="orgheadline18"></a>

`related:` encuentra páginas similares a una de tu elección.

    related:okfn.es

### `info:`<a id="orgheadline19"></a>

`info:` obtiene información sobre una página web, incluida la versión cacheada de la página, páginas similares y páginas que enlazan con el sitio.

    info:okfn.es

### `cache:`<a id="orgheadline20"></a>

`cache:` muestra la página la última vez que Google visitó la página.

    cache:okfn.es

## Desafíos<a id="orgheadline22"></a>

-   Busca patrones en la información, los datos o la estructura de las páginas:

-   Estructura de páginas estructurada:

<http://www.ejercito.mde.es/unidades/Cordoba/index.html> 

-   Una tabla en una web

<https://en.wikipedia.org/wiki/List_of_Spanish_provinces_by_sequence_or_length_of_coastline>

-   Tablas páginadas con *URLs* distintas

<http://www.bbc.co.uk/food/recipes/>

# Otras utilidades<a id="orgheadline30"></a>

Veremos algunas utilidades que nos pueden ayudar de una u otra manera:

-   *Bitly*
-   *Twitter*
-   *Archive.org*
-   *Wayback Machine*
-   Código fuente
-   *TinEye*
-   Otras: *Readability*, *Downthemall*.

## Bit.ly<a id="orgheadline24"></a>

-   El servicio de *urls* cortas nos puede ayudar a saber cuántas veces se ha compartido un determinado enlace.
-   Tenemos que ir a <http://bit.ly> e introducir la *URL* que nos interesa.
-   Si ya se ha utilizado, aparecerá una *URL* corta y podremos ver esa información escribiendo la URL seguida del símbolo `+`.
-   Así vemos las estadísticas completas de la página, da una idea de lo popular que era la página y de lo que fue utilizado por las redes sociales como *Twitter* o *Facebook*.

## Twitter<a id="orgheadline25"></a>

-   Con *Twitter* hacemos algo parecido a *Bit.ly*
-   No vamos a poder disfrutar del mismo nivel de estadísticas.
-   Se trata de buscar en el buscador de Twitter un enlace que nos interese y mostrará las últimas veces que se ha compartido.
-   No guarda un histórico de todo el tiempo.

## La máquina del tiempo de archive.org<a id="orgheadline26"></a>

-   La herramientas [Wayback Machine](http://archive.org/web/web.php) de [Internet Archive](http://www.archive.org) guarda pantallazos periódicos de las webs
-   456 mil millones de páginas en total que puedes consultar desde su buscador.
-   Una vez encontrada esa página, ese dominio, podemos ver en una línea de tiempo los distintos instantes que ha guardado la máquina y ver qué aspecto tenía.
-   No guarda muchas imágenes o estilos, por cuestiones de espacio, pero nos puede dar alguna sorpresa.

## Código fuente HTML<a id="orgheadline27"></a>

-   A menudo en el código fuente los programadores han realizado comentarios o han ocultado algo que podía estar en otro momento y que ahora no conviene.
-   No hace falta saber de *HTML* pero sí que hay que saber dónde buscar.
-   Los comentarios, contenido que el navegador no muestra, se encuentran entre los signos de `<!--` apertura de comentario y `-->` cierre de comentario.
-   Por ejemplo, en la página de [The Guardian](http://theguardian.co.uk) ahora ponen que están contratando programadores.

## TinEye<a id="orgheadline28"></a>

-   TinEye permite controlar el uso de las imágenes en un sitio web
-   Nos pueda dar pistas sobre el origen, la fuente, otros usos de esa imagen&#x2026;
-   Se puede subir una imagen o bien escribir una *URL*, ya sea de la imagen o de la página web que contiene esa imagen
-   Es capaz de mostrar unos resultados que pueden ser curiosos.. Por ejemplo, cuando se produce un acontecimiento importante, se suelen utilizar las mismas imágenes para ilustrarlo.
-   Con TinEye podemos ver en qué medios se están utilizando esas imágenes y cuándo lo hicieron, por lo que podemos saber quién lo hizo primero y crear una línea temporal del uso de la imagen.
-   Tiene extensiones para Firefox, Opera, Chrome o Safari. <http://www.tineye.com>
-   Ejemplo: <https://www.tineye.com/search/1dc12635c9e2e21a53002ef0ce9ac0e458d59492/>

## Otras<a id="orgheadline29"></a>

-   [Readability](http://www.readability.com), servicio web que ayuda a extraer texto de la página web. Dispone de extensión para Firefox.
-   [DownThemAll](http://www.downthemall.net/), extensión que permite la descarga de varios archivos a la vez.

# Outwit Hub<a id="orgheadline37"></a>

-   Outwit Hub, software y extensión para el navegador que contiene varias utilidades de reconocimiento y extracción de contenidos web y de organizar las colecciones de datos.
-   Busca automáticamente a través de páginas.
-   La primera vista en el marco de la izquierda es `Página`, mientras que los otros objetos son: `links`, `images`, `data`
-   OutWit considera la página web como elementos de datos, por lo que si nos ponemos sobre el objeto `images`, seleccionaremos todas las imágenes.

## Conceptos Outwit<a id="orgheadline31"></a>

Hay tres conceptos en OutWit Hub:

1.  Una cesta de la compra llamada *catch* o la *cesta*, discpuesto al pie de la página para recoger todo lo que queramos.
2.  Podemos filtrar la información por cada tipo de datos y recogerla en nuestra cesta.
3.  Puedes navegar a lo largo de varias páginas con el botón de paginación.

## Vistas Outwit<a id="orgheadline32"></a>

Las vistas que muestra *OutWit* son:

-   *Página*, actual. Muestra imágenes, enlaces, correos electrónicos, textos, rss, enlaces de noticias y otros datos que pueden extraerse de la página.
-   *Imágenes*, que aparecen en la página actual. Se pueden filtrar, ordenar y copiar en la cesta.
-   *Enlaces*, que aparecen en la página actual. Se pueden filtrar, ordenar y copiar en la cesta.
-   *Correos electrónicos*, que aparecen en la página. ídem.
-   *Texto*, muestra el texto de la página.
-   *RSS*, en caso de que los hubiera.
-   *Tablas*, extrae el contenido de la tabla y se le puede aqplicar las operaciones típicas.
-   *Listas*, extrae el contenido de las listas.
-   *Scraper*, aplica un escrapeador previamente cargado a la página.
-   *Source*, muestra el HTML de la página.

## Filtros Outwit<a id="orgheadline33"></a>

Los filtros de control de los que dispone:

-   Ocultar local, si activas esta caja de control, la vista solo mostrará los enlaces salientes o las imágenes externas, y se ocultaán los elementos locales.
-   Ocultar caché, cuando esta casilla esté activa, las URLs cacheadas no se mostrarán.
-   Documentos, cuando esta casilla esté marcada, sólo se mostrarán las URLs que correspondan con docuementos: pdf, doc, xls, etc.
-   *Script*, si está marcada esta casilla, se mostrarán las imágenes que vengan de scripts y el resto se ocultarán.
-   *Style*, si se marca se ocultarán las imágenes que no vengan de CSS.
-   Background, muestra las imágenes utilizadas como fondo si está marcada.

## Navegación Outwit<a id="orgheadline34"></a>

Cuando hay más de una página que cargar, cuenta con algunas opciones:

-   *Next*, carga la página siguiente de la serie
-   *Browse*, busca automáticamente a través de todas las páginas de una serie.
-   *Dig*, puede explorar todos los enlaces de la página. Si pinchamos en *Dig*, en el menú podemos establecer la profundidad de la búsqueda. Si marcamos `depth \` 0=, buscará por todos los enlaces de la página pero si modificamos el valor a `1`, explorará también todos los enlaces de las páginas visitadas.
-   *Site Home*, carga la página principal del sitio.
-   *Slideshow*, muestra las imágenes de la página como un carrusel.

## Resultados<a id="orgheadline35"></a>

-   Los datos se pueden exportar a CSV, TSV, HTML, XLS o crear scripts SQL para guardarlos en bases de datos.
-   En la versión de pago también se pueden programar tareas.
-   Se suele adoptar como estándar de tiempo entre petición y petición la de 2 segundos de retraso.
-   Si nos encontramos con contenido generado dinámicamente a través de javascript, será mejor que recopilemos los datos manualmente o que aprendemos otra técnica.

## Enlaces Outwit<a id="orgheadline36"></a>

-   Extensión, <http://www.outwit.com/products/hub/license.php>
-   Add-on Firefox, <https://addons.mozilla.org/en-US/firefox/addon/outwit-hub/>
-   Vídeo, <https://www.youtube.com/watch?v=ffoXpBlHZpo>

# Import.io<a id="orgheadline38"></a>

-   Import.io es una herramienta para la extracción de datos de páginas web.
-   No se necesita ningún aprendizaje de lenguajes de programación.
-   Para probarla podemos hacerlo a través de <https://magic.import.io>
-   Podemos [descargárnosla de la web](http://support.import.io/knowledgebase/articles/190281-how-do-i-install-import-io)
-   En <http://magic.import.io> pones la *URL* que deseas probar y pulsas el botón "GET DATA".
-   Nos aparecen los datos tabulados en una tabla.
-   Eliminamos columnas que no queramos pinchando en la `(x)` que aparece.
-   Si queremos guardar la información que aparece, tendremos que dar a `Extract Data`
-   En la parte de abajo de la página salen tres botones.
    -   Uno es por si lo que ha encontrado import.io no es lo que queríamos.
    -   Si queremos descargarnos los datos para jugar con ellos, *Download CSV*
    -   Pero también podemos crear una *API*, si estamos registrados.

# Kimonolabs<a id="orgheadline39"></a>

-   Herramienta de *scraping* que convierte web en API.
-   Se utiliza como [extensión](https://chrome.google.com/webstore/detail/kimono/deoaddaobnieaecelinfdllcgdehimih?hl%3Des%0A) en Chrome/Chromium o atajo a los marcadores en Firefox.
-   Una vez que estamos registrados en Kimono, podremos comenzar a crear nuestra propia API de cualquier sitio web apuntando al botón de Kimono.
-   Una de las características de Kimono y que lo hacen muy atractivo es el hecho de crear una API sobre la base de cualquier web.
-   La *API* nos ofrece una forma de interactuar con el contenido de esa web de forma automática, por lo que podemos crear nuestra propia web o aplicación con nuestro propio *HTML*, *CSS* y/o *JavaScript* y poner el contenido de esa *API*, normalmente en formato *JSON*.

# Inspección técnica de HTML<a id="orgheadline42"></a>

-   *Firebug* se ha convertido en la herramienta estándar
-   Chinche de la malva o zapatero, una extensión del navegador que permite analizar y descubrir todo lo necesario sobre la página web que estamos visitando para su modificación o interpretación.
-   Comenzó como una extensión muy utilizada por desarrolladores web para editar, mostrar errores y monitorear el funcionamiento de *JavaScript*, *CSS* y *HTML* en tiempo real y en cualquier página.
-   Permite también explorar el *DOM* (*Document Object Model* o modelo de objetos del documento) para crear selectores *CSS* en conjunción con *JavaScript* y así conseguir webs dinámicas.
-   Tanto es así que Mozilla Firefox tiene una versión integrada de Firebug, en analizador.
-   Si queremos experimentar un poco más, podemos descargar la extensión desde <http://www.getfirebug.com>

## Firebug<a id="orgheadline40"></a>

Una vez que hemos instalado la extesión de Firefox, podemos utilizarlo de dos manera:

-   Atajos de teclado:
    -   `F12` abre y cierra Firebug
    -   `CTRL + F12` abre Firebug en una ventana nueva
    -   `CTRL + F12`, si lo tienes abierto en ventana nueva, lo colca integrado
    -   `SHIFT + F12`, cierra la consola si la tienes abierta
-   Ratón:
    -   Activamos la aplicación con el icono.
    -   También podemos seleccionar cualquier parte de la web con el botón derecho y pinchar en `inspeccionar elemento`

## Consola<a id="orgheadline41"></a>

En ambos casos trabajamos con una consola que nos muestra la información de la página, en concreto:

-   Consola, muestra información de errores del JavaScript de la página. Podemos introducir y ejecutar comandos.
-   *HTML*, muestra el *HTML* como nodos DOM de una jerarquía. Los nodos individuales pueden expandirse o contraerse para mostrar u ocultar los nodos hijos. También muestra el *box model* (modelo de caja) CSS para cada elemento seleccionado.
-   CSS, muestra todos los estilos CSS cargados y puedes introducir CSS y mofificarlos al momento. Hay una ventana que muestra todos los estilos cargados por nombre.
-   Script, muestra los archivos JS incluidos y se pueden inspeccionar y activar o desactivar por partes.
-   DOM, Muestra los objetos y propiedades DOM.
-   Net, puedes comprobar cuańto tarda cada recurso en cargar, muestra las cabeceras de peticiones y respuestas HTTP para cada recurso.

# Google Drive<a id="orgheadline47"></a>

-   importHTML()
-   importFeed()
-   importXML()
-   importURL()
-   importData()
-   importRange()

## ImportHTML()<a id="orgheadline43"></a>

-   El método más fácil consiste en importar datos de una tabla o una lista a Google Drive con la función `IMPORTHTML`
-   Para ello tendremos que tener ciertas nociones de *HTML*
-   Permite importar contenido de tipos de elementos *HTML*, tablas y listados.
-   Afecta a los elementos `table` (tabla), `ul`, `ol` y `dl` (listados).
    -   `ul`, que corresponde a *unordered list* o lista desordenada, la típica lista donde cada elemento aparece con un punto o un guión.
    -   `ol`, que corresponde a *ordered list* o lista ordenada, donde los elementos del listado aparecerán ordenados, bien numérica o alfabéticamente, por ejemplo.
    -   `dl`, corresponde con *description list*, listas de descripciones
    -   `table`, corresponde con una tabla de datos tabulados.
-   Construiremos la función `IMPORTHTML` con la *url* entrecomillada, separado por punto y coma y entrecomillado el elemento del que queremos sacar la información, bien una lista `list` o una tabla `table`, seguido del número de elemento en la página de su mismo tipo, separado por otro punto y coma:

    =IMPORTHTML("URL";"list|table";n)

## ImportXML<a id="orgheadline44"></a>

-   También podemos utilizar la función `IMPORTXML("url";"xpath_query")` para extraer otro tipo de información o acceder al contenido por `XPath`.
-   Para ayudarnos a ello, además de *Firebug*, podemos utilizar la extensión de Firefox [XPath Checker](https://addons.mozilla.org/en-US/firefox/addon/xpath-checker/)
     -Por ejemplo, si queremos obtener el listado de todos los atributos `href` que contiene el elemento `a` que corresponde a los enlaces, de la *URL*, haremos:

    =IMPORTXML("URL";"//a/@href")

-   Pero podríamos elegir sólo los enlaces que tienen una determinada clase, lo que haríamos también con *XPath* de esta manera:

    =IMPORTXML("URL";"//a[@class='clase']")

-   En vez de editar la fórmula completa, se puede poner la *URL* en una celda, el elemento *XPath* a buscar en otra y construir la expresión llamando a las celdas:

    =IMPORTXML(celda1;celda2)

-   La potencia de *Xpath* es *infinita* y podemos hacer extracciones de datos muy concretas, como por ejemplo seleccionar solo los elementos que comiencen con una clase específica, como `[starts-with` y luego especificar la clase con el atributo `@` donde `class` es el valor del atributo `(@class, 'clase')`
-   Si queremos sacar todos los enlaces una *URL*, después de inspeccionar la página, comprobamos que los enlaces se encuentran en un `div` que tiene la clase `clase`. Construimos esta fórmula de `IMPORTXML`

    =IMPORTXML("URL"; "//div[starts-with(@class,'clase')]")

Si quisiéramos los enlaces, añadiríamos al final `//@href`, ya que el enlace se encuentra en el atributo de `a`, `href`

    =IMPORTXML("URL"; "//div[starts-with(@class,'clase')]")

Puede ser que la página no traiga los enlaces absolutos sino que sean relativos, por lo que podemos concatenarlos con la función `CONCATENATE`:

    =CONCATENATE("URL",celda-resultados)

Y luego estiramos esta función al resto de las celdas que lo requieran.

## Algunos ejemplos XPath útiles:<a id="orgheadline45"></a>

-   `/`, descarga todos los elementos de html que empiecen con `<`
-   `//a`, descarga todos los contenidos del elemento `a`, los enlaces, de la URL que decidamos.
-   `//a/@href`, descarga todos los contenidos del atributo `href` del elemento `a`, que corresponden con la URL del enlace.
-   `//input[@type`'text']/..=, descarga todos los elementos padre de los elementos de texto `input`
-   `count(//p)`, cuenta el número de elementos que le digamos, en este caso párrafos `p`
-   `//a[contains(@href, 'protesta')]/@href`, encuentra todos los enlaces que contienen la palabra `protesta`
-   `//div[not(@class`'left')]=, encuentra todos los `div` cuyas clases no sean `left`
-   `//img/@alt`, muestra todos los textos de los atributos `alt` de las imágenes `img`

## Ejemplo complejo<a id="orgheadline46"></a>

    =IMPORTXML("URL";"//div[@class='clase']//h3")

Nos da todos los titulares `h3` que se encuentran dentro del `div` con clase =clase=n de los artículos de la *URL*

# PDF<a id="orgheadline65"></a>

## Interroga a un *PDF*<a id="orgheadline48"></a>

Diagrama propuesto por Nicolas Kayser-Brill

![img](/home/flow/Documentos/curro/unir/mineria-datos/temas/nkb-pdf.png)

-   ¿Es tu imagen un PDF?
    -   Sí, entonces utiliza OCR para extraer datos
        -   Google Drive, <https://support.google.com/drive/answer/176692?hl=en>
    -   No, entonces ¿puedes copiar el texto seleccionándolo y pegándolo en otro documento?
        -   No, tendrás que usar otro software
        -   Sí, entonces puedes usar:
            -   [Tabula](http://tabula.technology), para extraer datos automáticamente.
            -   *PDFtoExcelOnline*: subes un PDF y te envían por correo el XLS. <http://pdftoexcelonline.com>
            -   [smallpdf](http://smallpdf.com)

## Colaboración<a id="orgheadline49"></a>

-   Si todo lo anterior falla, se puede utilizar alguna herramienta colaborativa.
-   [Documentcloud](http://www.documentcloud.org), creada por miembxs de la comunidad de periodismo de datos.
-   [mTurk](https://www.mturk.com/mturk/welcome) de *Amazon*.
-   [Crowdcrafting](http://crowdcrafting.org/)

## Crowdcrafting: PDF Transcribe<a id="orgheadline50"></a>

-   [PDF Transcribe](http://crowdcrafting.org/app/pdftranscribe/) es el nombre de la aplicación de *PyBossa* que permite transcribir un *PDF* colaborativamente.
-   Utiliza la librería *Mozilla PDF.JS library* para cargar un archivo *PDF* externo y renderizarlo en la aplicación que se ejecuta en el navegador sin necesidad de terceros.
-   A su lado se extiende un formulario  personalizado para extraer los datos que solicitamos de cada documento.
-   Se pueden añadir tantos campos como sean necesarios en el formulario para recopilar la información que necesitemos, explicándolo convenientemente.
-   Podemos asignar tareas a usuarios y completar de manera distribuida y colaborativa el proyecto de transcripción.

![img](//img10.imageshack.us/img10/5364/pdftranscribe1.png)

## Probar, probar, probar<a id="orgheadline51"></a>

-   ProPublica advierte en su guía para convertir PDF en documentos de texto que ninguna solución va a ser completa por la propia solución y/o por los documentos PDF.
-   Lo normal es combinar las técnicas y encontrar las opciones que más satisfagan.
-   Siempre se necesita una revisión manual o dos del trabajo realizado por las herramientas.

## pdftotext, xpdf<a id="orgheadline53"></a>

-   *pdftotext* es una herramienta de código abierto
-   Funciona en consola
-   Convierte archivos *PDF* a texto plano.
-   Forma parte de *xpdf*, un conjunto de aplicaciones para trabajar con documentos PDF. También se incluye como parte de *Poppler*, un proyecto derivado de *Xpdf*.

Solo puede convertir un documento cada vez:

    pdftotext archivo.pdf

<http://www.foolabs.com/xpdf/download.html>

-   Para especificar la primera página a convertir:

    pdftotext -f numero-primera-pagina-convertir

-   Especifica la última página a convertir:

    pdftotext -l numero-ultima-pagina-convertir

### Opciones<a id="orgheadline52"></a>

-   Especifica la resolución, en puntos por pulgada. El valor por defecto es 72.

    pdftotext -r resolucion-en-PPP

-   Especifica la coordenada x del área que selecciona desde la esquina superior izqda:

    pdftotext -x coordenada-x

-   Especifica coordenada y del área que selecciona desde la esquina superior izqda:

    pdftotext -y coordenada-y

-   Especifica la anchura (la `W` es por *width*) del área en pixels. El valor por defecto es 0:

    $ pdftotext -W valor-ancho

-   Especifica la altura (la `H` es por *height*) del área seleccionada en pixels. El valor por defecto es 0.

    pdftotext -H valor-alto

-   Si queremos conservar el aspecto tanto como se pueda, hay que apuntar la opción `-layout`. El valor por defecto es `undo`, que fuerza el texto a mostrarse en texto corrido.

    pdftotext -layout

-   Ancho fijo tabulado, con el valor de la anchura en puntos, lo cual fuerza el modo de disposición física:

    pdftotext -fixed valor-ancho-en-puntos

-   Generación de archivo *HTML* que incluya la meta información, encaja el texto en elementos `<pre>` y `</pre>`

    pdftotext -htmlmeta

-   Con la opción `-bbox` se genera un archivo *XHTML* que contiene caja de información de cada palabra.

    pdftotext -bbox

-   Si queremos especificar la codificación del formato de salida. Por defecto es *UTF-8*:

    pdftotext enc codificacion

## Ghostscript<a id="orgheadline54"></a>

-   Es el lenguaje que entienden las impresoras.
-   Se puede utilizar para reducir el tamaño de archivos *PDF*
-   Si tienes *Ghostscript* instalado (`gs`), puedes correr este comando en consola:

    gs -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/screen -sOutputFile=nuevo_archivo.pdf original.pdf

En las opciones de `-dPDFSETTINGS`, puedes optar por:

-   `/screen`. si quieres una baja resolución y un tamaño pequeño.
-   `/ebook`, selecciona resolución media y tamaño mediano.
-   `/printer` y `/prepress`, para resoluciones altas

## PDFtk<a id="orgheadline57"></a>

-   PDFtk permite realizar muchas operaciones con *PDF*
-   Necesitas el comando `pdftk` desde la terminal.
-   O bien o [pdf toolkit](http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) <http://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/>

### Rotar documentos<a id="orgheadline55"></a>

-   Para rotar por completo un *PDF* o páginas determinadas, en los puntos cardinales elegidos.
-   Por ejemplo, para rotar una página 90 grados en el sentido de las agujas del reloj:

    pdftk entrada.pdf cat 1east output salida.pdf

-   Donde `1east` significa que la página `1` gira 90º al `East` (Este)

Las opciones son:

-   `north`, 0 grados
-   `east` o `right`, 90º
-   `south` o `down`, 180º
-   `west` o `left`, 270º

`left`, `right` and `down` hacen ajustes relativos a la rotación de la páginas.

### Dividir un PDF en varios<a id="orgheadline56"></a>

-   Si queremos dividir (*split*) un *PDF* muy largo en varios documentos *PDF*, podemos utilizar la opción `burst`

    pdftk pdflargo.pdf burst

Lo que dará como resultado tantos archivos *PDF* como páginas tenía el documento.

## ImageMagick<a id="orgheadline58"></a>

-   *Imagemagick* es un conjunto de herramientas en consola para modificar y tratar imágenes, bien en el momento o bien integrado en un *script* en *bash*.
-   Lo podemos utilizar para convertir imágenes en *PDF* y así manipular el documento como *PDF*.
-   Utiliza el comando `convert`

    convert *.jpg +adjoin page-%d.pdf

-   Donde `jpg` es el formato de la imagen, pero podríamos trabajar también con archivos `png` o `gif`.
-   O ajustar los parámetros de conversión:

    convert -density 150 archivo.pdf -quality 90 salida.png

## Poppler-utils<a id="orgheadline59"></a>

-   Con las utilidades *poppler-utils* manipulamos *PDF*
-   Su paquete *pdftoppm* permite convertir *PDF* a imágenes en formato *ppm*, *png* o *jpg*.

    pdftoppm -png file.pdf prefijo

-   Lo que produce tantos *png* como páginas tiene, con el prefijo *prefix*.
-   La resolución por defecto es 150 *ppp* *puntos por pulgada*.
-   Para incrementar la resolución, se puede hacer con las opciones `rx` y `ry`.

    pdftoppm -rx 300 -ry 300 -png archivo.pdf prefijo

-   Para imprimir solo una página, se utiliza la opción `singlefile`, y con la opción `n` se especifica el número de página:

    pdftoppm -f N -singlefile -png file.pdf prefix

-   La primera página es la número 1.

## Rmagick<a id="orgheadline60"></a>

-   [Rmagick](http://rmagick.rubyforge.org/portfolio.html) es otra herramienta que recomiendan en el artículo de ProPublica para trabajar con imágenes desde la consola
-   También permite realizar dibujos en 2D.
-   Transformaciones: <http://rmagick.rubyforge.org/portfolio.html>
-   Dibujos: <http://rmagick.rubyforge.org/portfolio3.html>
-   Efectos especiales: <http://rmagick.rubyforge.org/portfolio2.html>
-   Repositorio en GitHub: <http://github.com/rmagick/rmagick>

## PDF Split and Merge<a id="orgheadline61"></a>

-   Si nos da un poco de respeto o no podemos acceder a una línea de comandos, podemos contar con [PDF Split and Merge](http://sourceforge.net/projects/pdfsam/%0A)
-   Se trata de una herramienta en modo gráfico (y también en línea de comandos) para separar, juntar, mezclar y rotar *PDF*.
-   Está disponible para *Windows*, *MacOSX* y *GNU/Linux* y el único requisito es que necesita del entorno virtual de *Java*.
-   Entre sus funcionalidades, destacan:
    -   Pegar documentos *PDF*
    -   Dividir documentos *PDF*, especificando el número de páginas
    -   Dividir documentos *PDF*, especificando el nivel de los marcadores
    -   Rotar *PDF*
    -   Mezclar dos documentos *PDF*, componiendo uno nuevo que alterne una página de cada.
    -   Componer visualmente un nuevo *PDF* arrastrando páginas de otros *PDF*.

## Herramientas Web<a id="orgheadline62"></a>

-   Zamzar, Cometdocs y Smallpdf son servicios web online.
-   Por tanto, el documento deja de estar en tu equipo y pasa por Inet hasta sus servidores.
-   Se suben los archivos ahí y o bien te devuelven una salida en un formato de texto o bien un correo electrónico con un enlace para que los puedas descargar.
-   [Zamzar](http://www.zamzar.com/) es un servicio web para realizar conversiones de todo tipo.
-   [Cometdocs](http://www.cometdocs.com/) es otro servicio web para realizar conversiones aunque también funciona como servicio de almacenamiento y para compartir archivos. Dispone de una versión escritorio para *Windows* e *iOS*. También dispone de una API como servicio de pago.
-   [smallpdf](http://smallpdf.com/) es otro servicio web que permite manipular y convertir *PDF*

## Tika<a id="orgheadline63"></a>

-   [OKFN Labs](http://okfnlabs.org) tiene en fase beta un [servicio web](http://okfnlabs.org/blog/2015/02/21/documents-to-text.html) que permite convertir un gran número de tipos de archivo a `TXT`:
-   El servicio web se encuentra en <http://beta.offenedaten.de:9998/tika>, y para comprobar su funcionamiento tan solo hemos de tener una imagen que contenga texto y lanzar la consulta, en *Mac*, *GNU/Linux* o *Cygwin*, desde la terminal:

    curl -T ruta_archivo_imagen http://beta.offenedaten.de:9998/tika

-   En `STDOUT`, es decir, en la consola, se nos mostrará el texto que contiene la imagen.

-   Si queremos guardarlo automáticamente en una archivo de texto para facilitar su revisión, podemos añadir una concatenación de tareas:

    curl -T ruta_archivo_imagen http://beta.offenedaten.de:9998/tika > ruta_archivo_a_revisar.txt

-   El proyecto lo realizó Matt Fullerton de [OKFNLabs](http://okfnlabs.org) a partir del servidor web de *Apache* *Tika Project*, que soporta *Tesseract*.
-   Ha creado una imagen *docker* por si quieres replicarlo en tu [propio servidor](https://registry.hub.docker.com/u/mattfullerton/tika-tesseract-docker/%0A)
-   Y también puedes construirla desde [GitHub](https://github.com/mattfullerton/tika-tesseract-docker)

## Good Tables<a id="orgheadline64"></a>

-   *Good Tables* es otro proyecto de [OKFNLabs](http://okfnlabs.org) que consiste en un paquete *Python* para validar datos tabulares.
-   Puede funcionar con simples *CSV* o en una tubería de procesos *ETL*.
-   Se trata de una versión alfa
-   Artículo sobre Good Tables, <http://okfnlabs.org/blog/2015/02/20/introducing-goodtables.html>
-   Read the Docs, <https://goodtables.readthedocs.org/en/latest/>

# Un caso singular: ProPublica<a id="orgheadline68"></a>

-   [ProPublica](http://propublica.org/) realiza grandes investigaciones de periodismo de datos.
-   Y tanto o más importante: lo documentan.
-   Un ejemplo concreto lo tuvieron con el proyecto [Dollars for Docs](https://projects.propublica.org/docdollars/) y cómo utilizaron [varias herramientas](http://www.propublica.org/nerds/item/image-to-text-ocr-and-imagemagick)
-   En este caso crearon la guía *Scraping for Journalism, A guide for Collecting Data*
    -   [Recolección de datos](https://www.propublica.org/nerds/item/doc-dollars-guides-collecting-the-data)
    -   [Tratamiento de imágenes](http://www.propublica.org/nerds/item/image-to-text-ocr-and-imagemagick)
    -   [PDF scraping](http://www.propublica.org/nerds/item/turning-pdfs-to-text-doc-dollars-guide)

## El proceso<a id="orgheadline66"></a>

Ante una tabla de datos en una imagen:

1.  En un programa de tratamiento de imágenes, con líneas guía, crearon una cuadrícula donde el texto de cada celda pudiera posteriormente seleccionarse con la herramienta de selección rectangular.
2.  Dividieron la imagen y crearon imágenes nuevas, una por cada celda con texto, identificándolas apropiadamente con el número de celda por fila (*row*) y por columna (*column*) correcto.
3.  Para ello utilizaron distintas operaciones de *RMagick*.
4.  Descartaron todo el espacio en blanco de los márgenes de la tabla con [bounding\_box](http://studio.imagemagick.org/RMagick/doc/image1.html#bounding_box),
5.  Convirtieron la tabla a blanco y negro (escala de grises) para que el *OCR* funcione mejor.
6.  Primero probaron con las opciones de *RMagick* `quantize` y `contrast`, pero como los resultados no fueron los esperados lo hicieron con *Photoshop*, que permite también operaciones por lotes.
7.  Crearon una imagen con cada celda con un nombre que lo identificara su posición en la tabla por número de fila y número de columna. Así lograron 500 archivos de imagen.
8.  Detectaron las líneas de la tabla para crear coordenadas de celdas con la opción `get_pixels`, sobre las que cortar la imagen de la tabla en imágenes de cada celda.
9.  Realiza *OCR* con *tesseract*, integrado en el *script* con esta llamada (más adelante se ve el *script* completo donde se integra esta llamada):

    `tesseract /cell-files/#{j}x#{i}.tif /cell-files/#{j}x#{i}.txt `

1.  Construye la tabla de datos en modo texto con el texto resultante del paso anterior, también de manera automatizada incorporándolo al *script*:

    \# abre el archivo que tesseract ha creado y almacena el texto en el array
    	       text_row << File.open("cell-files/#{j}x#{i}.txt", 'r').readlines.map{|line| line.strip}.join(" ")
    
    	     end
    
    \# une el array con los caracteres de tabulación y produce una salida de datos en una línea
    	     output_file.puts( text_row.join("\t"))

1.  Limpieza de los datos, ya que *Tesseract* puede equivocarse en caracteres similares, como por ejemplo `0` de cero y `O` de o mayúscula. Por lo que probablemente no podamos dejar de hacer una comprobación manual, si bien en este proceso podemos implicar a más personas, bien a través de las citadas *Crowdcrafting* o *mTurk*. En este sentido, ProPublica utilizó *mTurk* y realizó esta [guía](http://www.propublica.org/article/propublicas-guide-to-mechanical-turk).

## PDFTables<a id="orgheadline67"></a>

Servicio web creado por ScraperWiki, un servicio de *web scraping*, para extraer tablas de PDFs. Requiere crearse un usuario. Puedes descargar los resultados a través del navegador. Advierten que si usas muchos documentos, tendrás que convertirte en usuario de pago.
<https://pdftables.com/>

# OCR<a id="orgheadline71"></a>

El reconocimiento óptico de caracteres *OCR* (por sus siglas en inglés *Optical Character Recognition*) nos permite convertir imágenes que contienen texto en documentos de texto gracias a algoritmos automáticos que realizan ese reconocimiento.

## Google Drive<a id="orgheadline69"></a>

-   Google Drive realiza OCR sobre imágenes individuales en formato *jpg*, *png* o *gif* pero también en documentos *PDF* de una o más páginas
-   Google recomienda ciertas pautas para el uso de OCR:
    -   Los archivos han de tener la más alta resolución, ya que así funcionará mejor OCR. Como medida de ejemplo, recomiendan que cada línea de texto sea de al menos diez píxeles de altura.
    -   Es importante que estén orientados en horizontal de izquierda a derecha. Si no lo tienes así, utiliza las herramientas citadas anteriormente para resolverlo.
    -   Los idiomas y conjuntos de caracteres que soporta con seguridad son *Latin*, el soporte de otros es experimental. Puedes elegir el idioma de los documentos en el menú.
    -   Reconocen mejores resultados en fuentes comunes como *Arial* o *Times New Roman*.
    -   La calidad de la imagen también es importante. Las imágenes con mayor contraste funcionan mejor, las que están movidas o borrosas peor.
    -   El tamaño máximo para las imágenes es de 2 MB por imagen.
-   En los documentos *PDF* solo trabajará con las 10 primeras páginas, por lo que conviene dividir los documentos.
-   *Google OCR* pretende mantener el formato básico del texto, como son las negritas o las itálicas, el tamaño y el tipo de fuente y los saltos de línea, pero reconocen que detectar estos elementos es complicado y no siempre lo consiguen.
-   Otros contenidos estructurados como listas numeradas, listados estructurados, tablas, columnas de texto, pies de página y notas finales es probable que no sean reconocidos.

## Tesseract-ocr<a id="orgheadline70"></a>

-   [Tesseract](https://github.com/tesseract-ocr) se anuncia como las más completa y precisa solución de código abierto disponible para el reconocimiento óptico de caracteres.
-   Combinado con la librería de procesamiento de imágenes *Leptonica*, lee varios formatos de imagen y convierte texto de más de sesenta idiomas.
-   En 2006 Google retoma el proyecto y lo mejora.
-   Está disponible para *Windows*, *Mac OSX* y *GNU/Linux* en línea de comandos.
-   Cuenta con una licencia *Apache License 2.0*.

Para utilizarlo en línea de comandos, podemos hacerlo de esta simple manera:

    tesseract imagen.png out

Lo que producirá un archivo `out.txt` con el texto que ha conseguido reconocer de esa imagen.

Podemos especificar el idioma con la opción `l`

    tesseract imagen.png out -l spa

Donde `spa` corresponde a *Spanish*. Otros idiomas pueden ser:

-   `ara` para árabe
-   `cat` para catalán
-   `chi_sim` para chino simplificado
-   `chi_tra` para chino tradicional
-   `deu` para alemán
-   `eng` para inglés
-   `fra` para francés
-   `glg` para gallego
-   `ita` para italiano
-   `rus` para ruso.

El listado completo lo puedes encontrar en <https://tesseract-ocr.googlecode.com/svn/trunk/doc/tesseract.1.html#_languages>

-   Las instrucciones para la instalación están disponibles en <https://code.google.com/p/tesseract-ocr/wiki/ReadMe>.
-   El manual completo con las distintas opciones y argumentos de entrada y salida está disponible en <https://tesseract-ocr.googlecode.com/svn/trunk/doc/tesseract.1.html>
-   Tesseract-ocr, <https://code.google.com/p/tesseract-ocr/>

# Referencias bibliográficas     :OK:<a id="orgheadline72"></a>

-   Aristarain, Manuel & Tigas, Mike & Merril, Jeremy B. (2014) *Scraping PDFs with Tabula*. URL: <https://s3.amazonaws.com/media.miketigas.com/files/20140627/20140627-tabula-IRE2014-withnotes.pdf>

-   Crucianelli, Sandra. (2013) *Herramientas digitales para periodistas*. Centro Knight para el Periodismo en las Américas de la Universidad de la Universidad de Texas. URL: <https://knightcenter.utexas.edu/books/HDPP.pdf>

-   García Santiago, Lola. (2003) *Extraer y visualizar información en Internet: el Web Mining*. Gijón: Ediciones Trea

-   Gray, Jonathan & Bounegru, Liliana & Chambers, Lucy. (2012) *Data Journalism Handbook*. European Journalism Centre y Open Knowledge Foundation. URL: <http://datajournalismhandbook.org/>

-   Kayser-Brill, Nicolas. (2014) *Data wants to be free! (and clean)*. Medialab-Prado. URL: <http://bit.ly/free-clean>

-   Méndez Rodriguez, Eva Mª. (2002) *Metadatos y Recuperación de información: estándares, problemas y aplicabilidad en bibliotecas digitales*. Gijón: Trea

-   Nguyen, Dan. (2010) *Chapter 3: Turning PDFs to Text*. Propublica, Journalism in the Public Interest. URL: <https://www.propublica.org/nerds/item/turning-pdfs-to-text-doc-dollars-guide>

-   Nguyen, Dan. (2010) *Chapter 5: Getting Text Out of an Image-Only PDF*. ProPublica, Journalism in the Public Interest. URL: <https://www.propublica.org/nerds/item/image-to-text-ocr-and-imagemagick>

-   Schoolofdata, (2014) *Obteniendo datos de los PDF*. Web: School of Data. URL: <http://es.schoolofdata.org/obteniendo-datos-de-los-pdfs/>

# Manuales<a id="orgheadline73"></a>

-   Cómo utilizar *Google OCR*,  <https://www.youtube.com/watch?v=DPJJON26Do4>
-   Introducción al scraping de *PDF*, <http://www.irekia.euskadi.eus/es/news/11703-introduccion-google-refine-curso-periodismo-datos>
