---
title: "ImageBitMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en binär bildmask."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

Beskriver en binär bildmask.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | Initierar en ny instans av klassen [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med den angivna bredden och höjden. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med storleken på den angivna befintliga [RasterImage](../../com.aspose.imaging/rasterimage). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna för den valda delen av masken, i pixlar. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [inflate(int size)](#inflate-int-) | Utökar den här masken med den angivna mängden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [deepClone()](#deepClone--) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | Ställer in opaciteten för den angivna pixeln. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Inverterar masken. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Union av två masker. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Subtrahera andra masken från den första. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Snitt av två masker. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Exklusiv disjunktion av två masker. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


Initierar en ny instans av klassen [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Maskens bredd. |
| höjd | int | Maskens höjd. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


Initierar en ny instans av klassen [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med storleken på den angivna befintliga [RasterImage](../../com.aspose.imaging/rasterimage). Angiven [RasterImage](../../com.aspose.imaging/rasterimage) kommer att lagras som källbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Källbild. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Hämtar gränserna för den valda delen av masken, i pixlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Hämtar opaciteten för den angivna pixeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. Värde: true om den angivna pixeln är ogenomskinlig; annars false. |

**Returns:**
boolean
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Utökar den här masken med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Mängden för att blåsa upp den här masken. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Beskär masken med den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den angivna rektangeln. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns:**
java.lang.Object - Ett nytt objekt som är en kopia av den här instansen.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


Ställer in opaciteten för den angivna pixeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |
| värde | boolean | true om den angivna pixeln är ogenomskinlig; annars false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


Inverterar masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Masken som ska inverteras. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


Union av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den första masken. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


Subtrahera andra masken från den första.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den första masken. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


Snitt av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den första masken. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


Exklusiv disjunktion av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den första masken. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
