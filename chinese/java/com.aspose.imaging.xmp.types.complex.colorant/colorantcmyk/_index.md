---
title: "ColorantCmyk"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 CMYK 色剂。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase), [com.aspose.imaging.xmp.types.complex.colorant.ColorantBase](../../com.aspose.imaging.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

表示 CMYK 色剂。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | 初始化 `ColorantCmyk` 类的新实例。 |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | 初始化 `ColorantCmyk` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [COLOR_VALUE_MAX](#COLOR-VALUE-MAX) | CMYK 着色剂的颜色最大值。 |
| [COLOR_VALUE_MIN](#COLOR-VALUE-MIN) | CMYK 着色剂的颜色最小值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlack()](#getBlack--) | 获取或设置黑色组件的值。 |
| [setBlack(float value)](#setBlack-float-) | 获取或设置黑色组件的值。 |
| [getCyan()](#getCyan--) | 获取或设置青色组件的值。 |
| [setCyan(float value)](#setCyan-float-) | 获取或设置青色组件的值。 |
| [getMagenta()](#getMagenta--) | 获取或设置品红组件的值。 |
| [setMagenta(float value)](#setMagenta-float-) | 获取或设置品红组件的值。 |
| [getYellow()](#getYellow--) | 获取或设置黄色组件的值。 |
| [setYellow(float value)](#setYellow-float-) | 获取或设置黄色组件的值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


初始化 `ColorantCmyk` 类的新实例。

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


初始化 `ColorantCmyk` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 黑色 | float | 黑色组件的值。 |
| 青色 | float | 青色组件的值。 |
| 品红 | float | 品红组件的值。 |
| 黄色 | float | 黄色组件的值。 |

### COLOR_VALUE_MAX {#COLOR-VALUE-MAX}
```
public static final float COLOR_VALUE_MAX
```


CMYK 着色剂的颜色最大值。

### COLOR_VALUE_MIN {#COLOR-VALUE-MIN}
```
public static final float COLOR_VALUE_MIN
```


CMYK 着色剂的颜色最小值。

### getBlack() {#getBlack--}
```
public float getBlack()
```


获取或设置黑色组件的值。

值：黑色组件的值。

**Returns:**
float
### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


获取或设置黑色组件的值。

值：黑色组件的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getCyan() {#getCyan--}
```
public float getCyan()
```


获取或设置青色组件的值。

值：青色组件的值。

**Returns:**
float
### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


获取或设置青色组件的值。

值：青色组件的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


获取或设置品红组件的值。

值：品红组件的值。

**Returns:**
float
### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


获取或设置品红组件的值。

值：品红组件的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getYellow() {#getYellow--}
```
public float getYellow()
```


获取或设置黄色组件的值。

值：黄色组件的值。

**Returns:**
float
### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


获取或设置黄色组件的值。

值：黄色组件的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
