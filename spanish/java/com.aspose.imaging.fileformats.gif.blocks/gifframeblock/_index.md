---
title: "GifFrameBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Bloque de fotograma Gif."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Bloque de fotograma Gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Inicializa una nueva instancia de la clase `GifFrameBlock`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Etiqueta de extensión de bloque. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | El tamaño del descriptor de imagen. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Obtiene la paleta de colores asociada. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Crea las banderas. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getFrameTime()](#getFrameTime--) | Obtiene la duración. |
| [setFrameTime(int value)](#setFrameTime-int-) | Establece la duración. |
| [getInterlaced()](#getInterlaced--) | Obtiene o establece un valor que indica si este `GifFrameBlock` está entrelazado. |
| [isInterlaced()](#isInterlaced--) | Obtiene un valor que indica si esta instancia de imagen está entrelazada. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Obtiene o establece un valor que indica si este `GifFrameBlock` está entrelazado. |
| [isPaletteSorted()](#isPaletteSorted--) | Obtiene o establece un valor que indica si la paleta de colores está ordenada. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtiene o establece un valor que indica si la paleta de colores está ordenada. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Obtiene o establece los bits por píxel del cuadro GIF. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Obtiene o establece los bits por píxel del cuadro GIF. |
| [getLeft()](#getLeft--) | Obtiene o establece la ubicación izquierda de la imagen. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la ubicación izquierda de la imagen. |
| [getTop()](#getTop--) | Obtiene o establece la ubicación superior de la imagen. |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la ubicación superior de la imagen. |
| [getFrameTop()](#getFrameTop--) | Convierte a p. |
| [getFrameLeft()](#getFrameLeft--) | Obtiene la izquierda. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtiene el método de eliminación. |
| [getFlags()](#getFlags--) | Obtiene o establece las banderas. |
| [setFlags(byte value)](#setFlags-byte-) | Obtiene o establece las banderas. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtiene un valor que indica si [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | Obtiene el bloque de control gráfico asociado a este bloque. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si el bloque de cuadro tiene color transparente. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente del bloque de cuadro. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtiene un valor que indica si el bloque de cuadro tiene color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Obtiene el color transparente del bloque de cuadro. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un valor para el color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece un valor para el color de fondo. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de brillo para la imagen. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. |
| [getFullFrame()](#getFullFrame--) | Obtiene el cuadro completo. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona esta instancia de [RasterCachedImage](../../com.aspose.imaging/rastercachedimage). |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |
| isPaletteSorted | boolean | si se establece en `true` la paleta de colores está ordenada. |
| isGifFrameInterlaced | boolean | si se establece en `true` el fotograma GIF está entrelazado. |
| bitsPerPixel | byte | Los bits por píxel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que inicializar los datos de píxeles y paleta del fotograma. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |
| isPaletteSorted | boolean | si se establece en `true` la paleta de colores está ordenada. |
| isGifFrameInterlaced | boolean | si se establece en `true` el fotograma GIF está entrelazado. |
| lzwCodeSize | byte | Los bits por píxel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |
| isPaletteSorted | boolean | si se establece en `true` la paleta de colores está ordenada. |
| isGifFrameInterlaced | boolean | si se establece en `true` el fotograma GIF está entrelazado. |
| lzwCodeSize | byte | Los bits por píxel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Inicializa una nueva instancia de la clase `GifFrameBlock`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| izquierda | int | La posición izquierda de la imagen. |
| superior | int | La posición superior de la imagen. |
| isPaletteSorted | boolean | si se establece en `true` la paleta de colores está ordenada. |
| isGifFrameInterlaced | boolean | si se establece en `true` el fotograma GIF está entrelazado. |
| lzwCodeSize | byte | Los bits por píxel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Etiqueta de extensión de bloque.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


El tamaño del descriptor de imagen.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Obtiene la paleta de colores asociada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta del fotograma. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta del contenedor. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Crea las banderas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |
| isPaletteSorted | boolean | si se establece en `true` los colores en la paleta de colores están ordenados. |
| isGifFrameInterlaced | boolean | si se establece en `true` la imagen del fotograma GIF está entrelazada. |

**Returns:**
byte - Los indicadores creados.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene un valor del formato de archivo

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - El ancho de la imagen.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - La altura de la imagen.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Obtiene la duración.

Valor: La duración, en milisegundos.

**Returns:**
int - la duración.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Establece la duración.

Valor: La duración, en milisegundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la duración. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Obtiene o establece un valor que indica si este `GifFrameBlock` está entrelazado.

**Returns:**
boolean - `true` si está entrelazado; de lo contrario, `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Obtiene un valor que indica si esta instancia de imagen está entrelazada.

Valor: `true` si esta instancia de imagen está entrelazada; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta instancia de imagen está entrelazada.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Obtiene o establece un valor que indica si este `GifFrameBlock` está entrelazado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si está entrelazado; de lo contrario, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtiene o establece un valor que indica si la paleta de colores está ordenada.

**Returns:**
boolean - `true` si la paleta de colores está ordenada; de lo contrario, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtiene o establece un valor que indica si la paleta de colores está ordenada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si la paleta de colores está ordenada; de lo contrario, `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Obtiene o establece los bits por píxel del cuadro GIF.

**Returns:**
byte - Los bits por píxel del fotograma GIF.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Obtiene o establece los bits por píxel del cuadro GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | Los bits por píxel del fotograma GIF. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtiene o establece la ubicación izquierda de la imagen.

**Returns:**
int - La ubicación izquierda de la imagen.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtiene o establece la ubicación izquierda de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La ubicación izquierda de la imagen. |

### getTop() {#getTop--}
```
public int getTop()
```


Obtiene o establece la ubicación superior de la imagen.

**Returns:**
int - Ubicación superior de la imagen.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtiene o establece la ubicación superior de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Ubicación superior de la imagen. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Convierte a p.

Valor: La parte superior.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Obtiene la izquierda.

Valor: La izquierda.

**Returns:**
int - la izquierda.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Obtiene el método de eliminación.

**Returns:**
int - el método de disposición.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Obtiene o establece las banderas.

**Returns:**
byte - Los indicadores.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Obtiene o establece las banderas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | Los indicadores. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Obtiene un valor que indica si [use alpha blending].

Valor: `true` si [use alpha blending]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Obtiene el bloque de control gráfico asociado a este bloque.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene un valor que indica si el bloque de cuadro tiene color transparente.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtiene el color transparente del bloque de cuadro.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtiene un valor que indica si el bloque de cuadro tiene color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Obtiene el color transparente del bloque de cuadro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene un valor para el color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece un valor para el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un valor para el color de fondo. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones basadas en la configuración original del archivo. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste de brillo para la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldColorArgb | int | Valor ARGB del color antiguo a reemplazar. |
| oldColorDiff | byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| newColorArgb | int | Valor ARGB del color nuevo para reemplazar el color antiguo. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usas en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorArgb | int | Valor ARGB del color nuevo para reemplazar colores no transparentes. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Obtiene el cuadro completo.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Redimensiona esta instancia de [RasterCachedImage](../../com.aspose.imaging/rastercachedimage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | Nuevo ancho. |
| newHeight | int | Nueva altura. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Configuración de redimensionamiento. |

