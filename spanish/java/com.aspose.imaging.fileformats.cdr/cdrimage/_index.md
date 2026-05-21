---
title: "CdrImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para el soporte del formato de imagen vectorial CorelDRAW CDR es una herramienta esencial para los desarrolladores que trabajan con gráficos vectoriales."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

La API para el soporte del formato de imagen vectorial CorelDRAW CDR es una herramienta esencial para los desarrolladores que trabajan con gráficos vectoriales. Esta API permite el procesamiento sin problemas de archivos CDR, permitiendo el almacenamiento y la manipulación de diversos elementos como texto, líneas, formas, imágenes, colores y efectos. Con sus capacidades integrales, los desarrolladores pueden trabajar de manera eficiente con representaciones vectoriales del contenido de imágenes, garantizando precisión y flexibilidad al crear y editar gráficos vectoriales CorelDRAW de forma programática.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Comience a trabajar con la clase [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sin esfuerzo inicializando una nueva instancia con los parámetros stream y loadOptions. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Comience a trabajar con la clase [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sin esfuerzo inicializando una nueva instancia con los parámetros stream y loadOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Recupere la página predeterminada de la imagen con facilidad usando esta propiedad fácil de usar. |
| [isCached()](#isCached--) | Determine sin esfuerzo si los datos del objeto están actualmente en caché, eliminando la necesidad de leer los datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupere la profundidad de bits de la imagen sin esfuerzo con esta propiedad fácil de usar. |
| [getPageCount()](#getPageCount--) | Recupere o actualice sin esfuerzo el recuento total de páginas de la imagen con esta propiedad intuitiva. |
| [getPages()](#getPages--) | Recupere las páginas de la imagen de forma fluida con esta propiedad intuitiva. |
| [getCdrDocument()](#getCdrDocument--) | Recupere o actualice sin esfuerzo el documento CDR usando esta propiedad intuitiva. |
| [getFileFormat()](#getFileFormat--) | Recupere el formato de archivo de la imagen sin esfuerzo con esta propiedad intuitiva. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [cacheData()](#cacheData--) | Cachee los datos sin esfuerzo para evitar cargas adicionales desde la fuente subyacente con este método fácil de usar. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personalice la paleta de colores de la imagen con este método intuitivo. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Cargue una imagen desde un archivo CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Comience a trabajar con la clase [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sin esfuerzo inicializando una nueva instancia con los parámetros stream y loadOptions. Ideal para desarrolladores que buscan una forma conveniente de cargar imágenes CDR desde diversas fuentes de datos mientras personalizan el proceso de carga según sea necesario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Comience a trabajar con la clase [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sin esfuerzo inicializando una nueva instancia con los parámetros stream y loadOptions. Ideal para desarrolladores que buscan una forma conveniente de cargar imágenes CDR desde diversas fuentes de datos mientras personalizan el proceso de carga según sea necesario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream | El flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Recupere la página predeterminada de la imagen con facilidad usando esta propiedad fácil de usar. Perfecto para desarrolladores que buscan acceso rápido a la página principal de su imagen, garantizando una navegación y gestión eficientes.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Determine sin esfuerzo si los datos del objeto están actualmente en caché, eliminando la necesidad de leer los datos. Ideal para desarrolladores que buscan optimizar el rendimiento aprovechando los datos en caché de manera eficiente, garantizando un acceso más rápido a la información del objeto.

**Returns:**
boolean - `true` si los datos del objeto están en caché; de lo contrario, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupere la profundidad de bits de la imagen sin esfuerzo con esta propiedad fácil de usar. Ideal para desarrolladores que buscan determinar el nivel de detalle o la profundidad de color presente en sus imágenes, garantizando un procesamiento y manipulación precisos.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Recupere o actualice sin esfuerzo el recuento total de páginas de la imagen con esta propiedad intuitiva. Ideal para desarrolladores que buscan gestionar imágenes multipágina de forma dinámica, asegurando una navegación y manipulación eficientes del contenido de la imagen.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Recupere las páginas de la imagen sin problemas con esta propiedad intuitiva. Ideal para desarrolladores que buscan acceder y manipular páginas individuales dentro de imágenes multipágina, garantizando una navegación y procesamiento eficientes.

**Returns:**
com.aspose.imaging.Image[] - las páginas.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Recupere o actualice sin esfuerzo el documento CDR usando esta propiedad intuitiva. Ideal para desarrolladores que buscan acceder o modificar el documento CDR, garantizando flexibilidad y eficiencia en sus aplicaciones.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere el formato de archivo de la imagen sin esfuerzo con esta propiedad intuitiva. Ideal para desarrolladores que buscan determinar el formato de sus imágenes de forma dinámica, garantizando compatibilidad y procesamiento preciso en sus aplicaciones.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
int - el ancho de la imagen.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

Valor: La altura de la imagen.

**Returns:**
int - la altura de la imagen.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachee los datos sin esfuerzo para evitar cargas adicionales desde la fuente subyacente con este método fácil de usar. Ideal para desarrolladores que buscan optimizar el rendimiento precargando datos, garantizando un acceso más rápido y una operación más fluida en sus aplicaciones. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Cargue una imagen desde un archivo CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
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

