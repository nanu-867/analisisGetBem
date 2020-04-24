# Análisis de accesibilidad de la web getBem

El análisis se realizó con la herramienta **wave**

## Errores

 1. Falta el atributo **lang** de la etiqueta **html** que define el idioma.
> Solución: definir el idioma con dicho atributo

 2. Falta texto alternativo (atributo **alt** dentro de la etiqueta **img**) en 15 imágenes.
 > Solución: Escribir el atributo alt con una descripción acorde a cada imagen
 

## Alertas

 1. Faltan etiquetas semánticas que definan las áreas. 
> Solución: cambiar divs por etiquetas semánticas (header, nav, section, article...)

 2. Falta la etiqueta **h1**
 > Solución: el encabezado de la página, su títlo, escribirlo dentro de h1

 3. Links redundantes, es decir links cercanos que dirigen a la misma página.
> Solución: de ser posible combinar los links en uno solo y quitar el resto. Lo mismo para el texto o texto alternativo.

Número de ocurrencias: 3


## Trampas

1. Texto alternativo no descriptivo
 > Solución: al utilizar el atributo alt, escribir un texto acorde al contenido de la imagen, sea su descripción o función para que un lector de pantalla pueda leerlo correctamente, u otras situaciones en las que los usuarios no podrían ver la imagen.

Número de ocurrencias: 1# analisisGetBem
