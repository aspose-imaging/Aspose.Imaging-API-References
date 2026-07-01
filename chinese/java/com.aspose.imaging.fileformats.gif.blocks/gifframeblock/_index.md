---
title: "GifFrameBlock"
second_title: "Aspose.Imaging for Java API 参考"
description: "Gif 帧块。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Gif 帧块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | 初始化 `GifFrameBlock` 类的新实例。 |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | 初始化 `GifFrameBlock` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | 块扩展标签。 |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | 图像描述符大小。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | 获取关联的颜色调色板。 |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | 创建标志。 |
| [getFileFormat()](#getFileFormat--) | 获取文件格式的值 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getFrameTime()](#getFrameTime--) | 获取持续时间。 |
| [setFrameTime(int value)](#setFrameTime-int-) | 设置持续时间。 |
| [getInterlaced()](#getInterlaced--) | 获取或设置一个值，指示此 `GifFrameBlock` 是否为交错。 |
| [isInterlaced()](#isInterlaced--) | 获取一个值，指示此图像实例是否为交错。 |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | 获取或设置一个值，指示此 `GifFrameBlock` 是否为交错。 |
| [isPaletteSorted()](#isPaletteSorted--) | 获取或设置一个值，指示颜色调色板是否已排序。 |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 获取或设置一个值，指示颜色调色板是否已排序。 |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | 获取或设置 GIF 帧的每像素位数。 |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | 获取或设置 GIF 帧的每像素位数。 |
| [getLeft()](#getLeft--) | 获取或设置图像左侧位置。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置图像左侧位置。 |
| [getTop()](#getTop--) | 获取或设置图像顶部位置。 |
| [setTop(int value)](#setTop-int-) | 获取或设置图像顶部位置。 |
| [getFrameTop()](#getFrameTop--) | 转换为 p。 |
| [getFrameLeft()](#getFrameLeft--) | 获取左侧。 |
| [getDisposalMethod()](#getDisposalMethod--) | 获取处置方法。 |
| [getFlags()](#getFlags--) | 获取或设置标志。 |
| [setFlags(byte value)](#setFlags-byte-) | 获取或设置标志。 |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | 获取一个指示是否[use alpha blending]的值。 |
| [getControlBlock()](#getControlBlock--) | 获取与此块关联的图形控制块。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个指示帧块是否具有透明颜色的值。 |
| [getTransparentColor()](#getTransparentColor--) | 获取帧块的透明颜色。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 获取一个指示帧块是否具有透明颜色的值。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | 获取帧块的透明颜色。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色的值。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置背景颜色的值。 |
| [getOriginalOptions()](#getOriginalOptions--) | 根据原始文件设置获取选项。 |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | 调整图像的亮度。 |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始的 alpha 值以保持平滑边缘。 |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑边缘。 |
| [getFullFrame()](#getFullFrame--) | 获取完整帧。 |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | 调整此[RasterCachedImage](../../com.aspose.imaging/rastercachedimage)实例的大小。 |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像宽度。 |
| height | int | 图像高度。 |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |
| width | int | 图像宽度。 |
| height | int | 图像高度。 |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |
| width | int | 图像宽度。 |
| height | int | 图像高度。 |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |
| isPaletteSorted | boolean | 如果设置为`true`，则颜色调色板已排序。 |
| isGifFrameInterlaced | boolean | 如果设置为`true`，则 GIF 帧为隔行扫描。 |
| bitsPerPixel | byte | 每像素位数。 |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化帧像素和调色板数据的图像。 |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化帧像素和调色板数据的图像。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化帧像素和调色板数据的图像。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |
| isPaletteSorted | boolean | 如果设置为`true`，则颜色调色板已排序。 |
| isGifFrameInterlaced | boolean | 如果设置为`true`，则 GIF 帧为隔行扫描。 |
| lzwCodeSize | byte | 每像素位数。 |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像并初始化帧像素和调色板数据的流。 |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像并初始化帧像素和调色板数据的流。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像并初始化帧像素和调色板数据的流。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |
| isPaletteSorted | boolean | 如果设置为`true`，则颜色调色板已排序。 |
| isGifFrameInterlaced | boolean | 如果设置为`true`，则 GIF 帧为隔行扫描。 |
| lzwCodeSize | byte | 每像素位数。 |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像并初始化帧像素和调色板数据的路径。 |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像并初始化帧像素和调色板数据的路径。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


初始化 `GifFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 用于加载图像并初始化帧像素和调色板数据的路径。 |
| 左 | int | 图像左侧位置。 |
| 上 | int | 图像顶部位置。 |
| isPaletteSorted | boolean | 如果设置为`true`，则颜色调色板已排序。 |
| isGifFrameInterlaced | boolean | 如果设置为`true`，则 GIF 帧为隔行扫描。 |
| lzwCodeSize | byte | 每像素位数。 |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


块扩展标签。

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


图像描述符大小。

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


获取关联的颜色调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 帧调色板。 |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 容器调色板。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


创建标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 颜色调色板。 |
| isPaletteSorted | boolean | 如果设置为`true`，则颜色调色板中的颜色已排序。 |
| isGifFrameInterlaced | boolean | 如果设置为`true`，则 GIF 帧图像为隔行扫描。 |

**Returns:**
byte - 已创建的标志。
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


获取文件格式的值

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

**Returns:**
int - 图像宽度。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

**Returns:**
int - 图像高度。
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

**Returns:**
int - 图像每像素位数。
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


获取持续时间。

值：持续时间（毫秒）。

**Returns:**
int - 持续时间。
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


设置持续时间。

值：持续时间（毫秒）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 持续时间。 |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


获取或设置一个值，指示此 `GifFrameBlock` 是否为交错。

**Returns:**
boolean - 若为隔行扫描则为`true`；否则为`false`。
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


获取一个值，指示此图像实例是否为交错。

值：若此图像实例为隔行扫描则为`true`；否则为`false`。

**Returns:**
boolean - 一个指示此图像实例是否交错的值。
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


获取或设置一个值，指示此 `GifFrameBlock` 是否为交错。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示交错；否则为 `false`。 |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


获取或设置一个值，指示颜色调色板是否已排序。

**Returns:**
boolean - 如果颜色调色板已排序则为 `true`；否则为 `false`。
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


获取或设置一个值，指示颜色调色板是否已排序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示颜色调色板已排序；否则为 `false`。 |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


获取或设置 GIF 帧的每像素位数。

**Returns:**
byte - GIF 帧的每像素位数。
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


获取或设置 GIF 帧的每像素位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | GIF 帧的每像素位数。 |

### getLeft() {#getLeft--}
```
public int getLeft()
```


获取或设置图像左侧位置。

**Returns:**
int - 图像左侧位置。
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


获取或设置图像左侧位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 图像左侧位置。 |

### getTop() {#getTop--}
```
public int getTop()
```


获取或设置图像顶部位置。

**Returns:**
int - 图像顶部位置。
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置图像顶部位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 图像顶部位置。 |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


转换为 p。

值：顶部。

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


获取左侧。

值：左侧。

**Returns:**
int - 左侧。
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


获取处置方法。

**Returns:**
int - 处理方式。
### getFlags() {#getFlags--}
```
public byte getFlags()
```


获取或设置标志。

**Returns:**
byte - 标志。
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


获取或设置标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 标志。 |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


获取一个指示是否[use alpha blending]的值。

值：`true` 表示 [use alpha blending]；否则为 `false`。

**Returns:**
boolean - 一个指示是否 [use alpha blending] 的值。
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


获取与此块关联的图形控制块。

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个指示帧块是否具有透明颜色的值。

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


获取帧块的透明颜色。

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


获取一个指示帧块是否具有透明颜色的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


获取帧块的透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色的值。

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 用于背景颜色的值。 |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) 方法保存，它将生成每像素 8 位的 PNG 输出图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将它们作为第二个参数传递给 [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) 方法。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


调整图像的亮度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | int | 亮度值。 |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始的 alpha 值以保持平滑边缘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColorArgb | int | 要被替换的旧颜色 ARGB 值。 |
| oldColorDiff | byte | 允许的旧颜色差异，以便能够扩大替换后的颜色色调。 |
| newColorArgb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorArgb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


获取完整帧。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


调整此[RasterCachedImage](../../com.aspose.imaging/rastercachedimage)实例的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | int | 新宽度。 |
| newHeight | int | 新高度。 |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | 调整大小设置。 |

