# Ejercicios Teóricos para Programación II - Tecnologías WEB

## 1. ¿Qué es Internet y cuál es su importancia en la infraestructura de la Web?

Internet es una red global de computadoras interconectadas que permite compartir información y recursos a nivel mundial. Su importancia en la infraestructura de la Web radica en que proporciona la base sobre la cual se construye y opera la Web, permitiendo la comunicación y el acceso a sitios web y servicios.

**Historia breve:**

- **ARPANET** fue la primera red de computadoras, creada en 1969 por el Departamento de Defensa de EE. UU. para conectar centros de investigación.
- Introdujo tecnologías clave como el conmutado de paquetes y el protocolo TCP/IP, que permitieron la interconexión de diferentes redes.
- En 1983, ARPANET adoptó TCP/IP, sentando las bases para Internet.
- ARPANET fue desmantelada en 1990.

## 2. Protocolos de Comunicación

**Explica la función del protocolo TCP/IP en Internet.**

TCP/IP es el conjunto de protocolos que permite la transmisión de datos en Internet. **IP** se encarga de direccionar y enrutar los datos a su destino correcto, mientras que **TCP** asegura que los datos se envíen de manera fiable y en el orden adecuado. Juntos, garantizan una comunicación eficiente y segura en la red.

**¿Qué es una dirección IP y cuál es la diferencia entre una IP pública y una privada?**

Una dirección IP es un número que identifica de forma única a un dispositivo en una red.

- **IP Pública**: Es única en Internet y permite que un dispositivo sea accesible desde cualquier lugar en la red global.
- **IP Privada**: Se utiliza dentro de una red local y no es accesible desde fuera de esa red. Varias redes locales pueden usar la misma IP privada sin conflictos.

## 3. Infraestructura de Internet

**¿Qué elementos componen la infraestructura de comunicación de Internet?**

La infraestructura de Internet incluye:

- **Servidores**: Almacenan y gestionan datos.
- **Enrutadores y Switches**: Dirigen y gestionan el tráfico de datos.
- **Cables y Fibra Óptica**: Transportan datos físicamente.
- **Centros de Datos**: Alojan servidores y equipos de red.
- **ISP (Proveedores de Internet)**: Conectan usuarios a Internet.
- **IXP (Puntos de Intercambio)**: Facilitan el intercambio de tráfico entre redes.
- **Satélites y Redes Inalámbricas**: Soportan la conectividad en áreas remotas y móviles.

**Menciona y explica brevemente el rol de los satélites, antenas y cables submarinos en Internet.**

- **Satélites**: Proporcionan conectividad en áreas remotas y rurales donde no llegan redes terrestres.
- **Antenas**: Facilitan la transmisión inalámbrica de datos, conectando dispositivos a redes móviles y Wi-Fi.
- **Cables submarinos**: Transportan grandes volúmenes de datos a través de océanos para conectar continentes, siendo cruciales para la infraestructura global de Internet.

## 4. Conceptos Básicos de la Web

**Define y explica la importancia de los siguientes términos: HTML, URL, y HTTP/HTTPS.**

- **HTML**: Lenguaje de marcado utilizado para crear y estructurar páginas web.
- **URL**: Dirección que localiza recursos en la web.
- **HTTP/HTTPS**: Protocolos para transferir datos; **HTTPS** cifra la información para mayor seguridad.

**¿Cuál es la relación entre Internet y la Web?**

Internet es la infraestructura global de redes que conecta dispositivos, mientras que la Web (World Wide Web) es un servicio que utiliza Internet para acceder a páginas y recursos mediante navegadores. La Web es una parte esencial de Internet.

## Etiquetas en HTML

### Definición
Las etiquetas en HTML estructuran y formatean el contenido de una página web. La estructura básica es `<nombre-etiqueta>Contenido</nombre-etiqueta>`. Algunas etiquetas son auto-cerrables, como `<img src="imagen.jpg" alt="Descripción">`.



## UNIDAD 2. HTML5

**¿Qué es HTML y cuál es su propósito principal en la Web??**
El Lenguaje de Marcado de Hipertexto (HTML) es el código que se utiliza para estructurar y desplegar una página web y sus contenidos. Por ejemplo, sus contenidos podrían ser párrafos, una lista con viñetas, o imágenes y tablas de datos.

Es un lenguaje de marcado que define la estructura de tu contenido. HTML consiste en una serie de elementos que usarás para encerrar diferentes partes del contenido para que se vean o comporten de una determinada manera. Las etiquetas de encierre pueden hacer de una palabra o una imagen un hipervínculo a otro sitio, se pueden cambiar palabras a cursiva, agrandar o achicar la letra, etc.  También facilita la navegación y la integración con estilos (CSS) y scripts (JavaScript) para mejorar la presentación y funcionalidad de las páginas web.

**Estructura basica de HTML5**

```html
<!DOCTYPE html>     
<html lang="es">
    <head>
        <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a mi página web</h1>
    </header>
    <main>
        <p>Este es el contenido principal de la página.</p>
    </main>
    <footer>
        <p>© 2024 Mi Página Web</p>
    </footer>
</body>
</html>


`<!DOCTYPE html>: Define que el documento es HTML5.`
`<html>: Raíz del documento; lang="es" establece el idioma.`
    `<head>: Contiene metadatos, el título (<title>), y enlaces a CSS.`
        `<body>: Incluye todo el contenido visible como encabezados, texto y pie de página.`
```

**Etiquetas HTML:**

Las "tags" HTML, o "etiquetas" HTML, son códigos utilizados para "marcar" el texto de una página web, con el fin de dar instrucciones al navegador sobre cómo mostrarlo. Puedes utilizar etiquetas HTML para aplicar cursivas, crear saltos de línea, insertar objetos multimedia, crear listas con viñetas o para definir diferentes tipos de contenido en una página web, como encabezados, párrafos, imágenes, enlaces, formularios y mucho más.

En resumen, las etiquetas HTML son esenciales para diseñar y organizar el contenido de una página web de manera efectiva y clara.

## Etiquetas HTML Comunes

1. **`<h1>` a `<h6>`**
   - **Descripción**: Encabezados, de `<h1>` (más importante) a `<h6>` (menos importante).

2. **`<p>`**
   - **Descripción**: Define un párrafo de texto.

3. **`<a>`**
   - **Descripción**: Crea un enlace a otra página o recurso. Usa `href` para especificar la URL.

4. **`<img>`**
   - **Descripción**: Inserta una imagen. Usa `src` para la ruta de la imagen y `alt` para una descripción alternativa.

5. **`<ul>` y `<li>`**
   - **Descripción**: `<ul>` crea una lista no ordenada (con viñetas), y `<li>` define un elemento de la lista.

Estas etiquetas son esenciales para crear y estructurar contenido en una página web.


## Atributos HTML

**¿Qué son?**
Los atributos en HTML proporcionan información adicional sobre un elemento y se escriben en la etiqueta de apertura en el formato `nombre="valor"`.

**Ejemplo de etiqueta con atributos:**

```html
<a href="https://www.ejemplo.com" target="_blank" title="Ir a Ejemplo">Visita nuestro sitio web</a>

```
La etiqueta <a> en HTML, también conocida como "anchor" o "enlace", se utiliza para crear hipervínculos que permiten a los usuarios navegar a otras páginas web, recursos o ubicaciones dentro de la misma página.

## UNIDAD 3. CSS

**Definición y Uso de CSS:**
CSS (Cascading Style Sheets) es un lenguaje que se utiliza para definir el diseño y la presentación de las páginas web. Su función principal es separar el contenido (HTML) del estilo visual. Darle una nueva cara visual a las paginas con diseños extravagantes o el que uno quiera o le guste

CSS permite personalizar la apariencia de una página HTML modificando colores, fuentes, tamaños, espaciado, diseño, bordes, sombras y añadiendo efectos de transición y animación. Esto facilita la creación de diseños visualmente atractivos y funcionales.

**Selectores y Propiedades CSS:**

**¿Qué es un selector en CSS y cuáles son los tipos más comunes?**

Un selector CSS es la primera parte de una regla CSS. Es un patrón de elementos y otros términos que indican al navegador qué elementos HTML se seleccionan para aplicarles una regla que incluye los valores de las propiedades CSS

En CSS, los selectores se definen en la especificación de selectores de CSS correspondiente; al igual que cualquier otro elemento de CSS, es necesario que los navegadores los admitan para que funcionen. La mayoría de los selectores que encontrarás se definen en especificación de nivel 3 de selectores, que es una especificación consolidada y, por lo tanto, la mayoría de navegadores admitirán esos selectores.

Un selector de tipo también recibe el nombre de selector de nombre de etiqueta o selector de elemento porque selecciona un elemento/etiqueta HTML del documento. En el ejemplo siguiente hemos utilizado los selectores span, em y strong. Se aplica estilo a todas las instancias de los elementos <span>, <em> y <strong>.

**5 tipos de propiedades CSS**

Color, define el color del texto en un elemento.
background-image, agrega una imagen de fondo 
font-size , define el tamaño de la letra
border, define el borde de un elemento, incluyendo su ancho, estilo y color.
margin, controla el espacio exterior alrededor de un elemento. Puede ser especificado en valores individuales para cada lado (arriba, derecha, abajo, izquierda).

**Diseño Responsivo:**

El diseño responsive es un formato de programación que permite ajustar un sitio web automáticamente al tamaño y disposición de los dispositivos de sus usuarios. Los sitios web responsive cambian para ofrecer la mejor experiencia a los visitantes desde sus teléfonos inteligentes, tabletas o computadoras de escritorio.