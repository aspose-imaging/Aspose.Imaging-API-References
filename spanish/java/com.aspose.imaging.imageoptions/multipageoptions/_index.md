---
title: "MultiPageOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase base para formatos compatibles con múltiples páginas"
type: docs
weight: 30
url: /es/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Clase base para formatos compatibles con múltiples páginas
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase `MultiPageOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPages()](#getPages--) | Obtiene o establece las páginas. |
| [setPages(int[] value)](#setPages-int---) | Obtiene o establece las páginas. |
| [getPageTitles()](#getPageTitles--) | Obtiene o establece los títulos de página. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Obtiene o establece los títulos de página. |
| [getTimeInterval()](#getTimeInterval--) | Obtiene el intervalo de tiempo. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Establece el intervalo de tiempo. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Obtiene las opciones de rasterizado de página. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Establece las opciones de rasterizado de página. |
| [getExportArea()](#getExportArea--) | Obtiene o establece el área de exportación. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Obtiene o establece el área de exportación. |
| [getMode()](#getMode--) | Obtiene o establece el modo. |
| [setMode(int value)](#setMode-int-) | Obtiene o establece el modo. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Obtiene o establece los nombres de capas de salida (Funciona si el formato de exportación admite la nomenclatura de capas, por ejemplo para Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Obtiene o establece los nombres de capas de salida (Funciona si el formato de exportación admite la nomenclatura de capas, por ejemplo para Psd) |
| [getMergeLayers()](#getMergeLayers--) | Obtiene un valor que indica si [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Establece un valor que indica si [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Inicializa las páginas a partir de la matriz de rangos |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | int[] | Las páginas. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| páginas | int[] | La matriz de páginas. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área de exportación. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Los títulos de página. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Los títulos de página. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área de exportación. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | El `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | El `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área de exportación. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | El `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | El `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área de exportación. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | int | El índice de página. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Inicializa una nueva instancia de la clase `MultiPageOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | int | El índice de página. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área de exportación. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Obtiene o establece las páginas.

Valor: Las páginas.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Obtiene o establece las páginas.

Valor: Las páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Nota que si la imagen es colorida, se convertirá automáticamente al formato B/N según la opción a continuación:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Por defecto, todas las páginas se almacenarán en el TIFF de salida, pero el conjunto deseado de páginas puede especificarse explícitamente.
        // Solo la primera y la segunda página se exportarán.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Establecer títulos de página.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Guardar en TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Obtiene o establece los títulos de página.

Valor: Los títulos de página.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Obtiene o establece los títulos de página.

Valor: Los títulos de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Nota que si la imagen es colorida, se convertirá automáticamente al formato B/N según la opción a continuación:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Por defecto, todas las páginas se almacenarán en el TIFF de salida, pero el conjunto deseado de páginas puede especificarse explícitamente.
        // Solo la primera y la segunda página se exportarán.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Establecer títulos de página.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Guardar en TIFF
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Obtiene el intervalo de tiempo.

Valor: El intervalo de tiempo.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Establece el intervalo de tiempo.

Valor: El intervalo de tiempo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | el intervalo de tiempo. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Obtiene las opciones de rasterizado de página.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - las opciones de rasterizado de página.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Establece las opciones de rasterizado de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | las opciones de rasterizado de página. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Obtiene o establece el área de exportación.

Valor: El área de exportación.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Obtiene o establece el área de exportación.

Valor: El área de exportación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Obtiene o establece el modo.

Valor: El modo.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Obtiene o establece el modo.

Valor: El modo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Obtiene o establece los nombres de capas de salida (Funciona si el formato de exportación admite la nomenclatura de capas, por ejemplo para Psd)

Valor: Los nombres de capas de salida.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Obtiene o establece los nombres de capas de salida (Funciona si el formato de exportación admite la nomenclatura de capas, por ejemplo para Psd)

Valor: Los nombres de capas de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Obtiene un valor que indica si [merge layers].

Valor: `true` si [merge layers]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Establece un valor que indica si [merge layers].

Valor: `true` si [merge layers]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Inicializa las páginas a partir de la matriz de rangos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Los rangos. |

