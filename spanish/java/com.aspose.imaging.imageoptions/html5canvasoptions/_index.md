---
title: "Html5CanvasOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Cree archivos HTML5 Canvas sin esfuerzo con nuestra API que le permite combinar sin problemas elementos como formularios, texto, imágenes, animaciones y enlaces."
type: docs
weight: 23
url: /es/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Cree archivos HTML5 Canvas sin esfuerzo con nuestra API, que le permite combinar sin problemas elementos como formularios, texto, imágenes, animaciones y enlaces. Benefíciese de funciones robustas, incluido el soporte de identificador de etiqueta y configuraciones de codificación, garantizando un rendimiento óptimo y personalización para sus proyectos web.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Inicializa una nueva instancia de la clase [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Inicializa una nueva instancia de la clase `ImageOptionsBase`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Obtiene el identificador de etiqueta del canvas. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Establece el identificador de etiqueta del canvas. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Obtiene un valor que indica si se debe generar la página HTML completa. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Establece un valor que indica si se debe generar la página HTML completa. |
| [getEncoding()](#getEncoding--) | Obtiene la codificación. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Establece la codificación. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Cualquier imagen vectorial (SVG, WMF, CMX, etc.) puede usarse como fuente para sus imágenes Canvas. El siguiente código crea una imagen Canvas simple.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
Puede incrustar más de una imagen Canvas dentro de una página HTML o actualizar una página ya existente. Para ello, necesita exportar solo la etiqueta Canvas.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


Inicializa una nueva instancia de la clase [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Inicializa una nueva instancia de la clase `ImageOptionsBase`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Las opciones de imagen. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Obtiene el identificador de etiqueta del canvas.

**Returns:**
java.lang.String - el identificador de la etiqueta canvas.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Establece el identificador de etiqueta del canvas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | el identificador de la etiqueta canvas. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Obtiene un valor que indica si se debe generar la página HTML completa.

**Returns:**
boolean - un valor que indica si se debe generar la página HTML completa.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Establece un valor que indica si se debe generar la página HTML completa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si se debe generar la página HTML completa. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Puede incrustar más de una imagen Canvas dentro de una página HTML o actualizar una página ya existente. Para ello, necesita exportar solo la etiqueta Canvas.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Obtiene la codificación.

**Returns:**
java.nio.charset.Charset - la codificación.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Establece la codificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset | la codificación. |

