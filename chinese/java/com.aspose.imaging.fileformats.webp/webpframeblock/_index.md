---
title: "WebPFrameBlock"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 webp 块打开器注册表."
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

表示 webp 块打开器注册表.
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | 初始化 `WebPFrameBlock` 类的新实例。 |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | 初始化 `WebPFrameBlock` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [getDuration()](#getDuration--) | 获取或设置帧持续时间。 |
| [setDuration(short value)](#setDuration-short-) | 获取或设置帧持续时间。 |
| [getLeft()](#getLeft--) | 获取或设置帧左侧位置。 |
| [setLeft(short value)](#setLeft-short-) | 获取或设置帧左侧位置。 |
| [getTop()](#getTop--) | 获取或设置帧顶部位置。 |
| [setTop(short value)](#setTop-short-) | 获取或设置帧顶部位置。 |
| [getFrameTime()](#getFrameTime--) | 获取帧持续时间。 |
| [getFrameTop()](#getFrameTop--) | 获取帧顶部偏移。 |
| [getFrameLeft()](#getFrameLeft--) | 获取帧左侧偏移。 |
| [getDisposalMethod()](#getDisposalMethod--) | 获取处理方法。 |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | 设置处理方式。 |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | 获取指示当前帧是否与前一帧的 alpha 值混合的值。 |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | 设置指示当前帧是否与前一帧的 alpha 值混合的值。 |
| [getFullFrame()](#getFullFrame--) | 获取完整帧。 |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


初始化 `WebPFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


初始化 `WebPFrameBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

**Returns:**
int - 图像每像素位数。
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像高度。

**Returns:**
int - 图像高度。
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像宽度。

**Returns:**
int - 图像宽度。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

**Returns:**
boolean - 如果此实例具有 alpha，则为 `true`；否则为 `false`。

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // 如果活动 TIFF 帧具有 alpha 通道，则整个 TIFF 图像被视为具有 alpha 通道。
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

// 输出可能如下所示：
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


获取或设置帧持续时间。

**Returns:**
short - 持续时间。
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


获取或设置帧持续时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 持续时间。 |

### getLeft() {#getLeft--}
```
public short getLeft()
```


获取或设置帧左侧位置。

**Returns:**
short - 左侧。
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


获取或设置帧左侧位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 左侧。 |

### getTop() {#getTop--}
```
public short getTop()
```


获取或设置帧顶部位置。

**Returns:**
short - 顶部。
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


获取或设置帧顶部位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short | 顶部。 |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


获取帧持续时间。

**Returns:**
int - 帧持续时间。
### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


获取帧顶部偏移。

**Returns:**
int - 帧顶部偏移。
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


获取帧左侧偏移。

**Returns:**
int - 帧左侧偏移。
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


获取处理方法。

**Returns:**
int - 处理方式。
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


设置处理方式。

值：释放方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 处理方式。 |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


获取指示当前帧是否与前一帧的 alpha 值混合的值。

Value: `` 如果此帧使用 alpha 混合；否则， ``。

**Returns:**
boolean - 指示当前帧是否与前一帧的 alpha 值混合的值。
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


设置指示当前帧是否与前一帧的 alpha 值混合的值。

Value: `` 如果此帧使用 alpha 混合；否则， ``。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示当前帧是否与前一帧的 alpha 值混合的值。 |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


获取完整帧。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
