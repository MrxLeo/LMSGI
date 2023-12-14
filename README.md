# Actividad Cuaderno Clase UD1:
## ¿Qué es un lenguaje de marcas?
* **Un lenguaje de marcas, es un conjunto de etiquetas de marcas, utilizadas para definir la estructura, y el diseño de un documento. Es decir, que las etiquetas de marcas, proporcionan información semántica, sobre los contenidos, en lugar de especificar su presentación o diseño. Por lo tanto, es un sistema de anotación de un documento, que se distingue sintácticamente del contenido del texto. Los lenguajes de marcas, permiten etiquetar los elementos del documento, para identificar elementos especiales como títulos, párrafos, listas, énfasis, etc. Las etiquetas proporcionan información semántica sobre la estructura y el significado del documento.**
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