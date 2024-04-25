# INTRODUCCIÓN.

- CSS, o Cascading Style Sheets, es un lenguaje utilizado para describir la presentación de un documento HTML.
- Se utiliza para aplicar estilos como color, tamaño de fuente, márgenes, etc., a los elementos HTML.
- La sintáxis básica de CSS consiste en una regla de estilo que se compone de un selector y un bloque de declaración.
- El selector apunta a los elementos HTML a los que se aplicarán los estilos, mientras que el bloque de declaración contiene una o más propiedades de estilo y sus valores.
- CSS es esencial para dar estilo a los elementos HTML, permitiendo controlar su apariencia y diseño. Para un desarrollador es fundamental conocer bien CSS ya que esto le permitirá personalizar eficazmente la presentación de cualquier sitio web.

# SELECCIÓN DE ELEMENTOS HTML Y APLICACIÓN DE ESTILOS.
- Los selectores en CSS pueden apuntar a diferentes tipos de elementos HTML, como etiquetas específicas, clases, IDs o incluso elementos anidados.
- Por ejemplo, el selector `p` se aplica a todos los párrafos `<p>` en el documento, mientras que `.clase` se aplica a todos los elementos con la clase `"clase"`.
- Los estilos se aplican utilizando propiedades de CSS, como `color`, `font-size`, `background-color`, etc., seguidas por sus valores correspondientes.
- Por ejemplo, `color: blue;`, establece el color del texto en azul, `font-size: 16px;` establece el tamaño de fuente en 16 píxeles.

# PROPIEDADES BÁSICAS DE CSS COMO COLOR, FONDO, TAMAÑO DE FUENTE, ETC.
- CSS ofrece una amplia gama de propiedades para controlar la apariencia de los elementos HTML.
- Algunas propiedades básicas incluyen:
  - `color`: Define el color del texto.
  - `background-color`: Establece el color de fondo de un elemento.
  - `font-size`: Controla el tamaño de la fuente.
  - `font-family`: Especifica la fuente utilizada para el texto.
  - `margin`, `padding`: Controlan los márgenes internos y externos de un elemento, respectivamente.
- Estas propiedades se pueden aplicar utilizando valores específicos, como colores hexadecimales, nombres de color, unidades de tamaño (píxeles, em, rem, etc.).

# INTRODUCCION A RESPONSIVE.

En los primeros días del diseño web, las páginas se creaban con un tamaño de pantalla específico en mente. Sin embargo, esto generaba problemas cuando los usuarios tenían pantallas más grandes o más pequeñas que las previstas. Algunos de estos problemas incluían barras de desplazamiento no deseadas o líneas de texto extremadamente largas.

Para abordar esta limitación, surgió el concepto de diseño web responsivo `(RWD)`. El RWD permite que las páginas web se adapten dinámicamente a diferentes tamaños de pantalla, resoluciones y dispositivos. Algunos aspectos clave del RWD incluyen:

- **Media Queries**

- **Unidades Relativas** 
  
- **Flexbox y Grid**

- **Técnicas de imagen responsive**

# DISEÑO FLUIDO.
El diseño fluido en CSS se refiere a la creación de diseños web que se adaptan de manera dinámica al tamaño de la ventana del navegador o al dispositivo en el que se está visualizando el sitio. En logar de tener diseños fijos con medidas estáticas, como pixeles, el diseño fluido utiliza unidades relativas como porcentajes o unidades de vista para especificar dimensiones y márgenes.

Esto permite que el contenido se reorganice y redimensione automáticamente para adaptarse a diferentes tamaños de pantalla, lo que mejora la experiencia del usuario en dispositivos con pantallas de diferentes tamaños, como teléfonos inteligentes, tabletas y ordenadores de escritorio.

Para lograr un diseño fluido, se suelen utilizar técnicas como el uso de porcentajes en lugar de medidas absolutas para el ancho y el alto de los elementos, el uso de media queries para ajustar el diseño en diferentes puntos de interrupción y el diseño de cuadrículas flexibles que se ajusten automáticamente al tamaño de la pantalla. Esto permite que el diseño sea más adaptable y responda de manera efectiva a una amplia gama de dispositivos y tamaños de pantalla.

# DISEÑO FLUIDO VS RESPONSIVE.
Aunque comparten similitudes, diseño fluido y diseño responsive no son exactamente lo mismo, pero están estrechamente relacionados.

El diseño fluido se refiere a la técnica de diseño que utiliza unidades relativas, como porcentajes, en lugar de medidas fijas, como píxeles, para adaptar el diseño al tamaño de la ventana del navegador o dispositivo. Esto permite que los elementos del sitio se redimensionen fluidamente en proporción al tamaño de la pantalla.

Por otro lado, el diseño responsive va un paso más allá al incorporar no solo la flexibilidad en el tamaño de los elementos, sino también la reorganización del diseño y el ajuste de contenido según el tamaño y la orientación del dispositivo. Esto implica el uso de media queries en CSS para aplicar estilos específicos basados en características como el ancho de la pantalla, la orientación del dispositivo y otros factores.

El diseño fluido es una parte fundamental del diseño responsive, pero el diseño responsive también incluye la reorganización y el ajuste del contenido para adaptarse a diferentes dispositivos y tamaños de pantalla.

1. **Diseño Fluido:** Se refiere a la técnica de diseño que utiliza unidades relativas, como porcentajes, para que los elementos de un sitio web se ajusten de manera fluida al tamaño de la ventana del navegador o del contenedor que los contiene. Esto significa que los elementos se expanden o contraen en proporción al tamaño de la ventana del navegador, pero no necesariamente se reorganizan o se ajustan en función del dispositivo específico o de otras características de visualización.
2. **Diseño Responsive:** Es un enfoque más amplio que incorpora el diseño fluido y va más allá. Un diseño responsive no solo se adapta al tamaño de la ventana del navegador, sino que también responde y se ajusta activamente a diferentes dispositivos y condiciones de visualización. Esto implica el uso de media queries para aplicar estilos específicos según características como el ancho de la pantalla, la orientación del dispositivo, la resolución y otras características del dispositivo.

**recurso:** https://webdesignerwall.com/trends/inspiration-fluid-responsive-design

# UNIDADES RELATIVAS (%, em, rem):
- Las unidades relativas en CSS permiten especificar tamaños y posiciones en relación con otros elementos en la página, en lugar de valores absolutos.
- `%`: La unidad porcentual se refiere a un porcentaje del tamaño del elemento padre. Por ejemplo, `width: 50%;` hace que un elemento ocupe el 50% del ancho de su contenedor padre.
- `rem`: rem es una unidad de medida relativa que se refiere al tamaño de fuente del elemento raíz del documento HTML. La palabra rem significa “root em”, donde “em” es otra unidad de medida relativa en CSS que se basa en el tamaño de fuente del elemento en el que se utiliza. La particularidad de `rem` es que siempre se calcula en relación con el tamaño de fuente del elemento `<html>`, que es el elemento raíz.
Por ejemplo, si el tamaño de fuente del elemento raíz es de 16px (que es el valor predeterminado), entonces 1rem es igual a 16px. Si cambias el tamaño de fuente del elemento raíz a 20px, entonces 1rem sería igual a 20px.
- `em`: La unidad `"em"` se basa en el tamaño de fuente del elemento padre. Por ejemplo, si el tamaño de fuente del elemento padre es 16px y se establece `font-size: 1.5em;` en un elemento hijo, su tamaño de fuente será 24px (1.5 * 16px).

# MEDIA QUERIES.

Las media queries en CSS son una característica que permite aplicar estilos específicos basados en ciertas características del dispositivo o del medio en el que se está visualizando una página web. 

Cuando se desarrolla un sitio web, es importante que se vea bien en una variedad de dispositivos, como ordenadores de escritorio, tablets y teléfonos móviles. Las media queries son una forma de lograr esto, ya que permiten definir diferentes conjuntos de reglas de estilo que se aplicarán dependiendo de factores como el ancho de la pantalla, la orientación del dispositivo, la resolución de la pantalla, entre otros.

Por ejemplo, podrías definir una media query que cambie el tamaño del texto y el diseño de una página cuando se visualiza en un dispositivo con una pantalla más pequeña, como un teléfono móvil. Otra media query podría cambiar el diseño de una página cuando se imprime en papel en lugar de visualizarse en una pantalla.

Las media queries se definen en CSS utilizando la regla `@media`, seguida de una condición que especifica cuándo se deben aplicar los estilos definidos dentro de la media query.

## Media Queries más comúnes:

1. **Ancho de pantalla (width):**  Permite aplicar estilos basados en el ancho de la pantalla del dispositivo.
```
@media (max-width: 768px) {
  /* Estilos para pantallas pequeñas (como teléfonos móviles) */
}

@media (min-width: 768px) and (max-width: 1024px) {
  /* Estilos para pantallas medianas (como tablets) */
}

@media (min-width: 1024px) {
  /* Estilos para pantallas grandes (como ordenadores de escritorio) */
}
```
2. **Orientación (orientation):** Permite aplicar estilos dependiendo de si el dispositivo está en modo horizontal o vertical.
```
@media (orientation: portrait) {
  /* Estilos para orientación vertical */
}

@media (orientation: landscape) {
  /* Estilos para orientación horizontal */
}
```
3. **Resolución de pantalla (resolution):** Permite aplicar estilos basados en la resolución de la pantalla del dispositivo.
```
@media (min-resolution: 300dpi) {
  /* Estilos para dispositivos con una alta resolución */
}

@media (max-resolution: 72dpi) {
  /* Estilos para dispositivos con una baja resolución */
}
```

Estos son algunos ejemplos de media queries comunes, pero hay muchas más opciones disponibles para adaptar el diseño de una página web a una amplia variedad de dispositivos y condiciones de visualización.

## Breakpoints

Los breakpoints en CSS responsive son puntos específicos en el ancho de la ventana del navegador donde cambia el diseño de tu sitio web para adaptarse a diferentes tamaños de pantalla. Estos puntos de quiebre se definen utilizando media queries y se utilizan para ajustar el diseño, la disposición y los estilos de tu sitio web en función del dispositivo en el que se está visualizando.

Se suelen definir breakpoints que coincidan con los tamaños de pantalla comunes de varios dispositivos, como teléfonos móviles, tablets y ordenadores de escritorio. Al definir estos puntos de quiebre, puedes crear diseños que se adapten de manera fluida y se vean bien en una variedad de dispositivos y tamaños de pantalla.

1. **Pequeño (Small):** Por ejemplo, para dispositivos móviles con un ancho de pantalla menor a 768 píxeles.
2. **Mediano (Medium):** Por ejemplo, para tablets con un ancho de pantalla entre 768 y 1024 píxeles.
3. **Grande (Large):** Por ejemplo, para ordenadores de escritorio con un ancho de pantalla mayor a 1024 píxeles.

# MEDIA TYPES.

Los Media Types son una forma de especificar los diferentes tipos de medios de salida para los cuales se aplicarán estilos CSS. Esto significa que puedes definir estilos específicos que se aplicarán cuando tu página web se visualice en diferentes medios, como en una pantalla de ordenador, en una impresora o en un dispositivo de lectura de pantalla.

## Media Types más comunes:

1. **screen:** Este Media Type se utiliza para aplicar estilos cuando la página se muestra en una pantalla, como la pantalla de un ordenador, una tablet o un teléfono móvil. Es el Media Type predeterminado si no se especifica ninguno.
```
@media screen {
  /* Estilos específicos para la pantalla */
}
```
2. **print:** Este Media Type se utiliza para aplicar estilos cuando la página se imprime en papel o en otro medio similar. Los estilos definidos aquí pueden optimizar la apariencia de la página para la impresión, como ocultar elementos no esenciales, ajustar márgenes, cambiar colores, etc.
```
@media print {
  /* Estilos específicos para la impresión */
}
```
3. **speech:** Este Media Type se utiliza para aplicar estilos cuando la página se lee en voz alta, como por ejemplo por un lector de pantalla para personas con discapacidad visual. Los estilos definidos aquí pueden ayudar a mejorar la legibilidad y la comprensión del contenido cuando se lee en voz alta.
```
@media speech {
  /* Estilos específicos para la lectura en voz alta */
}
```

# FLEXBOX Y GRID LAYOUT.

Tanto Flexbox como Grid Layout son herramientas poderosas en CSS que facilitan la creación de diseños responsivos en páginas web.

1. **Flexbox:** Flexbox es un modelo de diseño unidimensional que se utiliza para distribuir elementos en un contenedor a lo largo de un eje (ya sea horizontal o vertical) y alinearlos de manera flexible. Es especialmente útil para diseñar componentes individuales dentro de un diseño, como barras de navegación, listas de elementos o disposiciones de artículos en una galería.
Para diseñar responsivamente con Flexbox, puedes ajustar fácilmente la dirección del flujo de los elementos y sus propiedades de alineación según el tamaño de la pantalla. Por ejemplo, puedes reorganizar los elementos de una fila a una columna en pantallas más pequeñas utilizando la propiedad flex-direction. Además, puedes controlar cómo los elementos se expanden y contraen con la propiedad flex-grow y flex-shrink, lo que te permite adaptar el diseño a diferentes tamaños de pantalla.
2. **Grid Layout:** Grid Layout es un sistema de diseño bidimensional que permite crear diseños de manera más estructurada y compleja, dividiendo el espacio de la página en filas y columnas. Con Grid Layout, puedes colocar elementos en cualquier celda de la cuadrícula, lo que brinda un mayor control sobre la disposición y el diseño de la página.
Al diseñar responsivamente con Grid Layout, puedes especificar cómo cambia la disposición de las filas y columnas en diferentes puntos de interrupción utilizando media queries. Por ejemplo, puedes definir un diseño de cuadrícula de tres columnas para pantallas grandes y cambiar a una sola columna para pantallas más pequeñas. Además, puedes utilizar la función minmax() para especificar rangos de tamaño flexible para las filas y columnas, lo que permite que se ajusten dinámicamente según el espacio disponible en la pantalla.

Tanto Flexbox como Grid Layout son herramientas esenciales para diseñar páginas web responsivas. Flexbox es ideal para diseños unidimensionales y componentes individuales, mientras que Grid Layout es más adecuado para diseños complejos y estructurados. Al combinar estas dos técnicas con media queries, puedes crear diseños que se adapten perfectamente a una amplia gama de dispositivos y tamaños de pantalla.

# TÉCNICAS DE IMAGEN RESPONSIVE.

Las técnicas de imagen responsive son métodos para asegurar que las imágenes en un sitio web se ajusten y se vean bien en una variedad de dispositivos y tamaños de pantalla.

Aquí algunas técnicas comunes de imagen responsive:
1. **Imágenes flexibles con CSS:** Esta técnica implica definir el ancho de las imágenes en porcentajes en lugar de valores fijos en píxeles. Por ejemplo:
```
img {
  max-width: 100%; /* La imagen se ajustará al ancho del contenedor */
  height: auto; /* La altura se ajustará automáticamente para mantener la proporción */
}
```
2. **Elemento <picture> con fuentes múltiples:** La etiqueta `<picture>` permite proporcionar diferentes versiones de una imagen para diferentes tamaños de pantalla. Esto se combina con la etiqueta `<source>` para definir las diferentes fuentes de la imagen y la etiqueta `<img>` como un respaldo. Por ejemplo:
```
<picture>
  <source srcset="imagen-grande.jpg" media="(min-width: 768px)">
  <source srcset="imagen-pequeña.jpg">
  <img src="imagen-pequeña.jpg" alt="Descripción de la imagen">
</picture>
```
En este ejemplo, se carga "imagen-grande.jpg" para dispositivos con una pantalla más grande que 768 píxeles de ancho, y "imagen-pequeña.jpg" para otros dispositivos.

3. **Imágenes SVG (Scalable Vector Graphics):** Los gráficos vectoriales escalables son imágenes basadas en vectores que se escalan fácilmente a diferentes tamaños sin perder calidad. Son ideales para iconos, logotipos y otros gráficos simples.
4. **Lazy loading:** Esta técnica retrasa la carga de imágenes que no están en la vista del usuario hasta que el usuario se desplaza hacia ellas. Esto mejora los tiempos de carga de la página inicial y reduce la carga en dispositivos móviles.
5. **Resolución de imagen adaptable (Responsive Image Resolution):** Esto implica proporcionar diferentes versiones de una imagen con diferentes resoluciones (por ejemplo, 1x, 2x, 3x) y utilizar media queries para seleccionar la versión adecuada según la resolución de la pantalla del dispositivo.

# MOBILE FIRST.

El enfoque de diseño "mobile first" es una estrategia que se centra en diseñar y desarrollar primero la versión móvil de un sitio web o aplicación antes de considerar las versiones para dispositivos más grandes, como tablets o ordenadores de escritorio. En lugar de comenzar con un diseño para pantallas grandes y luego adaptarlo para dispositivos móviles más pequeños, el enfoque mobile first invierte este proceso, lo que tiene varios beneficios:

1. **Prioriza la experiencia móvil:** Dado que el tráfico web proveniente de dispositivos móviles ha aumentado significativamente en los últimos años, es fundamental asegurarse de que la experiencia en dispositivos móviles sea óptima. Comenzar con el diseño móvil primero garantiza que la versión más importante y ampliamente utilizada del sitio web tenga la mejor experiencia posible.
2. **Fomenta la simplicidad y la claridad:** Los dispositivos móviles tienen pantallas más pequeñas y capacidades de procesamiento limitadas en comparación con los pc de escritorio. Por lo tanto, diseñar primero para dispositivos móviles tiende a fomentar un enfoque más simplificado y centrado en el contenido, lo que puede conducir a una mejor usabilidad y legibilidad en todas las versiones del sitio.
3. **Promueve la escalabilidad y la adaptabilidad:** Al comenzar con un diseño móvil simple y escalable, es más fácil adaptar y expandir el diseño a dispositivos más grandes. Esto significa que puedes agregar funcionalidades adicionales o elementos de diseño más complejos de manera progresiva, sin sacrificar la usabilidad en dispositivos móviles.
4. **Optimiza el rendimiento:** Los sitios web móviles generalmente requieren tiempos de carga más rápidos y un uso eficiente de los recursos para garantizar una experiencia fluida para el usuario. Al diseñar primero para dispositivos móviles, se fomenta la optimización del rendimiento desde el principio, lo que puede resultar en un sitio web más rápido y eficiente en general.

Para implementar el enfoque mobile first, puedes utilizar media queries en tu hoja de estilos CSS para agregar estilos adicionales que se apliquen a dispositivos más grandes a medida que avanzas en el proceso de diseño. Esto garantiza que el diseño se adapte de manera efectiva a una variedad de tamaños de pantalla y dispositivos.