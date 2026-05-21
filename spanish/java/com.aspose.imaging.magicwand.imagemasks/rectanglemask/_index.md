---
title: "RectangleMask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Describe una máscara rectangular."
type: docs
weight: 17
url: /es/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Describe una máscara rectangular.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Inicializa una nueva instancia de la clase [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con el punto superior izquierdo especificado, ancho y alto. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Inicializa una nueva instancia de la clase [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con el rectángulo especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtiene los límites de la parte seleccionada de la máscara, en píxeles. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtiene la opacidad del píxel especificado. |
| [inflate(int size)](#inflate-int-) | Infla esta máscara en la cantidad especificada. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la máscara con el rectángulo especificado. |
| [deepClone()](#deepClone--) | Crea un nuevo objeto que es una copia de la instancia actual. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Inicializa una nueva instancia de la clase [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con el punto superior izquierdo especificado, ancho y alto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto superior izquierdo del área seleccionada. |
| y | int | La coordenada y del punto superior izquierdo del área seleccionada. |
| width | int | Ancho del área seleccionada. |
| height | int | Altura del área seleccionada. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Inicializa una nueva instancia de la clase [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) con el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Área seleccionada especificada como un rectángulo. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Obtiene los límites de la parte seleccionada de la máscara, en píxeles.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
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
public ImageMask inflate(int size)
```


Infla esta máscara en la cantidad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | La cantidad para inflar esta máscara. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Recorta la máscara con el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo especificado. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea un nuevo objeto que es una copia de la instancia actual.

**Returns:**
java.lang.Object - Un nuevo objeto que es una copia de esta instancia.
