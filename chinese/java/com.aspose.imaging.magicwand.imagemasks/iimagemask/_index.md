---
title: "IImageMask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述掩码。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

描述掩码。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSource()](#getSource--) | 获取用于创建此掩码的源图像（如果存在）。 |
| [getWidth()](#getWidth--) | 获取此掩码的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 获取此掩码的高度（以像素为单位）。 |
| [getBounds()](#getBounds--) | 获取此掩码的边界（以像素为单位）。 |
| [getSelectionBounds()](#getSelectionBounds--) | 获取掩码选定部分的边界（以像素为单位）。 |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | 检查指定像素是否不透明。 |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | 检查指定像素是否透明。 |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | 获取指定像素的透明度，精确到字节。 |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


获取用于创建此掩码的源图像（如果存在）。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


获取此掩码的宽度（以像素为单位）。

**Returns:**
int - 此掩码的宽度（以像素为单位）。
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


获取此掩码的高度（以像素为单位）。

**Returns:**
int - 此掩码的高度（以像素为单位）。
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


获取此掩码的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


获取掩码选定部分的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


检查指定像素是否不透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素不透明则为 true；否则为 false。
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


检查指定像素是否透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素透明则为 true；否则为 false。
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


获取指定像素的透明度，精确到字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
byte - 字节值，表示指定像素的透明度。
