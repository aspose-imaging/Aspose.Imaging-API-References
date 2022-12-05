---
title: WebPFrameBlock
second_title: Aspose.Imaging for Java API Reference
description: Represents the webp blocks openers registry.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Represents the webp blocks openers registry.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Initializes a new instance of the `WebPFrameBlock` class. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Initializes a new instance of the `WebPFrameBlock` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [hasAlpha()](#hasAlpha--) | Gets a value indicating whether this instance has alpha. |
| [getDuration()](#getDuration--) | Gets or sets the frame duration. |
| [setDuration(short value)](#setDuration-short-) | Gets or sets the frame duration. |
| [getLeft()](#getLeft--) | Gets or sets the frame position left. |
| [setLeft(short value)](#setLeft-short-) | Gets or sets the frame position left. |
| [getTop()](#getTop--) | Gets or sets the frame position top. |
| [setTop(short value)](#setTop-short-) | Gets or sets the frame position top. |
| [getFrameTime()](#getFrameTime--) | Gets the frame duration. |
| [getFrameTop()](#getFrameTop--) | Gets the frame top offset. |
| [getFrameLeft()](#getFrameLeft--) | Gets the frame left offset. |
| [getDisposalMethod()](#getDisposalMethod--) | Gets the disposal method. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Sets the disposal method. |
| [getUseAlphaBlending()](#getUseAlphaBlending--) | Gets the value indicating whether current frame gets blended with the previous frame alpha values. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Sets the value indicating whether current frame gets blended with the previous frame alpha values. |
| [getFullFrame()](#getFullFrame--) | Gets the full frame. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Initializes a new instance of the `WebPFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Initializes a new instance of the `WebPFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - The image bits per pixel count.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int - The image height.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int - The image width.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets a value indicating whether this instance has alpha.

**Returns:**
boolean - `true` if this instance has alpha; otherwise, `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // If the active TIFF frame has alpha channel, then the entire TIFF image is considered to have alpha channel.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// The output may look like this:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Gets or sets the frame duration.

**Returns:**
short - The duration.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Gets or sets the frame duration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | The duration. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Gets or sets the frame position left.

**Returns:**
short - The left.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Gets or sets the frame position left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | The left. |

### getTop() {#getTop--}
```
public short getTop()
```


Gets or sets the frame position top.

**Returns:**
short - The top.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Gets or sets the frame position top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | The top. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Gets the frame duration.

**Returns:**
int - the frame duration.
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
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Sets the disposal method.

Value: The disposal method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the disposal method. |

### getUseAlphaBlending() {#getUseAlphaBlending--}
```
public final boolean getUseAlphaBlending()
```


Gets the value indicating whether current frame gets blended with the previous frame alpha values.

Value: `` if this frame uses alpha-blending; otherwise, ``.

**Returns:**
boolean - the value indicating whether current frame gets blended with the previous frame alpha values.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Sets the value indicating whether current frame gets blended with the previous frame alpha values.

Value: `` if this frame uses alpha-blending; otherwise, ``.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | the value indicating whether current frame gets blended with the previous frame alpha values. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Gets the full frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
