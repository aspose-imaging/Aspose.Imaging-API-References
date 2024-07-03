---
title: GifFrameBlock
second_title: Aspose.Imaging for Java API Reference
description: Gif frame block.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Gif frame block.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Initializes a new instance of the `GifFrameBlock` class. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Initializes a new instance of the `GifFrameBlock` class. |
## Fields

| Field | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Block extension label. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | The image descriptor size. |
## Methods

| Method | Description |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Gets the associated color palette. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Creates the flags. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getFrameTime()](#getFrameTime--) | Gets the duration. |
| [setFrameTime(int value)](#setFrameTime-int-) | Sets the duration. |
| [getInterlaced()](#getInterlaced--) | Gets or sets a value indicating whether this `GifFrameBlock` is interlaced. |
| [isInterlaced()](#isInterlaced--) | Gets a value indicating whether this image instance is interlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Gets or sets a value indicating whether this `GifFrameBlock` is interlaced. |
| [isPaletteSorted()](#isPaletteSorted--) | Gets or sets a value indicating whether color palette is sorted. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Gets or sets a value indicating whether color palette is sorted. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Gets or sets the GIF frame bits per pixel. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Gets or sets the GIF frame bits per pixel. |
| [getLeft()](#getLeft--) | Gets or sets the left image location. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the left image location. |
| [getTop()](#getTop--) | Gets or sets the top image location. |
| [setTop(int value)](#setTop-int-) | Gets or sets the top image location. |
| [getFrameTop()](#getFrameTop--) | Converts to p. |
| [getFrameLeft()](#getFrameLeft--) | Gets the left. |
| [getDisposalMethod()](#getDisposalMethod--) | Gets the disposal method. |
| [getFlags()](#getFlags--) | Gets or sets the flags. |
| [setFlags(byte value)](#setFlags-byte-) | Gets or sets the flags. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Gets a value indicating whether [use alpha blending]. |
| [getControlBlock()](#getControlBlock--) | Gets the graphics control block associated with this block. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether frame block has transparent color. |
| [getTransparentColor()](#getTransparentColor--) | Gets the transparent color of frame block. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gets a value indicating whether frame block has transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Gets the transparent color of frame block. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a value for the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets a value for the background color. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjust of a brightness for image. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. |
| [getFullFrame()](#getFullFrame--) | Gets the full frame. |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The left image position. |
| top | int | The top image position. |
| width | int | The image width. |
| height | int | The image height. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The left image position. |
| top | int | The top image position. |
| width | int | The image Width. |
| height | int | The image Height. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |
| isPaletteSorted | boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | boolean | if set to `true` the GIF frame is interlaced. |
| bitsPerPixel | byte | The bits per pixel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize frame pixel and palette data with. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |
| isPaletteSorted | boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | byte | The bits per pixel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image from and initialize frame pixel and palette data with. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image from and initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image from and initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |
| isPaletteSorted | boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | byte | The bits per pixel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image from and initialize frame pixel and palette data with. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image from and initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initializes a new instance of the `GifFrameBlock` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image from and initialize frame pixel and palette data with. |
| left | int | The left image position. |
| top | int | The top image position. |
| isPaletteSorted | boolean | if set to `true` the color palette is sorted. |
| isGifFrameInterlaced | boolean | if set to `true` the GIF frame is interlaced. |
| lzwCodeSize | byte | The bits per pixel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Block extension label.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


The image descriptor size.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Gets the associated color palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The frame palette. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The container palette. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Creates the flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |
| isPaletteSorted | boolean | if set to `true` the colors in color palette are sorted. |
| isGifFrameInterlaced | boolean | if set to `true` the GIF frame image is interlaced. |

**Returns:**
byte - The created flags.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int - The image width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int - The image height.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - The image bits per pixel count.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Gets the duration.

Value: The duration, in milliseconds.

**Returns:**
int - the duration.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Sets the duration.

Value: The duration, in milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the duration. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Gets or sets a value indicating whether this `GifFrameBlock` is interlaced.

**Returns:**
boolean - `true` if interlaced; otherwise, `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Gets a value indicating whether this image instance is interlaced.

Value: `true` if this image instance is interlaced; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this image instance is interlaced.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Gets or sets a value indicating whether this `GifFrameBlock` is interlaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if interlaced; otherwise, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Gets or sets a value indicating whether color palette is sorted.

**Returns:**
boolean - `true` if color palette is sorted; otherwise, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Gets or sets a value indicating whether color palette is sorted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if color palette is sorted; otherwise, `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Gets or sets the GIF frame bits per pixel.

**Returns:**
byte - The GIF frame bits per pixel.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Gets or sets the GIF frame bits per pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The GIF frame bits per pixel. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Gets or sets the left image location.

**Returns:**
int - The left image location.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Gets or sets the left image location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The left image location. |

### getTop() {#getTop--}
```
public int getTop()
```


Gets or sets the top image location.

**Returns:**
int - The top image location.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Gets or sets the top image location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The top image location. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Converts to p.

Value: The top.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Gets the left.

Value: The left.

**Returns:**
int - the left.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Gets the disposal method.

**Returns:**
int - the disposal method.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Gets or sets the flags.

**Returns:**
byte - The flags.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Gets or sets the flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The flags. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Gets a value indicating whether [use alpha blending].

Value: `true` if [use alpha blending]; otherwise, `false`.

**Returns:**
boolean - a value indicating whether [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Gets the graphics control block associated with this block.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets a value indicating whether frame block has transparent color.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Gets the transparent color of frame block.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Gets a value indicating whether frame block has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Gets the transparent color of frame block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets a value for the background color.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Sets a value for the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | a value for the background color. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Adjust of a brightness for image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldColorArgb | int | Old color ARGB-value to be replaced. |
| oldColorDiff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| newColorArgb | int | New color ARGB-value to replace old color with. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newColorArgb | int | New color ARGB-value to replace non-transparent colors with. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Gets the full frame.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
