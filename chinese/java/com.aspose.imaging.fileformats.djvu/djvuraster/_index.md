---
title: "DjvuRaster"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "用于表示 Djvu 栅格图像的类，其中包含某些操作的结果。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.djvu/djvuraster/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class DjvuRaster extends RasterCachedImage
```

用于表示 Djvu 栅格图像的类，其中包含某些操作的结果。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DjvuRaster(int width, int height, IRasterImageArgb32PixelLoader loader)](#DjvuRaster-int-int-com.aspose.imaging.IRasterImageArgb32PixelLoader-) | 初始化 `DjvuRaster` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取宽度。 |
| [getHeight()](#getHeight--) | 获取高度。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取图像每像素位数计数。 |
| [getLength()](#getLength--) | 获取长度。 |
### DjvuRaster(int width, int height, IRasterImageArgb32PixelLoader loader) {#DjvuRaster-int-int-com.aspose.imaging.IRasterImageArgb32PixelLoader-}
```
public DjvuRaster(int width, int height, IRasterImageArgb32PixelLoader loader)
```


初始化 `DjvuRaster` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 宽度。 |
| 高度 | int | 高度。 |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader) | 加载器。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取宽度。

值：宽度。

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取高度。

值：高度。

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取图像每像素位数计数。

值：图像每像素位数。

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


获取长度。

值：长度。

**Returns:**
int
