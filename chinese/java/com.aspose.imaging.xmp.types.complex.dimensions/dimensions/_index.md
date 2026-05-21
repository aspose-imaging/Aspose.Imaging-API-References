---
title: "尺寸"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "包含已绘制对象的尺寸。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.complex.dimensions/dimensions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class Dimensions extends ComplexTypeBase
```

包含已绘制对象的尺寸。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Dimensions()](#Dimensions--) | 初始化 `Dimensions` 类的新实例。 |
| [Dimensions(float width, float height)](#Dimensions-float-float-) | 初始化 `Dimensions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 获取或设置宽度。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置宽度。 |
| [getHeight()](#getHeight--) | 获取或设置高度。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置高度。 |
| [getUnits()](#getUnits--) | 获取或设置单位。 |
| [setUnits(String value)](#setUnits-java.lang.String-) | 获取或设置单位。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### Dimensions() {#Dimensions--}
```
public Dimensions()
```


初始化 `Dimensions` 类的新实例。

### Dimensions(float width, float height) {#Dimensions-float-float-}
```
public Dimensions(float width, float height)
```


初始化 `Dimensions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | float | 宽度。 |
| 高度 | float | 高度。 |

### getWidth() {#getWidth--}
```
public float getWidth()
```


获取或设置宽度。

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


获取或设置宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


获取或设置高度。

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


获取或设置高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getUnits() {#getUnits--}
```
public String getUnits()
```


获取或设置单位。

例如：英寸、毫米、像素、派卡、磅点等。值：单位。

**Returns:**
java.lang.String
### setUnits(String value) {#setUnits-java.lang.String-}
```
public void setUnits(String value)
```


获取或设置单位。

例如：英寸、毫米、像素、派卡、磅点等。值：单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
