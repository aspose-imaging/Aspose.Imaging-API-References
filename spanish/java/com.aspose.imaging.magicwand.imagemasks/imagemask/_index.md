---
title: "ImageMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara de imagen binaria."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

Describe una máscara de imagen binaria.
## Métodos

| Método | Descripción |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Convertir `mask` a un [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Invierte la máscara. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Unión de dos máscaras. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Restar la segunda máscara de la primera. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Intersección de dos máscaras. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Disyunción exclusiva de dos máscaras. |
| [getSource()](#getSource--) | Obtiene la imagen fuente utilizada para crear esta máscara, si existe. |
| [getWidth()](#getWidth--) | Obtiene el ancho, en píxeles, de esta máscara. |
| [getHeight()](#getHeight--) | Obtiene la altura, en píxeles, de esta máscara. |
| [getBounds()](#getBounds--) | Obtiene los límites, en píxeles, de esta máscara. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtiene la opacidad del píxel especificado. |
| [inflate(int size)](#inflate-int-) | Infla esta máscara en la cantidad especificada. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Recorta la máscara con el tamaño especificado. |
| [crop(int width, int height)](#crop-int-int-) | Recorta la máscara con el ancho y la altura especificados. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la máscara con el rectángulo especificado. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Comprueba si el píxel especificado es opaco. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Comprueba si el píxel especificado es transparente. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Obtiene la opacidad del píxel especificado con precisión de byte. |
| [getFeathered()](#getFeathered--) | Obtiene la máscara en escala de grises con el borde difuminado con la configuración predeterminada. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Obtiene la máscara en escala de grises con el borde difuminado con la configuración especificada. |
| [apply()](#apply--) | Aplica la máscara actual a la fuente [RasterImage](../../com.aspose.imaging/rasterimage), si existe. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Aplica la máscara actual al [RasterImage](../../com.aspose.imaging/rasterimage) especificado. |
| [invert()](#invert--) | Obtiene la inversión de la máscara actual. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Obtiene la unión de la máscara actual con la proporcionada. |
| [union()](#union--) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Obtiene la sustracción de la máscara proporcionada de la actual. |
| [subtract()](#subtract--) | Obtiene el resultado de la selección con varita mágica aplicada a la fuente de la máscara actual restado de la máscara. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene el resultado de la selección con varita mágica aplicada a la fuente de la máscara actual restado de la máscara. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Obtiene la intersección de la máscara actual con la proporcionada. |
| [intersect()](#intersect--) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Obtiene la disyunción exclusiva de la máscara actual con la proporcionada. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada. |

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

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


Convertir `mask` a un [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | El valor de la máscara. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Invierte la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La máscara a invertir. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


Unión de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La primera máscara. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La segunda máscara. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


Restar la segunda máscara de la primera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La primera máscara. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La segunda máscara. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


Intersección de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La primera máscara. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La segunda máscara. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


Disyunción exclusiva de dos máscaras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La primera máscara. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | La segunda máscara. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
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
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
```


Obtiene la opacidad del píxel especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del píxel. |
| y | int | La coordenada y del píxel. |

**Returns:**
boolean - true si el píxel especificado es opaco; de lo contrario, false.
### inflate(int size) {#inflate-int-}
```
public abstract ImageMask inflate(int size)
```


Infla esta máscara en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | La cantidad para inflar esta máscara. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Recorta la máscara con el tamaño especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | El tamaño especificado. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Recorta la máscara con el ancho y la altura especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho especificado. |
| height | int | La altura especificada. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Recorta la máscara con el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo especificado. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
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
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Obtiene la máscara en escala de grises con el borde difuminado con la configuración predeterminada.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Obtiene la máscara en escala de grises con el borde difuminado con la configuración especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Configuración de difuminado. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Aplica la máscara actual a la fuente [RasterImage](../../com.aspose.imaging/rasterimage), si existe.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nueva máscara usando la herramienta magic wand basada en el tono y color del píxel (120, 100) con un umbral personalizado igual a 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Aplicar máscara a la imagen
            .apply();

    // Guardar imagen con la opción de tipo de color de transparencia forzada
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Aplica la máscara actual al [RasterImage](../../com.aspose.imaging/rasterimage) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen a la que aplicar la máscara. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Obtiene la inversión de la máscara actual.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

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

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Obtiene la unión de la máscara actual con la proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Máscara proporcionada |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Obtiene la unión de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Obtiene la sustracción de la máscara proporcionada de la actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Máscara proporcionada |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Obtiene el resultado de la selección con varita mágica aplicada a la fuente de la máscara actual restado de la máscara.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Obtiene el resultado de la selección con varita mágica aplicada a la fuente de la máscara actual restado de la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Obtiene el resultado de la selección con varita mágica aplicada a la imagen proporcionada restado de la máscara actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Obtiene la intersección de la máscara actual con la proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Máscara proporcionada |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Obtiene la intersección de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Obtiene la disyunción exclusiva de la máscara actual con la proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Máscara proporcionada |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la fuente de la máscara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Obtiene la disyunción exclusiva de la máscara actual con el resultado de la selección con varita mágica aplicada a la imagen proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Imagen para la varita mágica. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Configuración de la varita mágica. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
