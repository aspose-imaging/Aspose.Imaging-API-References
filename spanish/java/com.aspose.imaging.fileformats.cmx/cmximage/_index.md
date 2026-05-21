---
title: "CmxImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para Corel Metafile Exchange CMX, formato de imagen vectorial con soporte de descripciones de metadatos, es una solución integral para desarrolladores que trabajan con archivos CMX."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

La API para Corel Metafile Exchange (CMX), formato de imagen vectorial con soporte de descripciones de metadatos, es una solución integral para desarrolladores que trabajan con archivos CMX. Esta API permite la carga fluida de imágenes CMX, la extracción de metadatos como bits por píxel, dimensiones de los objetos y más. Con funcionalidades adicionales como redimensionado, rotación, configuración de paletas y conversión a otros formatos, esta API capacita a los desarrolladores para manipular y personalizar eficientemente imágenes vectoriales CMX y satisfacer los requisitos específicos de sus aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Comience a trabajar con la clase [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) de forma fluida inicializando una nueva instancia con los parámetros streamContainer y loadOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere el formato de archivo de la imagen sin esfuerzo con esta propiedad fácil de usar. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupere la profundidad de bits de la imagen sin esfuerzo con esta propiedad fácil de usar. |
| [getDefaultPage()](#getDefaultPage--) | Recupere la página predeterminada de la imagen sin esfuerzo con esta propiedad intuitiva. |
| [isCached()](#isCached--) | Determine si los datos del objeto están actualmente en caché, eliminando la necesidad de leer los datos. |
| [getWidthF()](#getWidthF--) | Recupere el ancho del objeto en pulgadas con esta propiedad intuitiva. |
| [getHeightF()](#getHeightF--) | Obtenga sin esfuerzo la altura del objeto, medida en pulgadas, con esta propiedad fácil de usar. |
| [getDocument()](#getDocument--) | Recupere el documento CMX sin esfuerzo con esta propiedad intuitiva. |
| [getCmxPage()](#getCmxPage--) | Recupere sin esfuerzo la página CMX de la imagen con esta propiedad intuitiva. |
| [getPageCount()](#getPageCount--) | Recupere el recuento total de páginas de la imagen con esta propiedad intuitiva. |
| [getPages()](#getPages--) | Recupere las páginas de la imagen de forma fluida con esta propiedad intuitiva. |
| [cacheData()](#cacheData--) | Almacene en caché los datos para evitar cargas adicionales desde la fuente subyacente [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) con este método conveniente. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalice la paleta de colores de la imagen con este método intuitivo. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Cargar una imagen desde un archivo CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Comience a trabajar con la clase [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) de forma fluida inicializando una nueva instancia con los parámetros streamContainer y loadOptions. Ideal para desarrolladores que buscan una forma conveniente de cargar imágenes CMX desde diversas fuentes de datos mientras personalizan el proceso de carga según sea necesario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | El contenedor del flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere el formato de archivo de la imagen sin esfuerzo con esta propiedad fácil de usar. Ideal para desarrolladores que buscan determinar dinámicamente el formato de sus imágenes, garantizando compatibilidad y un procesamiento preciso en sus aplicaciones.

**Returns:**
long - El formato de archivo [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupere la profundidad de bits de la imagen sin esfuerzo con esta propiedad fácil de usar. Ideal para desarrolladores que buscan determinar el nivel de detalle o la profundidad de color presente en sus imágenes, garantizando un procesamiento y manipulación precisos.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Recupere sin esfuerzo la página predeterminada de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido a la página principal de su imagen, garantizando una navegación y gestión eficientes.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Determine si los datos del objeto están actualmente en caché, eliminando la necesidad de leer los datos. Ideal para desarrolladores que buscan optimizar el rendimiento aprovechando los datos en caché de manera eficiente, garantizando un acceso más rápido a la información del objeto.

**Returns:**
boolean - `true` si los datos del objeto están en caché; de lo contrario, `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Recupere el ancho del objeto en pulgadas con esta propiedad intuitiva. Ideal para desarrolladores que buscan mediciones precisas de los objetos en sus aplicaciones, garantizando un diseño y presentación exactos.

**Returns:**
float - El ancho del objeto, en pulgadas.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Obtenga sin esfuerzo la altura del objeto, medida en pulgadas, con esta propiedad fácil de usar. Ideal para desarrolladores que buscan información dimensional precisa para un diseño y presentación efectivos en sus aplicaciones.

**Returns:**
float - La altura del objeto, en pulgadas.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Recupere el documento CMX sin esfuerzo con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceder o modificar imágenes CMX, garantizando flexibilidad y eficiencia en sus aplicaciones.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Recupere sin esfuerzo la página CMX de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceso rápido a páginas individuales dentro de imágenes CMX, garantizando una navegación y gestión eficientes.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupere el recuento total de páginas de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan gestionar imágenes multipágina de forma dinámica, garantizando una navegación y manipulación eficientes del contenido de la imagen.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupere las páginas de la imagen sin problemas con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceder y manipular páginas individuales dentro de imágenes multipágina, garantizando una navegación y procesamiento eficientes.

**Returns:**
com.aspose.imaging.Image[] - las páginas.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen desde un archivo CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacene en caché los datos para evitar cargas adicionales desde la fuente subyacente [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) con este método conveniente. Ideal para desarrolladores que buscan optimizar el rendimiento mediante la precarga de datos, garantizando un acceso más rápido y una operación más fluida en sus aplicaciones.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen desde un archivo CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personalice la paleta de colores de la imagen con este método intuitivo. Ideal para desarrolladores que buscan aplicar esquemas de color o ajustes específicos de forma dinámica, garantizando un control preciso sobre la apariencia visual de sus imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

