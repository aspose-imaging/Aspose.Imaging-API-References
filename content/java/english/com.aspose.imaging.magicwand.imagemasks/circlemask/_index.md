---
title: CircleMask
second_title: Aspose.Imaging for Java API Reference
description: Describes a circle mask.
type: docs
weight: 10
url: /com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Describes a circle mask.
## Constructors

| Constructor | Description |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Initializes a new instance of the [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) class with the specified center point and radius. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Initializes a new instance of the [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) class with the specified center point and radius. |
## Methods

| Method | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gets the bounds, in pixels, of this mask. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Gets the opacity of the specified pixel. |
| [inflate(int size)](#inflate-int-) | Inflates this mask by the specified amount. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops mask with the specified rectangle. |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Initializes a new instance of the [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) class with the specified center point and radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the center point of the selected area. |
| y | int | The y-coordinate of the center point of the selected area. |
| radius | int | Radius of the selected area. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Initializes a new instance of the [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) class with the specified center point and radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | The center point of the selected area. |
| radius | int | Radius of the selected area. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Gets the bounds, in pixels, of this mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates a new object that is a copy of the current instance.

**Returns:**
java.lang.Object - A new object that is a copy of this instance.
