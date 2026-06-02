---
title: "ColorMap"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义颜色转换映射。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging/colormap/
---
**Inheritance:**
java.lang.Object
```
public final class ColorMap
```

定义用于转换颜色的映射。[ImageAttributes](../../com.aspose.imaging/imageattributes) 类的多个方法通过使用颜色重新映射表（即 `com.aspose.imaging.ColorMap` 结构数组）来调整图像颜色。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorMap()](#ColorMap--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOldColor()](#getOldColor--) | 获取要转换的现有 `com.aspose.imaging.Color` 结构。 |
| [setOldColor(Color value)](#setOldColor-com.aspose.imaging.Color-) | 设置要转换的现有 `com.aspose.imaging.Color` 结构。 |
| [getNewColor()](#getNewColor--) | 获取要转换到的新 `com.aspose.imaging.Color` 结构。 |
| [setNewColor(Color value)](#setNewColor-com.aspose.imaging.Color-) | 设置要转换到的新 `com.aspose.imaging.Color` 结构。 |
### ColorMap() {#ColorMap--}
```
public ColorMap()
```


### getOldColor() {#getOldColor--}
```
public Color getOldColor()
```


获取要转换的现有 `com.aspose.imaging.Color` 结构。

**Returns:**
[Color](../../com.aspose.imaging/color) - The existing `com.aspose.imaging.Color` structure to be converted.
### setOldColor(Color value) {#setOldColor-com.aspose.imaging.Color-}
```
public void setOldColor(Color value)
```


设置要转换的现有 `com.aspose.imaging.Color` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 要转换的现有 `com.aspose.imaging.Color` 结构。 |

### getNewColor() {#getNewColor--}
```
public Color getNewColor()
```


获取要转换到的新 `com.aspose.imaging.Color` 结构。

**Returns:**
[Color](../../com.aspose.imaging/color) - The new `com.aspose.imaging.Color` structure to which to convert.
### setNewColor(Color value) {#setNewColor-com.aspose.imaging.Color-}
```
public void setNewColor(Color value)
```


设置要转换到的新 `com.aspose.imaging.Color` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 要转换到的新 `com.aspose.imaging.Color` 结构。 |

