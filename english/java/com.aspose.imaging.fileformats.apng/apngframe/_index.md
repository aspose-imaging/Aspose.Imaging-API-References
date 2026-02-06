---
title: ApngFrame
second_title: Aspose.Imaging for Java API Reference
description: Craft animated PNG APNG image frames from single-page raster images with our API.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Craft animated PNG (APNG) image frames from single-page raster images with our API. Seamlessly set animation and frame duration, program the number of frames, and adjust gamma and contrast levels, ensuring captivating and customizable animations tailored to your vision.
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getFrameTime()](#getFrameTime--) | Gets the frame duration. |
| [setFrameTime(int value)](#setFrameTime-int-) | Sets the frame duration. |
| [getFrameTop()](#getFrameTop--) | Gets the frame top offset. |
| [getFrameLeft()](#getFrameLeft--) | Gets the frame left offset. |
| [getDisposalMethod()](#getDisposalMethod--) | Gets the disposal method. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether image has transparent color. |
| [hasAlpha()](#hasAlpha--) | Get a value indicating whether this instance has alpha. |
| [getTransparentColor()](#getTransparentColor--) | Gets the transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | A value indicating whether image has transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | The transparent color. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gets a value indicating whether it has background color. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | A value indicating whether it has background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | The background color. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Gets a value indicating whether [use alpha blending]. |
| [getFullFrame()](#getFullFrame--) | Gets the full frame. |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - the image bits per pixel count.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int - the image width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int - the image height.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Gets the frame duration.

**Returns:**
int - the frame duration.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Sets the frame duration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the frame duration. |

### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Gets the frame top offset.

**Returns:**
int - the frame top offset.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Gets the frame left offset.

**Returns:**
int - the frame left offset.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Gets the disposal method.

**Returns:**
int - the disposal method.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets a value indicating whether image has transparent color.

**Returns:**
boolean - a value indicating whether image has transparent color.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Get a value indicating whether this instance has alpha.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Gets the transparent color.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


A value indicating whether image has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether image has transparent color. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


The transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the transparent color. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Gets a value indicating whether it has background color.

**Returns:**
boolean - a value indicating whether it has background color.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


A value indicating whether it has background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether it has background color. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


The background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background color. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Gets a value indicating whether [use alpha blending].

Value: `true` if [use alpha blending]; otherwise, `false`.

**Returns:**
boolean - a value indicating whether [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Gets the full frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

