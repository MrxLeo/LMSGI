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
## Tabla de contenidos/Índice:
1.- [HTML (Hypertext Markup Language), y su evolución.](#html-)
2.- [XHTML, diferencias, ventajas, y desvantajas, con respecto a HTML.](#xhtml)
3.- [Estructura de un documento HTML.](#estructura-de-un-documento-html)
  ## Estructura de un documento HTML:
* **HTML**