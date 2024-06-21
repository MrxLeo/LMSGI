# Unidad 1: Introducción a los lenguajes de marcas:
* ## Qué es un lenguaje de marcas:
    * **Un lenguaje de marcas, es un conjunto de etiquetas, utilizadas para definir la estructura y el diseño de un documento. Las etiquetas, proporcionan información semántica sobre los contenidos, en lugar de especificar su presentación o diseño.**
* ## Evolución de los lenguajes de marcas:
    * **GML: Fue desarrollado originalmente en los años 60, para el direccionamiento e indexación de documentos gubernamentales estadounidenses.**
    * **SGML: Fue desarrollado en los años 80, como metalenguaje estándar, para definir estructuras de documentos.**
* ## Características de los lenguajes de marcas:
    * **Utiliza etiquetas para definir la estructura y la semántica del documento.**
    * **Separa el contenido de la presentación y el formato.**
    * **Se da más importancia a la estructura lógica que a la presentación visual.**
    * **Lectura programable/máquina en lugar de lectura humana.**
    * **Flexible y ampliable mediante el uso de etiquetas definidas.**
* ## Características y ejemplos de los siguientes lenguajes de marcas:
    * **XML:**
        - **Metalenguaje utilizado para definir otros lenguajes como HTML.**
        - **Utiliza etiquetas de elementos con sintaxis de inicio `<tag>` y fin `</tag>`.**
        - **Los atributos proporcionan información adicional sobre los elementos.**
        - **Debe estar bien formado, con etiquetas de inicio/fin coincidente.**
    * **HTML:**
        - **Lenguaje de marcas para páginas web.**
        - **Numerosas etiquetas predefinidas para elementos comunes de los documentos.**
        - **Formato menos estricto que XML.**
        - **Soportado por todos los navegadores web para renderizar páginas.**
    * **JSON:**
        - **Formato ligero de intercambio de datos derivado de JavaScript.**
        - **Utiliza pares nombre/valor y listas ordenadas para almacenar y transmitir datos.**
        - **Popular como alternativa a XML para estructuras de datos más sencillas.**
    * **YAML:**
        - **Formato de serialización de datos amigable para los archivos de configuración.**
        - **Se inspira en XML, pero utiliza una sintaxis diferente para especificar listas, mapas y otras estructuras.**
        - **Comúnmente utilizado para archivos de configuración, pero también formato de datos de uso general.**
    * ## XML: definición y características del metalenguaje:
    * **XML es un metalenguaje que define reglas para crear otros lenguajes de marcas personalizados. Como metalenguaje, XML permite definir las etiquetas y la estructura del documento específicas de un dominio o aplicación.**
    * **El prólogo:**
        - **El prólogo XML proporciona información sobre la codificación de caracteres y la versión XML. Aparece en la parte superior del documento, antes del elemento raíz.**
    * **Etiquetas:**
        - **Las etiquetas están delimitadas por `<>`, y proporcionan etiquetas y estructura a los elementos. Todas las etiquetas deben cerrarse correctamente.**
    * **Atributos:**
        - **Los atributos proporcionan información adicional sobre los elementos, y adoptan la forma de pares nombre/valor en la etiqueta de inicio, como `<tag attribute="value">.`**
    * **Ejemplo en XML:**
    ```xml
    <?xml version="1.0" encoding="UTF-8"?>
    <catalogo>
        <libro ID="01"> 
            <autor>John Doe</author>
                <titulo>Guía del desarrollador XML</titulo> 
                    <genero>Informática</genero>
                    <precio>40 </precio>
                <publicacion>31/12/2023</publicacion>
             <descripcion>Una mirada en profundidad a la creación de aplicaciones con XML.</descripcion>
        </libro>
    </catalogo>
    ```
=======
# Actividad Cuaderno Clase UD1:
## ¿Qué es un lenguaje de marcas?
* **Un lenguaje de marcas, es un conjunto de etiquetas de marcas, utilizadas para definir la estructura, y el diseño de un documento. Es decir, que las etiquetas de marcas, proporcionan información semántica, sobre los contenidos, en lugar de especificar su presentación o diseño. Por lo tanto, es un sistema de anotación de un documento, que se distingue sintácticamente del contenido del texto. Los lenguajes de marcas, permiten etiquetar los elementos del documento, para así, identificar elementos especiales como títulos, párrafos, listas, énfasis, etc. Mientras que las etiquetas, proporcionan información semántica, sobre la estructura, y el significado del documento.**
## Evolución de los lenguajes de marcas:
* **GML: Desarrollado originalmente en la década de 1960, para el direccionamiento e indexación de documentos del gobierno de U.S. El GML, fue uno de los primeros lenguajes de marcas estandarizados de uso general. Su objetivo principalmente, era ofrecer un sistema de intercambio de documentos estructurados independiente de las aplicaciones.**
* **SGML: Desarrollado en los años 80, como metalenguaje estándar, para definir estructuras de documentos. El SGML, fue el primer lenguaje de marcas internacional normalizado, de uso general que constituyó, la base del tratamiento general de documentos. Permitiendo definir metalenguajes, para clases específicas de documentos. Esto quiere decir, que el SGML, se desarrolló en la década de 1980, como la primera norma ISO aceptada internacionalmente para definir lenguajes de marcas generalizados para documentos. El SGML, introdujo el concepto de separar la estructura lógica de la presentación física. Por lo que, permitía que los documentos fueran independientes de las aplicaciones y las representaciones.**
## Características de los lenguajes de marcas:
* **Utiliza etiquetas, para definir la estructura y la semántica del documento.**
* **Énfasis en la estructura lógica por encima de la disposición visual.**
* **Flexible y ampliable mediante el uso de etiquetas definidas.**
* **Separa el contenido de la presentación, mediante el uso de etiquetas.**
* **Añade estructura semántica y etiquetas de metadatos, para así identificar elementos como títulos, párrafos, etc.**
* **Permite múltiples representaciones y renderizaciones, del mismo contenido estructurado.**
* **Apoya la validación de documentos, con respecto a las definiciones de tipo de documento definidas.**
* **Son independientes de la aplicación y la plataforma, ya que separan la estructura lógica de la visualización.**
## Características y ejemplos de los siguientes lenguaje de marcas:
* **XML:**
    * **El XML, se basa en el SGML y es un formato de texto sencillo y muy flexible para datos estructurados. Permitiendo a los usuarios, definir sus propias etiquetas mediante el uso de un `DOCTYPE`, para definir qué elementos están permitidos.**
    * **Metalenguaje utilizado para definir otros lenguajes como HTML.**
    * **Utiliza etiquetas de elementos con sintaxis de inicio `<tag>` y fin `</tag>.`**
    * **Los atributos, proporcionan información adicional sobre los elementos.**
    * **Debe estar bien formado con etiquetas de inicio/fin que coincidan.**
* **HTML:**
    * **HTML, es el lenguaje de marcas estándar, utilizado principalmente, para crear páginas, y aplicaciones web. Los elementos y etiquetas HTML, definen la estructura, y el diseño de una página web.**
    * **Numerosas etiquetas predefinidas para elementos comunes de los documentos.**
    * **Formato menos estricto que XML.**
    * **Soportado por todos los navegadores web, para renderizar páginas.**
* **JSON:**
    * **JSON, es un formato ligero de intercambio de datos fácil de leer, y escribir para los humanos, y de analizar para las máquinas. Se utiliza principalmente para transmitir datos entre un servidor y una aplicación web.**
    * **Formato ligero de intercambio de datos derivado de JavaScript.**
    * **Utiliza pares nombre/valor y listas ordenadas para almacenar y transmitir datos.**
    * **Popular como alternativa a XML para estructuras de datos más sencillas.**
* **YAML:**
    * **YAML, es un estándar de serialización de datos amigable diseñado para todos los lenguajes de programación. Pudiendo ser analizado por la mayoría de los lenguajes de programación modernos, lo que lo convierte en un formato popular para configuraciones y serialización de datos.**
    * **Formato de serialización de datos amigable para los archivos de configuración.**
    * **Se inspira en XML, pero utiliza una sintaxis diferente para especificar listas, mapas y otras estructuras.**
    * **Comúnmente, utilizado para archivos de configuración, pero también utilizado para formato de datos de uso general.**
## XML: definición y características del metalenguaje:
* **XML es un metalenguaje, que define reglas para crear otros lenguajes de marcas personalizado, es decir, como metalenguaje, XML permite definir las etiquetas y la estructura del documento específicas de un dominio o aplicación. Es un lenguaje que permite definir lenguajes de marcas para estructurar, almacenar y transportar datos. No es un lenguaje de marcas propiamente dicho, sino que permite definir lenguajes de marcas específicos.**
* **Prólogo: El prólogo XML proporciona información sobre la codificación de caracteres y la versión XML. Aparece en la parte superior del documento, antes del elemento raíz.**
* **Tags: Las etiquetas están delimitadas por `<` `>` y proporcionan etiquetas y estructura a los elementos. Todas las etiquetas deben cerrarse correctamente.**
* **Atributos: Los atributos proporcionan información adicional sobre los elementos y adoptan la forma de pares nombre/valor en la etiqueta de inicio, como `<tag attribute="value">`.**
## Ejemplo en XML:
```xml
<?xml version="1.0" encoding="UTF-8"?>
    <catalogo>
        <libro ID="1">
            <autor>Matthew Gambardella</autor>
                <titulo>Guía del desarrollador XML</titulo>
                    <genero>Informatica</genero>
                    <precio>44.95</precio>
                <fecha>01/01/2023</fecha>
            <descripcion>Una mirada en profundidad a la creación de aplicaciones con XML.</descripcion>
        </libro>
    </catalogo>
```
# Actividad Cuaderno Clase UD2:
## Documentos XML, estructura:
* **Declaración o prologo: La declaración o prólogo, contiene la declaración XML, y la información de codificación. Se encuentra, en la parte superior del documento XML.**
* **Elementos: Los elementos son los principales componentes de un documento XML. Contienen tanto contenido (texto, otros elementos, etc.) como atributos. Los elementos se definen mediante etiquetas de inicio y fin.**
* **Atributos: Los atributos, proporcionan información adicional sobre los elementos. Se definen dentro, de la etiqueta de inicio de un elemento con el formato: `nombre="valor"`.**
* **Comentarios: Los comentarios en XML, empiezan por `<!--` y terminan por `-->`. Se utilizan, para añadir notas, o explicaciones al código, sin afectar a su funcionalidad.**
* **Espacios de nombres: Los espacios de nombres, se utilizan para evitar conflictos, entre nombres de elementos. Asocian elementos, y atributos, con identificadores denominados espacios de nombres.**
* **Entidades: Las entidades, permiten sustituir partes de un documento XML, por otros valores o recursos externos, mediante referencias a entidades.**
* **CDATA: Las secciones CDATA, se utilizan para escapar de bloques de texto que contienen caracteres que, de otro modo, se reconocerían, como marcas. Están delimitadas por `<![CDATA[` y `]]>`.**
## Validación de documentos:
* **DTD: Es un mecanismo para definir los elementos, y atributos legales de la estructura, de un documento XML.**
    * **Entidades: Las entidades declaradas, en la DTD pueden referenciarse, en el contenido de los elementos, mediante referencias a entidades.**
    * **Anotaciones: Las anotaciones documentan la DTD mediante comentarios.**
    * **Elementos: Se definen los elementos permitidos, en el documento XML, y los elementos hijos que puedan contener.**
    * **Atributos: Los atributos de los elementos se definen, junto con las restricciones de los valores posibles.**
* **XMLSchema: Un XMLSchema, ofrece más flexibilidad, y capacidades que los DTD, para definir la estructura y la semántica de los documentos.**
    * **Definición: La estructura básica del esquema XML, define los espacios de nombres, las ubicaciones del esquema, y los espacios de nombres de destino.**
    * **Estructura básica: Los elementos, atributos, y tipos complejos/simples se definen, junto con las restricciones.**
    * **Elementos locales y globales: Los elementos, pueden definirse localmente, para un elemento específico o globalmente.**
    * **Elementos simples: Definir elementos, con contenido simple como cadenas, fechas, etc.**
    * **Elementos complejos: Definir elementos, que pueden contener otros elementos y atributos.**
    * **Subelementos: Se permiten elementos, como hijos de un elemento definido.**
    * **Atributos: Los atributos de los elementos, se definen junto con los tipos de datos, y las restricciones.**
    * **Restricciones: Los esquemas pueden imponer restricciones a los elementos y atributos mediante funciones como longitudes mínimas/máximas, enumeraciones, etc.**
    * **Tipos de datos: Los esquemas, admiten tipos de datos incorporados, como cadenas, decimales, etc., y tipos definidos por el usuario.**
    * **Comentarios en XMLSchema: Se pueden añadir comentarios, para describir partes del esquema, utilizando la sintaxis de comentarios XML.**
# Actividad Cuaderno Clase UD7:
## SGI (Sistemas de gestión de la información):
* **Características: Los SGI, están diseñados, para organizar, almacenar, y procesar datos, para así, apoyar los procesos de negocio. Por lo que, las características claves, incluyen:**
    * **Almacenamiento centralizado: Los SGI, centralizan el almacenamiento de datos, para facilitar, el acceso, y la gestión.**
    * **Seguridad de los datos: Implementación de medidas, para proteger la integridad, y confidencialidad de los datos.**
    * **Escalabilidad: Debe gestionar, volúmenes de datos, y cargas de usuarios, cada vez mayores.**
    * **Integración: Se integra, con otros sistemas, para garantizar, un flujo de datos fluido.**
* **Tipos: Existen varios tipos de SGI, entre ellos:**
    * **Sistemas de gestión de bases de datos relacionales (RDBMS): Organizan los datos, en tablas, con relaciones.**
    * **Sistemas de Gestión Documental (SGD): Gestionan documentos,y facilitan, la colaboración.**
    * **Sistemas de gestión de contenidos (CMS): Gestionan contenidos digitales, como sitios web, y medios de comunicación.**
    * **Sistemas de gestión del conocimiento (KMS): Organizan, y recuperan, el conocimiento de la organización.**
## ERP (Planificación de recursos empresariales):
* **Características y ventajas: Los sistemas ERP, integran los procesos organizativos, y empresariales. Sus principales características, y ventajas son las siguientes:**
    * **Integración de procesos: El ERP, consolida varios procesos empresariales, en un sistema unificado.**
    * **Información en tiempo real: Proporciona, datos en tiempo real, para la toma de decisiones.**
    * **Eficacia: Mejora la eficiencia operativa, mediante la racionalización de los procesos.**
    * **Reducción de costes: Reduce los costes operativos, mediante la optimización de procesos.**
* **Ejemplos de ERP, más conocidos:**
    * **ERP SAP: Ampliamente utilizado, para gestionar las operaciones empresariales, y las relaciones, con los clientes.**
    * **Oracle ERP Cloud: Ofrece, un conjunto completo, de aplicaciones integradas.**
## CRM (Gestión de las relaciones con los clientes):
* **Características y ventajas: Los sistemas de gestión de las relaciones con los clientes (CRM), se centran, en la gestión de las interacciones, con los clientes. Las características, y ventajas claves, incluyen:**
    * **Centralización de datos de clientes: Centraliza, la información del cliente, para una mejor comprensión, y compromiso.**
    * **Automatización de ventas y marketing: Automatiza, los procesos de ventas, y marketing, para una mayor eficiencia.**
    * **Mejora del servicio al cliente: Mejora, el servicio al cliente, a través de procesos racionalizados.**
* **Ejemplos de CRM, más conocidos:**
    * **Salesforce: La plataforma CRM líder, para ventas, servicio y marketing.**
    * **HubSpot CRM: Ofrece, herramientas de marketing, ventas, y servicio al cliente.**
## BI (Inteligencia de negocio):
* **Definición y componentes: Business Intelligence (BI), implica herramientas de análisis de datos, para tomar decisiones empresariales informadas. Los componentes incluyen:**
    * **Almacenamiento de datos: Almacenamiento de grandes volúmenes de datos estructurados.**
    * **OLAP (Procesamiento analítico, en línea): Permite, el análisis multidimensional de datos.**
    * **Minería de datos: Extracción de patrones, y conocimientos, a partir de grandes conjuntos de datos.**
    * **Cuadros de mando: Representaciones visuales de indicadores clave de rendimiento.**
    * **ETL (Extracción, transformación y carga):**
        * **Extraer: Recupera datos de diversas fuentes.**
        * **Transformación: Procesa, y limpia los datos, para su análisis.**
        * **Carga: Carga los datos transformados, en un almacén de datos.**
    * **Minería de datos:**
        * **Extrae patrones, e información de grandes conjuntos de datos, para identificar tendencias, y relaciones.**
    * **Cuadro de mando:**
        * **Una representación visual de los indicadores clave de rendimiento, y las métricas empresariales, para obtener información rápida.**
# Actividad Cuaderno Clase UD3:
## HTML, y su evolución:
* **HTML (HyperText Markup Language) es el lenguaje estándar para crear páginas y aplicaciones web. Fue desarrollado por primera vez por Tim Bernes-Lee en 1991 y desde entonces ha sufrido varias versiones y mejoras.**
    * **Evolución del HTML:**
        * **HTML 1.0 (1991): La primera versión, muy básica, con etiquetas limitadas.**
        * **HTML 2.0 (1995): Añadió formularios y tablas.**
        * **HTML 3.2 (1997): Introduce soporte para applets, scripts y estilos.**
        * **HTML 4.01 (1999): Introduce el concepto de Modelo de Objetos del Documento (DOM) y mejora la accesibilidad.**
        * **XHTML 1.0 (2000): Una versión más estricta de HTML 4.01, basada en XML.**
        * **HTML5 (2014): Introdujo nuevos elementos semánticos, soporte multimedia y APIs.**
        **Diferencias, ventajas y desventajas de XHTML con respecto a HTML:**
* **XHTML (Extensible HyperText Markup Language) es una versión más estricta y limpia de HTML, basada en XML.**
    * **Diferencias:**
        * **Reglas sintácticas: XHTML requiere una sintaxis bien formada (por ejemplo, todas las etiquetas deben estar cerradas).**
        * **Distinción entre mayúsculas y minúsculas: XHTML distingue entre mayúsculas y minúsculas, mientras que HTML no.**
        * **Declaración del tipo de documento: XHTML requiere una declaración DOCTYPE específica.**
    * **Ventajas:**
        * **Coherencia: Impone normas de codificación estrictas.**
        * **Interoperabilidad: Más fácil de analizar y procesar con herramientas XML.**
        * **Tratamiento de errores: Los errores se detectan más fácilmente gracias a una sintaxis estricta.**
    * **Desventajas:**
        * **Rigurosidad: Requiere una codificación más cuidadosa, lo que puede resultar engorroso.**
        * **Compatibilidad con versiones anteriores: Los navegadores más antiguos pueden no ser totalmente compatibles con XHTML.**
    * **Estructura de un documento HTML:**
        * **Un documento HTML suele seguir la siguiente estructura:**
    ```html
    <!DOCTYPE HTML>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <title>Título del documento.</title>
        <meta name="description" content="Descripción del documento">
        <link rel="stylesheet" href="estilos.css">
        <script src="script.js"></script>
        <title>Lenguajes de marcado web - Elementos de bloque.</title>
    </head>
    <body>
        <h1>Título principal</h1>
        <p>Párrafo del texto.</p>
    </body>
    </html>
    ```
    * **Cabecera HTML:**
        * **La etiqueta `<head>` contiene metadatos y recursos para el documento.**
    * **Título:**
        * **La etiqueta `<title>` define el título del documento, que aparece en la pestaña del navegador.**
    * **Meta:**
        * **La etiqueta `<meta>` proporciona metadatos como codificación de caracteres, autor y descripción.**
    ```html
    <meta charset="UTF-8">
    <meta name="description" content="Descripción del documento.">
    <meta name="author" content="Nombre del autor">
    ```
    * **Estilo:**
        * **La etiqueta `<style>` contiene estilos CSS internos.**
    ```html
    <style>
    body {
        background-color: #f0f0f0;
    }
    </style>
    ```
    * **Enlace:**
        * **La etiqueta `<link>` enlaza recursos externos como hojas de estilo.**
    ```html
    <link rel="stylesheet" href="estilos.css">
    ```
    * **Script:**
        * **La etiqueta `<script>` incluye o enlaza a archivos JavaScript.**
    ```html
    <script src="script.js"></script>
    ```
    * **Cuerpo HTML:**
        * **La sección "cuerpo" contiene el contenido visible del documento.**
    * **Elementos de bloque:**
        * **Los elementos de bloque ocupan todo el ancho de su contenedor y comienzan en una nueva línea.**
        * **Encabezamiento:`<h1>` a `<h6>`.**
        * **Párrafos: `<p>`.**
        * **Divisiones: `<div>`.**
        * **Listas: `<ul>`, `<ol>`, `<li>`.**
        * **Tablas: `<table>`, `<tr>`, `<td>`.**
        * **Formularios: `<form>`, `<input>`, `<textarea>`, `<button>`.**
    ```html
    <h1>Título principal.</h1>
    <p>Párrafo del texto.</p>
    <div>
        <ul>
            <li>Elemento 1.</li>
            <li>Elemento 2.</li>
        </ul>
    </div>
    ```
    * **Elementos en línea:**
        * **Los elementos en línea no empiezan en una nueva línea y sólo ocupan el ancho necesario.**
        * **Formato del texto: `<b>`, `<i>`, `<strong>`, `<em>`.**
        * **Enlaces: `<a>`.**
        * **Imágenes: `<img>`.**
        * **Span: `<span>`.**
    ```html
    <a href="https://ejemplo.com">Enlace de ejemplo.</a>
    <img src="imagen.jpg" alt="Imágen de ejemplo.">
    <span style="color: red;">Texto en rojo.</span>
    ```
    * **Listas, tablas y formularios:**
        * **Listas:**
        * **Lista desordenada: `<ul>`, `<li>`.**
        * **Lista ordenada: `<ol>`, `<li>`.**
        * **Lista descriptiva: `<dl>`, `<dt>`, `<dd>`.**
    ```html
    <ul>
        <li>Elemento 1.</li>
        <li>Elemento 2.</li>
    </ul>
    ```
    * **Tablas:**
        * **Elementos de la tabla: `<table>`, `<tr>`, `<td>`, `<th>`, `<thead>`, `<tbody>`, `<tfoot>`.**
    ```html
    <table>
        <thead>
            <tr>
                <th>Cabezera 1.</th>
                <th>Cabezera 2.</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Dato 1.</td>
                <td>Dato 2.</td>
            </tr>
        </tbody>
    <table>
    ```
    * **Formularios:**
        * **Elementos del formulario: `<form>`, `<input>`, `<textarea>`, `<button>`, `<select>`, `<option>`.**
    ```html
    <form action="submit.php" method="post">
        <label for="name">Nombre.</label>
        <input type="text" id="name" name="name">
        <button type="sumbit">Enviar.</button>
    </form>
    ```
    * **Elementos multimedia para HTML5:**
        * **Audio: `<audio>`.**
        * **Vídeo: `<video>`.**
        * **Canvas: `<lienzo>`.**
        * **SVG: `<svg>`.**
    ```html
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <video controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the audio element.
    </video>
    ```
    * **Herramientas de edición y desarrollo web:**
        * **Editores de texto: Visual Studio Code, Sublime Text, Atom.**
        * **IDEs: IntelliJ IDEA, WebStorm, Eclipse.**
        * **Herramientas de desarrollo para navegadores: Chrome DevTools, Firefox Developer Tools.**
        * **Control de versiones: Git, GitHub, GiLab.**
        * **Frameworks/Bibliotecas: Boostrap, jQuery, React, Angular.**
# Actividad Cuaderno UD 4:**
## CSS:
* **Generalmente, además de documentos HTML, se utiliza otro lenguaje de marcas, que se utiliza para mejorar el formato del diseño de documentos HTML, lamado CSS (Cascade Style Sheets).**
    * **CSS permite añadir estilo a un documento web para poder mejorar la presentación de la información.**
    * **CSS es mantenido por la W3C al igual que HTML y XML. Comenzó en 1996 y hoy en día es indespensable para cualquier página web.**
    * **La sintaxis de CSS se divide en todas las siguientes partes:**
    * **Selectores: Herramientas, que permiten seleccionar el elemento, o elementos, sobre los que aplicar reglas.**
    * **Declaraciones: Son las reglas para aplicar estilos a los distintos elementos, normalmente tienen una estructura clave valor.**
    * **Comentarios: Se aplican entre los caracteres `/* */`.**
    Ejemplo de CSS:
    ```css
    body{
    color: green;
    }
    ```
## Agregar CSS:
Para añadir CSS a un documento HTML, podemos hacerlo de las siguientes formas:
1. Como Documento externo usando una etiqueta link.

```<link rel=”stylesheet” href=”estilos.css” >```

2. Como elemento style dentro de la cabecera del documento.

```<style>…</style>```

3. Como elemento en línea usando el atributo style.

```<p style=”color:white”>...</p>```

### Prioridad al usar CSS
Cuando hay una o varias reglas que se superponen en diferentes elementos se
aplican las siguientes prioridades que se aplican en cascada:
* Origen e importancia: Primero se tienen en cuenta los estilos propios por
encima de los del propio navegador.
* Nivel de especificidad: Contra más específico más importante.
* Orden de aparición: Los últimos estilos en leerse tienen más prioridad.

Además, podemos establecer la máxima prioridad utilizando el modificador
```!important```.

También se pueden establecer una serie de valores para cada regla, para
reestablecer la prioridad:
* inherit: Activa la herencia, haciendo que la propiedad sea asignada con el
valor heredado del elemento padre.
* initial: El valor tomado será el valor por defecto.
* unset: Reestablece el valor a su valor natural.
* revert: Reestablece el valor de la propiedad al valor que habría tenido si no se hiciese cambio.
### Tipos de Datos y Unidades
En CSS podemos encontrar los siguientes tipos de datos:
* Entero: Números enteros positivos y negativos.
* Número: número decimal.
* Dimensión: un número con con una dimensión asociada; puede ser deg
(grados), s(segundos) o px(píxeles).
* Porcentaje: Indica un porcentaje o fracción se indica con el símbolo %.
* Colores: indican un color que puede ser uno predeterminado (green, red,
white…) valor RGB (rgba(22,33,11,20)), hexadecimal (#112233) o HSL (Hue
Saturation Lightness) (hsl(0,100%,50%)).

Por otro lado, existen diferentes Unidades que pueden clasificarse en Absolutas o relativas.

Unidades Absolutas:
* px: píxeles.
* cm: centímetro.
* mm: milímetro.
* Q: Cuarto de milímetro.
* in: Pulgada
* pt: Puntos (1/72 in).
* pc: Picas (1/16 in).

Unidades Relativas:
* em: Tamaño letra del padre.
* ex: Altura de la fuente del elemento.
* ch: Ancho del carácter.
* rem: Tamaño de letra del elemento Raíz.
* lh: Altura de la línea del elemento.
* vw: 1% del ancho de ventana gráfica.
* vh: 1% del alto de la ventana gráfica.
* vmin: 1% de la dimensión más pequeña de la ventana gráfica.
* vmax: 1% de la dimensión más grande de la ventana gráfica.
### Selectores
Como hemos comentado, un selector no es más que una regla para seleccionar
uno o varios elementos que modificarán sus reglas; podemos dividirlos en los
siguientes tipos:
* Universal: selecciona todos los elementos; ejemplo: *
* Tipo: Tipo de elemento: ejemplo: h1.
* Clase: elementos de una determinada clase: .clase.
* Identificador: elemento con un identificador en concreto; ejemplo:
#elemento.
* Atributo: elemento con un atributo en concreto; por ejemplo:
input[type=”submit”].

También podemos realizar combinaciones o agrupaciones:
* Agrupación: aplicará las reglas a todos esos elementos o clases; ejemplo:
h1,h2,h3.
* Combinación: indica que sólo aplicará a la combinación de varios elementos;
podemos clasificarlos en los siguientes casos:
    * Hermanos: Elemento hermano a otro; ejemplo: A~B.
    * Hijos: Elemento Hijo a otro; ejemplo: A>B.
    * Hermanos adyacentes: Elemento hermano a otro pero adyacente; ejemplo: A+B.
    * Descendientes: Elemento descendente;Ejemplo A B.
### Pseudoclases
Una pseudoclase es un modificador que se añade a un selector para que solo se
aplique cuando dicho elemento pase a un estado específico, normalmente se
establece con la siguiente sintaxis:

```CSS
selector:pseudoclase{
color: white;
}
```
Algunas de las pseudoclases son:
* active: cuando el elemento está activo.
* checked: cuando un checkbox está activo.
* disabled: cuando el elemento está deshabilitado.
* focus: Cuando el elemento tiene el foco.
* hover: Cuando el ratón pasa por encima.
* visited: Cuando el enlace apunta a una dirección ya visitada
anteriormente.

### Pseudoelementos
Un Pseudoelemento se añade a un selector para establecer el estilo de parte de dicho elemento; por ejemplo la primera letra o palabra; Los pseudoelementos
pueden ser:
* after: Permite añadir contenido después del elemento.
* before: Permite añadir contenido antes del elemento.
* first-letter: Primera letra del primer bloque de texto.
* first-line: Primera línea del primer bloque de texto.
* selection: Modificar el estilo cuando hay parte del contenido
seleccionado.
### Propiedades CSS
Una vez hemos visto los distintos selectores, vamos a ver algunas de las reglas más importantes de CSS.

Comenzaremos con ver las dimensiones del modelo de cajas. Algunas de las características son:
* Margen exterior: espacio circundante con otros elementos; se establece con la propiedadmargin.
* Margen Interior: espacio interior vacío que se agrega al elemento; se establece con la propiedad padding.
* Borde: Espacio que tiene distintos rellenos y diferentes colores; se establece con la propiedad border; aunque tiene diferentes variantes.
* Contorno: Se dibuja encima del elemento sin ocupar espacio; se establece con la propiedad outline.
* Ancho: ancho del elemento; se establece con la propiedad width.
* Alto: Alto del elemento: se establece con la propiedad height.

### Modelos de cajas
![Alt text](1cc44a6e53e6405796eddd976b77fe04.png)
### Display
Una de las propiedades más importantes es display; que permite establecer cómo se
mostrarán los elementos; algunos de los valores que permite son:
* **block**: indica que se mostrará como un bloque (ocupando todo el espacio
disponible).
* **inline**: Indica que se mostrará en línea (ocupando solo su contenido).
* **flex**: Se mostrará como un bloque pero establece el modelo denominado flexbox;
estableciendo una dirección por la que fluye. Se utiliza la propiedad
flex-direction, para ver en qué dirección fluirá
* **grid**: Se mostrará como bloque pero establece una cuadrícula. Se utiliza la propiedad
grid-template-columns para establecer la cuadrícula y sus dimensiones.
### Flex
```CSS
.container-flex{
    display: flex;
    flex-direction: column;
}
.container-flex div{
    padding: 5px;
    margin: 5px;
}
.container-flex p{
    text-align: center;
}
```
### Grid
```CSS
.container-flex{
    display: grid;
    grid-template-columns: 50% 50%;
}
.container-flex div{
    padding: 5px;
    margin: 5px;
}
.container-flex p{
    text-align: center;
}
```
### Float
Se puede establecer el comportamiento de dónde aparecerán los elementos y su
contenido con la propiedad float. 

Tiene los siguientes valores:
* left: empuja al elemento a la izquierda.
* right: empuja al elemento a la derecha.
* none: no empuja al elemento.
* inherit: hereda el valor de la propiedad float del elemento padre.

### Position
También es importante ver que la posición de un elemento pueda ser dependiendo
de su contenedor o por el mismo con la propiedad position. 

Tiene los siguientes valores:
* static: valor por defecto; se posiciona siguiendo el flujo normal.
* relative: Permite establecer su posición de forma relativa al anterior elemento.
* absolute: Establece la posición absoluta con respecto al documento.
* fixed: El elemento deja de seguir el flujo normal del documento.
* Sticky: EL elemento se posiciona siguiendo el flujo normal y se pueden
establecer la posición límite con su contenedor.

### Propiedades de texto
Podemos establecer una serie de propiedades para dar formato al texto:
* color: color del texto.
* font-family: el tipo de letra; se establece como una lista con prioridad.
* font-size: Tamaño del texto.
* font-weight: Determina el grosor del trazo.
* text-align: Determina la alineación del texto; tiene los valores: left,
right, center y justify.
* letter-spacing: espacio entre letras.
### Propiedades de lista
Algunas de las propiedades que podemos establecer las listas son:
* list-style-type: Indica el tipo de viñeta a utilizar; tiene los valores: disc,
circle, square, decimal, lower-roman, upper-roman,
lower-greek, lower-latin, lower-latin y none.
* list-style-position: establece la posición de las viñetas; puede ser
inside u outside.
* list-style-image: Establece una viñeta como una imagen pasando una
URL.
### Diseño adaptativo o Responsive
Hoy en día existen muchos dispositivos capaces de navegar por la web, desde ordenadores, tablets, dispositivos móviles e incluso ya gafas de realidad aumentada.

Es por ello que se necesita adaptar el CSS para cada pantalla; por lo que se utilizan las llamadas media
queries, que permiten seleccionar una serie de reglas dependiendo del tamaño de la pantalla.

```CSS
@media screen and (min-width: 480px) {
 body {
 background-color: lightgreen;
 }
}
```
# Sindicación de contenidos web
Dado a que hay muchisima información y no es facil dar a conocer nuestro contenido.
Por ello se pueden utilizar herramientas de sindicación de contenidos para poder difundir esta información.
## Sindicación de contenidos
Los sistemas de redifusión web o sindicación web permite liberar de trabajo a los usuarios al proporcionar un mecanismo de suscripción con el cual la información llega a los usuarios en vez de tener que buscarla.

Algunos de estos sistemas se basan en canales de redifusión llamados **fuente web, canal web o web feed**.

Una fuente web es un documento que contiene información básica sobre elementos de información incluyendo referencias para acceder a estos elementos.

Existen varios formatos, como pueden ser **Atom** o **RSS**.

* [RSS](RSS.md)
* [Atom](Atom.md)

## Validar Canales
Se pueden utilizar validadores para ver si realmente nuestro canal de sindicación funciona correctamente, como por ejemplo el ofrecido por la w3c:
![alt text](image.png)

[https://validator.w3.org/feed/#validate_by_input](https://validator.w3.org/feed/#validate_by_input)

## Añadir a una web
Los ficheros RSS o Atom, pueden ser añadidos a una web HTML, usando un enlace ```<a>``` como si de un fichero se tratara.
Aunque existe otra manera, y es mendiante la etiqueta ```<link>``` en la cabecera ```<head>```.
```HTML
<link href="atom.xml" type="application/atom+xml" rel="alternate" title="Sitewide Atom feed">
```
## Herramientas de lectura de sindicación
Podemos encontrar muchas aplicaciones que son capaces de leer este tipo de formato, tanto locales como en línea.
Estas aplicaciones se llaman **agregadores de contenido**:
    
1. *Agregadores de contenido locales*: NewsFox,RSSOwl.
2. *Agregadores de contenido en línea*: Feedly, The Old Reader.
3. *Agregadores de contenido como extensíon*, esos se añaden como extension o plugins del navegador

## Canales de sindicación
Algunos ejemplos de canales de sindicación que podemos descargar:
* [AEMET](https://www.aemet.es/es/rss_info/avisos/esp)
* [Marca](https://www.marca.com/rss.html)
* [DGT](https://revista.dgt.es/es/rss/)

# Almacenamiento usando lenguajes de Marcas
## Introducción a Python
* [Python](Python.md)
## Introducción a Json
* [Json](Json2.md)
## Introducción de MongoDB
* [MongoDB](mongo.md)
## Enlaces de interés 
* [Enlace a W3C](https://www.w3.org/) 
* [Enlace a W3C school](https://www.w3schools.com/)
