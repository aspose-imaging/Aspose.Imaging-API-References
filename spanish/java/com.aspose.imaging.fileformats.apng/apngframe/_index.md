---
title: "ApngFrame"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Crea fotogramas de imágenes PNG animado APNG a partir de imágenes raster de una sola página con nuestra API."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Crea fotogramas de imágenes PNG animado (APNG) a partir de imágenes raster de una sola página con nuestra API. Configura sin problemas la animación y la duración de los fotogramas, programa el número de fotogramas y ajusta los niveles de gamma y contraste, garantizando animaciones cautivadoras y personalizables adaptadas a tu visión.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getFrameTime()](#getFrameTime--) | Obtiene la duración del fotograma. |
| [setFrameTime(int value)](#setFrameTime-int-) | Establece la duración del fotograma. |
| [getFrameTop()](#getFrameTop--) | Obtiene el desplazamiento superior del fotograma. |
| [getFrameLeft()](#getFrameLeft--) | Obtiene el desplazamiento izquierdo del fotograma. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtiene el método de eliminación. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si la imagen tiene color transparente. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Un valor que indica si la imagen tiene color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | El color transparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtiene un valor que indica si tiene color de fondo. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Un valor que indica si tiene color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | El color de fondo. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtiene un valor que indica si [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | Obtiene el cuadro completo. |
| [cacheData()](#cacheData--) | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - el recuento de bits por píxel de la imagen.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - el ancho de la imagen.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - la altura de la imagen.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Obtiene la duración del fotograma.

**Returns:**
int - la duración del fotograma.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Establece la duración del fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la duración del fotograma. |

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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene un valor que indica si la imagen tiene color transparente.

**Returns:**
booleano - un valor que indica si la imagen tiene color transparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtiene el color transparente.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Un valor que indica si la imagen tiene color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si la imagen tiene color transparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


El color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | el color transparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtiene un valor que indica si tiene color de fondo.

**Returns:**
boolean - un valor que indica si tiene color de fondo.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Un valor que indica si tiene color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si tiene color de fondo. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


El color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | el color de fondo. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Obtiene un valor que indica si [use alpha blending].

Valor: `true` si [use alpha blending]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Obtiene el cuadro completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

