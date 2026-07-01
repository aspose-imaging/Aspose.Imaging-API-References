---
title: "ApngFrame"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 从单页光栅图像制作动画 PNG（APNG）图像帧。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

使用我们的 API 从单页光栅图像制作动画 PNG（APNG）图像帧。无缝设置动画和帧持续时间，编程帧数，并调整伽马和对比度水平，确保生成引人入胜且可定制的动画，以符合您的愿景。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getWidth()](#getWidth--) | 获取图像宽度。 |
| [getHeight()](#getHeight--) | 获取图像高度。 |
| [getFrameTime()](#getFrameTime--) | 获取帧持续时间。 |
| [setFrameTime(int value)](#setFrameTime-int-) | 设置帧持续时间。 |
| [getFrameTop()](#getFrameTop--) | 获取帧顶部偏移。 |
| [getFrameLeft()](#getFrameLeft--) | 获取帧左侧偏移。 |
| [getDisposalMethod()](#getDisposalMethod--) | 获取处置方法。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示图像是否具有透明颜色。 |
| [hasAlpha()](#hasAlpha--) | 获取一个值，指示此实例是否具有 alpha 通道。 |
| [getTransparentColor()](#getTransparentColor--) | 获取透明颜色。 |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | 指示图像是否具有透明颜色的值。 |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | 透明颜色。 |
| [hasBackgroundColor()](#hasBackgroundColor--) | 获取指示它是否具有背景颜色的值。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | 指示它是否具有背景颜色的值。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 背景颜色。 |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | 获取一个指示是否[use alpha blending]的值。 |
| [getFullFrame()](#getFullFrame--) | 获取完整帧。 |
| [cacheData()](#cacheData--) | 缓存数据并确保不会从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) 进行额外的数据加载。 |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

**Returns:**
int - 图像每像素位数。
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
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


获取帧持续时间。

**Returns:**
int - 帧持续时间。
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


设置帧持续时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 帧持续时间。 |

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


获取处置方法。

**Returns:**
int - 处理方式。
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


获取一个值，指示图像是否具有透明颜色。

**Returns:**
布尔型 - 指示图像是否具有透明颜色的值。
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


获取一个值，指示此实例是否具有 alpha 通道。

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


获取透明颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


指示图像是否具有透明颜色的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示图像是否具有透明颜色的值。 |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 透明颜色。 |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


获取指示它是否具有背景颜色的值。

**Returns:**
布尔型 - 指示它是否具有背景颜色的值。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


指示它是否具有背景颜色的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示它是否具有背景颜色的值。 |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


获取一个指示是否[use alpha blending]的值。

值：`true` 表示 [use alpha blending]；否则为 `false`。

**Returns:**
boolean - 一个指示是否 [use alpha blending] 的值。
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


获取完整帧。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


缓存数据并确保不会从底层 `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) 进行额外的数据加载。

