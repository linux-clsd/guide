# HTML  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/2048px-HTML5_logo_and_wordmark.svg.png" alt="Texto alternativo" style="width:30px;height:30px;">

- [Introducción](#introducción)
- [Antes de empezar](#antes-de-empezar)
- [Sintaxis](#sintaxis)  
  - [Doctype](#doctype)
  - [html](#html)
  - [head](#head)
  - [body](#body)

## Introducción
Desde su creación en la década de 1990, el lenguaje de marcado de hipertexto, HTML, ha sido el pilar fundamental de la World Wide Web (WWW) y ha revolucionado la forma en que interactuamos y compartimos información en línea.

HTML fue concebido por Tim Berners-Lee, un científico de la computación británico, quien en 1989 propuso un sistema para compartir y acceder a documentos en hipertexto a través de una red de computadoras. Berners-Lee, junto con su equipo en el CERN (Organización Europea para la Investigación Nuclear), desarrolló los fundamentos del HTML como parte de su visión para una "web" global.

El HTML original fue un lenguaje simple que permitía a los usuarios enlazar documentos a través de hipervínculos y agregar ciertos elementos de formato básico. Sin embargo, a medida que la web creció en popularidad, también lo hizo la necesidad de una mayor funcionalidad y diseño visual.

Con el tiempo, HTML evolucionó y se actualizaron sus estándares para adaptarse a las demandas cambiantes de la web moderna. La introducción de nuevas versiones, como HTML4 en 1997 y HTML5 en 2014, permitió a los desarrolladores web crear sitios más dinámicos e interactivos al agregar características como video, audio, animaciones y formularios avanzados.

HTML, combinado con las hojas de estilo en cascada (CSS) y JavaScript, ha sentado las bases para la creación de sitios web atractivos y receptivos que brindan una experiencia rica y fluida a los usuarios.

En la actualidad, HTML continúa siendo un lenguaje esencial para cualquier desarrollador web. Desde pequeños blogs personales hasta aplicaciones web complejas, HTML sigue siendo la base sobre la cual se construye la arquitectura de la web.

En este manual, te embarcarás en un emocionante viaje para aprender los conceptos fundamentales de HTML y descubrirás cómo crear y dar forma a tus propias páginas web. Prepárate para adquirir habilidades que te permitirán dar vida a tus ideas en el mundo digital y ser parte del emocionante futuro de la web.

¡Comencemos a explorar el poder de HTML y a construir juntos la web del mañana!

# Antes de empezar
¡Bienvenido a esta guía de HTML! Aquí encontrarás todo lo que necesitas saber para comenzar a construir tus propias páginas web utilizando este lenguaje de marcado fundamental.

Antes de sumergirte en el mundo de HTML, es importante comprender algunos conceptos básicos y establecer una base sólida. Aquí tienes algunos puntos clave que debes tener en cuenta antes de comenzar tu aventura en la creación de páginas web:

1. Entorno de desarrollo: Asegúrate de tener un entorno de desarrollo adecuado para trabajar con HTML. Necesitarás un editor de texto simple como Notepad++ o Visual Studio Code, junto con un navegador web actualizado como Google Chrome, Mozilla Firefox o Microsoft Edge.
2. Todo el código escrito en HTML tiene que tener una etiqueta de entrada y una de cerrar como se muestra en la siguiente imagen:

![img](https://kinsta.com/wp-content/uploads/2022/06/Untitled-2.png)

<strong>Recuerda que la práctica constante es la clave para convertirse en un desarrollador web hábil.</strong> A medida que avances en esta guía, te encontrarás con ejemplos prácticos y desafíos que te ayudarán a fortalecer tus habilidades en HTML.

## Sintaxis
### Doctype
```
<!DOCTYPE html>
```
El DOCTYPE (Declaración de Tipo de Documento) es una declaración especial que se coloca al comienzo de un documento HTML para indicarle al navegador qué versión de HTML se está utilizando en el documento y cómo debe interpretarlo. Esencialmente, el DOCTYPE define el conjunto de reglas y estándares que el navegador debe seguir al renderizar la página.

En HTML5, el DOCTYPE estándar es <!DOCTYPE html>. Esta declaración le dice al navegador que interprete el documento como HTML5 y aplique las reglas de sintaxis y estructura correspondientes a esta versión del lenguaje.

Es importante incluir el DOCTYPE correcto al comienzo de un documento HTML, ya que ayuda a los navegadores a interpretar y renderizar correctamente la página. También asegura la compatibilidad con estándares web y evita problemas de visualización o interpretación del contenido.

### html
```
<html></html>
```
El elemento html es la envoltura principal de un documento HTML. Es el contenedor principal que contiene todo el contenido visible en el navegador. Todos los demás elementos y etiquetas HTML deben estar contenidos dentro de este elemento.

Aquí tienes un ejemplo básico de cómo se usa el elemento html en un documento HTML:
```
<!DOCTYPE html>
<html>
   <!-- Contenido de la web -->
</html>
```

### head
```
<head></head>
```
El elemento de encabezado head es una sección del documento HTML que se utiliza para incluir metadatos, enlaces a hojas de estilo CSS, enlaces a archivos JavaScript y otras configuraciones relacionadas con el documento. Aunque el contenido dentro del elemento head no se muestra directamente en el navegador, desempeña un papel importante en la configuración y presentación de la página web.

Aquí hay algunos elementos comunes que se pueden incluir dentro del elemento head:

title: Define el título de la página que se muestra en la pestaña o barra de título del navegador.

meta: Se utiliza para especificar metadatos sobre el documento, como la codificación de caracteres, descripción, palabras clave, autor, entre otros.

link: Se utiliza para enlazar el documento HTML con una hoja de estilo CSS externa. También se puede usar para enlazar a otros recursos, como fuentes tipográficas o iconos.

style: Permite incluir estilos CSS directamente en el documento HTML, en lugar de usar una hoja de estilo externa.

script: Se utiliza para enlazar el documento con archivos JavaScript externos o para incluir scripts directamente en el documento.

Otros elementos y etiquetas relacionados con la configuración del documento, como base, meta http-equiv, meta name, etc.

Aquí tienes un ejemplo básico de cómo se utiliza el elemento head en un documento HTML:
```
<!DOCTYPE html>
<html>
   <head>
   <!-- Metadatos, estilos, scripts y más -->
   </head>
</html>
```

### body
```
<body></body>
```
El elemento body es una de las secciones principales de un documento HTML y se utiliza para contener el contenido visible que se muestra en el navegador. Todo el contenido como texto, imágenes, enlaces, tablas, formularios y otros elementos HTML que se deseen mostrar en la página web debe estar contenido dentro del elemento body.

Aquí tienes un ejemplo básico de cómo se utiliza el elemento body en un documento HTML:
```
<!DOCTYPE html>
<html>
   <head>
      <!-- Metadatos, estilos, scripts y más -->
   </head>
   <body>
      <!-- Contenido visible en el navegador -->
      <h1>Este es un título de página</h1>
      <p>Este es un párrafo.</p>
      <!-- Otros elementos y etiquetas HTML -->
   </body>
</html>
```
Dentro del elemento body, se pueden incluir y anidar diferentes elementos y etiquetas HTML para estructurar y formatear el contenido de la página. Algunos ejemplos comunes de elementos que se pueden usar dentro del body son:

Encabezados: "h1, h2, h3", etc., se utilizan para mostrar títulos y subtítulos.

Párrafos: "p", se utiliza para mostrar texto en párrafos.

Listas: "ul, ol, li", se utilizan para crear listas desordenadas y ordenadas.

Imágenes: "img", se utiliza para mostrar imágenes en la página.

Enlaces: "a", se utiliza para crear enlaces a otras páginas web o recursos.

Tablas: "table, tr, td", se utilizan para mostrar datos en una estructura de tabla.

Formularios: "form, input, select, textarea", se utilizan para crear formularios interactivos.

Elementos de diseño: "div, span", se utilizan para agrupar y dar estilo a secciones específicas del contenido.

Estos son solo algunos ejemplos de elementos que se pueden utilizar dentro del body. La combinación y la estructura de estos elementos dependen de los requisitos y la estructura de la página web específica que se está desarrollando.
