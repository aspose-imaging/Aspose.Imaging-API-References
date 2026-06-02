---
title: "ImageGrayscaleMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara de imagen en escala de grises."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Describe una máscara de imagen en escala de grises.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Inicializa una nueva instancia de la clase [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con el ancho y alto especificados. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Inicializa una nueva instancia de la clase [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con el tamaño de la [RasterImage](../../com.aspose.imaging/rasterimage) existente especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSource()](#getSource--) | Obtiene la imagen fuente utilizada para crear esta máscara, si existe. |
| [getWidth()](#getWidth--) | Obtiene el ancho, en píxeles, de esta máscara. |
| [getHeight()](#getHeight--) | Obtiene la altura, en píxeles, de esta máscara. |
| [getBounds()](#getBounds--) | Obtiene los límites, en píxeles, de esta máscara. |
| [getSelectionBounds()](#getSelectionBounds--) | Obtiene los límites de la parte seleccionada de la máscara, en píxeles. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtiene la opacidad del píxel especificado. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Establece la opacidad del píxel especificado. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Comprueba si el píxel especificado es opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Comprueba si el píxel especificado es transparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Obtiene la opacidad del píxel especificado con precisión de byte. |
| [deepClone()](#deepClone--) | Crea un nuevo objeto que es una copia de la instancia actual. |
| [apply()](#apply--) | Aplica la máscara actual a la fuente [RasterImage](../../com.aspose.imaging/rasterimage), si existe. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Aplica la máscara actual al [RasterImage](../../com.aspose.imaging/rasterimage) especificado. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Recorta la máscara con el tamaño especificado. |
| [crop(int width, int height)](#crop-int-int-) | Recorta la máscara con el ancho y la altura especificados. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la máscara con el rectángulo especificado. |
| [invert()](#invert--) | Obtiene la inversión de la máscara actual. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Unión de dos máscaras. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtiene la sustracción de la máscara proporcionada de la actual. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtiene la intersección de la máscara actual con la proporcionada. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtiene la disyunción exclusiva de la máscara actual con la proporcionada. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Invierte la máscara. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Unión de dos máscaras. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Restar la segunda máscara de la primera. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Intersección de dos máscaras. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Disyunción exclusiva de dos máscaras. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nueva máscara usando la herramienta magic wand basada en el tono y color del píxel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unir la máscara existente con la especificada creada por la herramienta magic wand
            .union(new MagicWandSettings(416, 387))
            // Invertir la máscara existente
            .invert()
            // Restar la máscara especificada creada por la herramienta magic wand con el umbral especificado de la existente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Restar cuatro máscaras rectangulares especificadas de la máscara existente una por una
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Suavizar la máscara con los ajustes especificados
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Aplicar máscara a la imagen
            .apply();

    // Guardar imagen
    image.save(outputFilePath);
}

```

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Inicializa una nueva instancia de la clase [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con el ancho y alto especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | Ancho de la máscara. |
| height | int | Altura de la máscara. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Inicializa una nueva instancia de la clase [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) con el tamaño de la [RasterImage](../../com.aspose.imaging/rasterimage) existente. La [RasterImage](../../com.aspose.imaging/rasterimage) especificada se almacenará como imagen de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen de origen. |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Obtiene la imagen fuente utilizada para crear esta máscara, si existe.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho, en píxeles, de esta máscara.

**Returns:**
int - el ancho, en píxeles, de esta máscara.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura, en píxeles, de esta máscara.

**Returns:**
int - la altura, en píxeles, de esta máscara.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtiene los límites, en píxeles, de esta máscara.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Obtiene los límites de la parte seleccionada de la máscara, en píxeles.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Obtiene la opacidad del píxel especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. Valor: valor de byte; 0 si es transparente; 255 si es opaco. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Establece la opacidad del píxel especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. Valor: valor de byte; 0 si es transparente; 255 si es opaco. |
| valor | byte | la opacidad del píxel especificado. |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


Comprueba si el píxel especificado es opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es opaco; de lo contrario, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


Comprueba si el píxel especificado es transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es transparente; de lo contrario, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


Obtiene la opacidad del píxel especificado con precisión de byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
byte - Valor Byte, que representa la opacidad del píxel especificado.
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crea un nuevo objeto que es una copia de la instancia actual.

**Returns:**
java.lang.Object - Un nuevo objeto que es una copia de esta instancia.
### apply() {#apply--}
```
public final void apply()
```


Aplica la máscara actual a la fuente [RasterImage](../../com.aspose.imaging/rasterimage), si existe.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Aplica la máscara actual al [RasterImage](../../com.aspose.imaging/rasterimage) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen a la que aplicar la máscara. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Recorta la máscara con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | El tamaño especificado. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Recorta la máscara con el ancho y la altura especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho especificado. |
| height | int | La altura especificada. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Recorta la máscara con el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo especificado. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Obtiene la inversión de la máscara actual.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


Unión de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Máscara proporcionada |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Obtiene la sustracción de la máscara proporcionada de la actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Máscara proporcionada |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Obtiene la intersección de la máscara actual con la proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Máscara proporcionada |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Obtiene la disyunción exclusiva de la máscara actual con la proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Máscara proporcionada |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Invierte la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La máscara a invertir. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Unión de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La primera máscara. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La segunda máscara. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Restar la segunda máscara de la primera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La primera máscara. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La segunda máscara. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Intersección de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La primera máscara. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La segunda máscara. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Disyunción exclusiva de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La primera máscara. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | La segunda máscara. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
