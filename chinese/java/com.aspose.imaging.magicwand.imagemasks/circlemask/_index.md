---
title: "CircleMask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述圆形掩码。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

描述圆形掩码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | 使用指定的中心点和半径初始化 [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) 类的新实例。 |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | 使用指定的中心点和半径初始化 [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | 获取此掩码的边界（以像素为单位）。 |
| [get_Item(int x, int y)](#get-Item-int-int-) | 获取指定像素的透明度。 |
| [inflate(int size)](#inflate-int-) | 按指定量膨胀此掩码。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形裁剪掩码。 |
| [deepClone()](#deepClone--) | 创建一个新对象，该对象是当前实例的副本。 |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


使用指定的中心点和半径初始化 [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 所选区域中心点的 x 坐标。 |
| y | int | 所选区域中心点的 y 坐标。 |
| radius | int | 所选区域的半径。 |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


使用指定的中心点和半径初始化 [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | 所选区域的中心点。 |
| radius | int | 所选区域的半径。 |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


获取此掩码的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


获取指定像素的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素不透明则为 true；否则为 false。
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


按指定量膨胀此掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 大小 | int | 用于膨胀此掩码的量。 |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


使用指定的矩形裁剪掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 指定的矩形。 |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建一个新对象，该对象是当前实例的副本。

**Returns:**
java.lang.Object - 此实例的副本的新对象。
