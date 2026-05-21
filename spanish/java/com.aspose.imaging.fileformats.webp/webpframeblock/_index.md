---
title: "WebPFrameBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el registro de abridores de bloques webp."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Representa el registro de abridores de bloques webp.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Inicializa una nueva instancia de la clase `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Inicializa una nueva instancia de la clase `WebPFrameBlock`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [getDuration()](#getDuration--) | Obtiene o establece la duración del fotograma. |
| [setDuration(short value)](#setDuration-short-) | Obtiene o establece la duración del fotograma. |
| [getLeft()](#getLeft--) | Obtiene o establece la posición izquierda del fotograma. |
| [setLeft(short value)](#setLeft-short-) | Obtiene o establece la posición izquierda del fotograma. |
| [getTop()](#getTop--) | Obtiene o establece la posición superior del fotograma. |
| [setTop(short value)](#setTop-short-) | Obtiene o establece la posición superior del fotograma. |
| [getFrameTime()](#getFrameTime--) | Obtiene la duración del fotograma. |
| [getFrameTop()](#getFrameTop--) | Obtiene el desplazamiento superior del fotograma. |
| [getFrameLeft()](#getFrameLeft--) | Obtiene el desplazamiento izquierdo del fotograma. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtiene el método de eliminación. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Establece el método de eliminación. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtiene el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Establece el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior. |
| [getFullFrame()](#getFullFrame--) | Obtiene el cuadro completo. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Inicializa una nueva instancia de la clase `WebPFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Inicializa una nueva instancia de la clase `WebPFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - La altura de la imagen.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - El ancho de la imagen.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

**Returns:**
boolean - `true` si esta instancia tiene alfa; de lo contrario, `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Si el fotograma TIFF activo tiene canal alfa, entonces se considera que toda la imagen TIFF tiene canal alfa.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Obtiene o establece la duración del fotograma.

**Returns:**
short - La duración.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Obtiene o establece la duración del fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | La duración. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Obtiene o establece la posición izquierda del fotograma.

**Returns:**
short - La izquierda.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Obtiene o establece la posición izquierda del fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | La izquierda. |

### getTop() {#getTop--}
```
public short getTop()
```


Obtiene o establece la posición superior del fotograma.

**Returns:**
short - La superior.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Obtiene o establece la posición superior del fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | La superior. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Obtiene la duración del fotograma.

**Returns:**
int - la duración del fotograma.
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Obtiene el desplazamiento superior del fotograma.

**Returns:**
int - el desplazamiento superior del fotograma.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Obtiene el desplazamiento izquierdo del fotograma.

**Returns:**
int - el desplazamiento izquierdo del fotograma.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Obtiene el método de eliminación.

**Returns:**
int - el método de disposición.
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Establece el método de eliminación.

Valor: El método de eliminación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el método de eliminación. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Obtiene el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior.

Valor: `` si este fotograma usa mezcla alfa; de lo contrario, ``.

**Returns:**
boolean - el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Establece el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior.

Valor: `` si este fotograma usa mezcla alfa; de lo contrario, ``.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | el valor que indica si el fotograma actual se mezcla con los valores alfa del fotograma anterior. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Obtiene el cuadro completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
