---
title: EmptyImageMask
second_title: Aspose.Imaging for Java API Reference
description: Describes an empty non-abstract mask.
type: docs
weight: 11
url: /com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Describes an empty non-abstract mask.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Initializes a new instance of the [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) class with the specified width and height. |
## Methods

| Method | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gets the bounds of the selected part of the mask, in pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Gets the opacity of the specified pixel. |
| [inflate(int size)](#inflate-int-) | Inflates this mask by the specified amount. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops mask with the specified rectangle. |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Initializes a new instance of the [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) class with the specified width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Width of the mask. |
| height | int | Height of the mask. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Gets the bounds of the selected part of the mask, in pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Gets the opacity of the specified pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is opaque; otherwise, false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Inflates this mask by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The amount to inflate this mask. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Crops mask with the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The specified rectangle. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates a new object that is a copy of the current instance.

**Returns:**
java.lang.Object - A new object that is a copy of this instance.
