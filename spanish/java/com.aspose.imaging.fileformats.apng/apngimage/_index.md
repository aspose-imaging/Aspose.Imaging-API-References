---
title: "ApngImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para el formato de archivo de imagen Animated PNG (Portable Network Graphics animado) es una solución versátil para los desarrolladores que buscan integrar contenido animado en sus aplicaciones."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

La API para el formato de archivo de imagen Animated PNG (Animated Portable Network Graphics) es una solución versátil para los desarrolladores que buscan integrar contenido animado en sus aplicaciones. Esta API ofrece un control amplio sobre la configuración de los fotogramas, permitiendo a los usuarios definir parámetros específicos de cada fotograma, incluidos la duración del bucle y la configuración de archivos PNG. Con esta herramienta rica en funciones, puedes gestionar y optimizar sin esfuerzo la visualización de imágenes APNG, importar y exportar imágenes, mejorando los aspectos dinámicos e interactivos de tus aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Comienza a trabajar con la clase [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) inicializando una nueva instancia sin esfuerzo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Accede rápidamente a la información sobre el formato de archivo con esta propiedad conveniente. |
| [getPageCount()](#getPageCount--) | Obtén el número total de páginas en tu archivo de imagen sin esfuerzo con esta propiedad. |
| [getPages()](#getPages--) | Accede sin esfuerzo a las páginas de tu imagen con esta propiedad conveniente. |
| [getNumPlays()](#getNumPlays--) | Controla sin esfuerzo la cantidad de veces que tu animación se repite con esta propiedad versátil. |
| [setNumPlays(int value)](#setNumPlays-int-) | Controla sin esfuerzo la cantidad de veces que tu animación se repite con esta propiedad versátil. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Ajusta fácilmente la duración predeterminada del fotograma para crear nuevos fotogramas con esta propiedad flexible. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Ajusta fácilmente la duración predeterminada del fotograma para crear nuevos fotogramas con esta propiedad flexible. |
| [getInterlaced()](#getInterlaced--) | Determina rápidamente si este objeto [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) está entrelazado con esta propiedad conveniente. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupera opciones basadas en la configuración original del archivo sin esfuerzo con este método intuitivo. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Recupere sin esfuerzo las opciones predeterminadas con este método sencillo. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtén rápidamente la fecha y hora en que la imagen de recurso fue modificada por última vez con este método fácil de usar. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Agrega una nueva página a la imagen sin esfuerzo con este método intuitivo. |
| [addFrame()](#addFrame--) | /\\*\\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Expande sin esfuerzo tu colección de fotogramas añadiendo un nuevo fotograma al final con este método intuitivo. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Expande tu colección de fotogramas sin problemas añadiendo un nuevo fotograma al con este método intuitivo. |
| [insertFrame(int index)](#insertFrame-int-) | Inserta sin esfuerzo un nuevo fotograma en tu colección de fotogramas en el especificado con este método intuitivo. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Inserta un nuevo fotograma en su propia colección de fotogramas en el índice especificado. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Inserta un nuevo fotograma en su propia colección de fotogramas en el índice especificado. |
| [popFrameAt(int index)](#popFrameAt-int-) | Elimina y recupera el fotograma en el índice especificado de tu colección de fotogramas con este método intuitivo. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Elimina el fotograma en el índice especificado de tu colección de fotogramas sin problemas con este método. |
| [removeAllFrames()](#removeAllFrames--) | Limpia tu colección de fotogramas eliminando todos los fotogramas con este método intuitivo. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Establece la imagen raster especificada como la imagen predeterminada para la animación actual sin esfuerzo con este método. |
| [resetDefaultImage()](#resetDefaultImage--) | Elimine una imagen predeterminada establecida previamente con este método intuitivo. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Configuración de la duración de fotograma predeterminada
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Comience a trabajar con la clase [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) inicializando una nueva instancia sin esfuerzo. Perfecto para desarrolladores que buscan comenzar a usar objetos ApngImage rápida y eficientemente en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Las opciones. |
| width | int | El ancho. |
| height | int | La altura. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Acceda rápidamente a información sobre el formato de archivo con esta práctica propiedad. Ideal para desarrolladores que necesitan obtener detalles sobre el formato de sus archivos Apng fácilmente.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupere el número total de páginas en su archivo de imagen sin esfuerzo con esta propiedad. Ideal para desarrolladores que necesitan acceso rápido a la información del recuento de páginas.

Valor: El recuento de páginas.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Acceda sin esfuerzo a las páginas de su imagen con esta práctica propiedad. Perfecto para desarrolladores que buscan un acceso rápido y sencillo a páginas individuales para su manipulación.

Valor: Las páginas.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Controle sin esfuerzo la cantidad de veces que su animación se repite con esta versátil propiedad. Perfecto para desarrolladores que buscan un control preciso sobre el comportamiento de la animación, con soporte para bucle infinito cuando el valor es 0.

Valor: La cantidad de repeticiones.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Controle sin esfuerzo la cantidad de veces que su animación se repite con esta versátil propiedad. Perfecto para desarrolladores que buscan un control preciso sobre el comportamiento de la animación, con soporte para bucle infinito cuando el valor es 0.

Valor: La cantidad de repeticiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Ajuste fácilmente la duración predeterminada del fotograma para crear nuevos fotogramas con esta propiedad flexible. Perfecto para desarrolladores que buscan personalizar la sincronización de fotogramas de manera eficiente en sus animaciones.

Valor: La duración predeterminada del fotograma, en milisegundos.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Ajuste fácilmente la duración predeterminada del fotograma para crear nuevos fotogramas con esta propiedad flexible. Perfecto para desarrolladores que buscan personalizar la sincronización de fotogramas de manera eficiente en sus animaciones.

Valor: La duración predeterminada del fotograma, en milisegundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Determine rápidamente si este objeto [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) está entrelazado con esta práctica propiedad. Ideal para desarrolladores que necesitan verificar el estado de entrelazado de imágenes PNG fácilmente.

Valor: `true` si está entrelazado; de lo contrario, `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupere opciones basadas en la configuración del archivo original sin esfuerzo con este método intuitivo. Perfecto para desarrolladores que buscan acceder y utilizar configuraciones que se alineen con las características del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá la imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Recupere las opciones predeterminadas sin esfuerzo con este método sencillo. Ideal para desarrolladores que buscan acceso rápido a la configuración predeterminada de imágenes Apng.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] | Los argumentos. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Obtenga rápidamente la fecha y hora en que la imagen de recurso fue modificada por última vez con este método fácil de usar. Ideal para desarrolladores que necesitan rastrear cambios y gestionar recursos de manera eficaz.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useDefault | boolean | si se establece en `true` utiliza la información de FileInfo como valor predeterminado. |

**Returns:**
java.util.Date - La fecha y hora en que la imagen de recurso fue modificada por última vez.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Agregue una nueva página a la imagen sin esfuerzo con este método intuitivo. Perfecto para desarrolladores que buscan expandir dinámicamente el contenido de sus archivos de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La página a agregar. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\\*\\*

Añada fácilmente un nuevo fotograma al final de su colección de fotogramas con este método sencillo. Ideal para desarrolladores que desean expandir dinámicamente su colección de fotogramas para animaciones con imágenes de varios fotogramas. Se creará un nuevo fotograma según el tamaño de la imagen actual.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Expanda sin esfuerzo su colección de fotogramas añadiendo un nuevo fotograma al final con este método intuitivo. Perfecto para desarrolladores que buscan mejorar dinámicamente sus animaciones de imágenes de varios fotogramas. El contenido del nuevo fotograma se rellenará a partir de la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen del fotograma. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Expanda su colección de fotogramas sin problemas añadiendo un nuevo fotograma con este método intuitivo. Ideal para desarrolladores que buscan enriquecer sus animaciones de imágenes de varios fotogramas. El contenido del nuevo fotograma se rellenará a partir de la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen del fotograma. |
| frameTime | long | La duración del fotograma, en milisegundos. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Inserte sin esfuerzo un nuevo fotograma en su colección de fotogramas en la posición especificada con este método intuitivo. Ideal para desarrolladores que buscan un control preciso sobre la disposición de los fotogramas en sus animaciones de imágenes de varios fotogramas. Se creará un nuevo fotograma según el tamaño de la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Inserta un nuevo fotograma en la propia colección de fotogramas en el índice especificado. El contenido del nuevo fotograma se rellenará a partir de la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen del fotograma. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Inserta un nuevo fotograma en la propia colección de fotogramas en el índice especificado. El contenido del nuevo fotograma se rellenará a partir de la imagen especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen del fotograma. |
| frameTime | long | La duración del fotograma, en milisegundos. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Elimine y recupere el fotograma en el índice especificado de su colección de fotogramas con este método intuitivo. Perfecto para desarrolladores que buscan una gestión eficiente de los fotogramas en sus animaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Elimine el fotograma en el índice especificado de su colección de fotogramas sin problemas con este método. Perfecto para desarrolladores que buscan una gestión simplificada de los fotogramas en sus imágenes de varios fotogramas. El fotograma a eliminar será descartado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Limpia tu colección de fotogramas eliminando todos los fotogramas con este método intuitivo. Ideal para desarrolladores que buscan restablecer o actualizar sus animaciones.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Establece la imagen raster especificada como la imagen predeterminada para la animación actual sin esfuerzo con este método. Perfecto para desarrolladores que buscan personalizar la imagen predeterminada en sus animaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Elimina una imagen predeterminada establecida previamente con este método intuitivo. Ideal para desarrolladores que buscan restablecer o borrar la imagen predeterminada en su animación. Después de esto, la imagen predeterminada es el primer fotograma de la propia colección de fotogramas (no se puede eliminar con este método).

