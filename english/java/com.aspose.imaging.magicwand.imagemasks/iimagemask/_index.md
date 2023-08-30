---
title: IImageMask
second_title: Aspose.Imaging for Java API Reference
description: Describes a mask.
type: docs
weight: 18
url: /java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Describes a mask.
## Methods

| Method | Description |
| --- | --- |
| [getSource()](#getSource--) | Gets the source image used to create this mask, if exists. |
| [getWidth()](#getWidth--) | Gets the width, in pixels, of this mask. |
| [getHeight()](#getHeight--) | Gets the height, in pixels, of this mask. |
| [getBounds()](#getBounds--) | Gets the bounds, in pixels, of this mask. |
| [getSelectionBounds()](#getSelectionBounds--) | Gets the bounds of the selected part of the mask, in pixels. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Checks if the specified pixel is opaque. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Checks if the specified pixel is transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Gets the opacity of the specified pixel with byte precision. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Gets the source image used to create this mask, if exists.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gets the width, in pixels, of this mask.

**Returns:**
int - the width, in pixels, of this mask.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gets the height, in pixels, of this mask.

**Returns:**
int - the height, in pixels, of this mask.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Gets the bounds, in pixels, of this mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Gets the bounds of the selected part of the mask, in pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Checks if the specified pixel is opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is opaque; otherwise, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Checks if the specified pixel is transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is transparent; otherwise, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Gets the opacity of the specified pixel with byte precision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
byte - Byte value, representing the opacity of the specified pixel.
