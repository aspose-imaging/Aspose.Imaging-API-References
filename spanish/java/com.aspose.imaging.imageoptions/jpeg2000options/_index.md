---
title: "Jpeg2000Options"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Cree archivos de imagen JPEG2000 JP2 con nuestra API utilizando tecnología avanzada de wavelet para codificar contenido sin pérdida."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Cree archivos de imagen JPEG2000 (JP2) con nuestra API, utilizando tecnología avanzada de wavelet para codificar contenido sin pérdida. Aproveche el soporte para varios códecs, incluida la compresión irreversible y sin pérdida, así como contenedores de metadatos XMP, garantizando versatilidad y creación de imágenes de alta calidad adaptada a sus necesidades.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Inicializa una nueva instancia de la clase `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Inicializa una nueva instancia de la clase `Jpeg2000Options`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getComments()](#getComments--) | Obtiene o establece los marcadores de comentario Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Obtiene o establece los marcadores de comentario Jpeg. |
| [getCodec()](#getCodec--) | Obtiene o establece el códec JPEG2000 |
| [setCodec(int value)](#setCodec-int-) | Obtiene o establece el códec JPEG2000 |
| [getCompressionRatios()](#getCompressionRatios--) | Obtiene o establece el Array de relación de compresión. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Obtiene o establece el Array de relación de compresión. |
| [getIrreversible()](#getIrreversible--) | Obtiene un valor que indica si se usa el DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Establece un valor que indica si se usa el DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado). |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. De hecho, solo se rasterizará una página porque JPEG 2000 no es un formato multipágina.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Inicializa una nueva instancia de la clase `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Inicializa una nueva instancia de la clase `Jpeg2000Options`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Las opciones del formato de archivo Jpeg2000 de las que copiar la configuración. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Obtiene o establece los marcadores de comentario Jpeg.

**Returns:**
java.lang.String[] - Los marcadores de comentario Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Obtiene o establece los marcadores de comentario Jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] | Los marcadores de comentario Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Obtiene o establece el códec JPEG2000

**Returns:**
int - El códec JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Obtiene o establece el códec JPEG2000

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El códec JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellene toda la imagen de rojo.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Use la Transformada Discreta de Wavelet irreversible 9-7
    saveOptions.setIrreversible(true);

    // JP2 es el formato "container" para los flujos de código JPEG 2000.
    // J2K es datos comprimidos sin procesar, sin un contenedor.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Guardar en un archivo
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Obtiene o establece el Array de relación de compresión. Diferentes relaciones de compresión para capas sucesivas. La tasa especificada para cada nivel de calidad es el factor de compresión deseado. Se requieren relaciones decrecientes.

**Returns:**
int[] - Las relaciones de compresión.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Obtiene o establece el Array de relación de compresión. Diferentes relaciones de compresión para capas sucesivas. La tasa especificada para cada nivel de calidad es el factor de compresión deseado. Se requieren relaciones decrecientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | Las relaciones de compresión. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Obtiene un valor que indica si se usa el DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado).

**Returns:**
boolean - un valor que indica si usa el DWT irreversible 9-7 (true) o usa compresión DWT sin pérdida 5-3
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Establece un valor que indica si se usa el DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si usa el DWT irreversible 9-7 (true) o usa compresión DWT sin pérdida 5-3 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellene toda la imagen de rojo.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Use la Transformada Discreta de Wavelet irreversible 9-7
    saveOptions.setIrreversible(true);

    // JP2 es el formato "container" para los flujos de código JPEG 2000.
    // J2K es datos comprimidos sin procesar, sin un contenedor.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Guardar en un archivo
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

