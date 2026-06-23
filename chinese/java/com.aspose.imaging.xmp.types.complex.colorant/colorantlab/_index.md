---
title: "ColorantLab"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 LAB 色剂。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.xmp.types.complex.colorant/colorantlab/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase), [com.aspose.imaging.xmp.types.complex.colorant.ColorantBase](../../com.aspose.imaging.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantLab extends ColorantBase
```

表示 LAB 色剂。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorantLab()](#ColorantLab--) | 初始化 `ColorantLab` 类的新实例。 |
| [ColorantLab(int a, int b, float l)](#ColorantLab-int-int-float-) | 初始化 `ColorantLab` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MIN_A](#MIN-A) | 最小 A 分量值 |
| [MAX_A](#MAX-A) | 最大 A 分量值 |
| [MIN_B](#MIN-B) | 最小 B 分量值 |
| [MAX_B](#MAX-B) | 最大 A 分量值 |
| [MIN_L](#MIN-L) | 最小 L 分量值 |
| [MAX_L](#MAX-L) | 最大 A 分量值 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getA()](#getA--) | 获取或设置 A 分量。 |
| [setA(int value)](#setA-int-) | 获取或设置 A 分量。 |
| [getB()](#getB--) | 获取或设置 B 分量。 |
| [setB(int value)](#setB-int-) | 获取或设置 B 分量。 |
| [getL()](#getL--) | 获取或设置 L 分量。 |
| [setL(float value)](#setL-float-) | 获取或设置 L 分量。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### ColorantLab() {#ColorantLab--}
```
public ColorantLab()
```


初始化 `ColorantLab` 类的新实例。

### ColorantLab(int a, int b, float l) {#ColorantLab-int-int-float-}
```
public ColorantLab(int a, int b, float l)
```


初始化 `ColorantLab` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | int | 一个组件。 |
| b | int | B 组件。 |
| l | float | L 组件。 |

### MIN_A {#MIN-A}
```
public static final int MIN_A
```


最小 A 分量值

### MAX_A {#MAX-A}
```
public static final int MAX_A
```


最大 A 分量值

### MIN_B {#MIN-B}
```
public static final int MIN_B
```


最小 B 分量值

### MAX_B {#MAX-B}
```
public static final int MAX_B
```


最大 A 分量值

### MIN_L {#MIN-L}
```
public static final float MIN_L
```


最小 L 分量值

### MAX_L {#MAX-L}
```
public static final float MAX_L
```


最大 A 分量值

### getA() {#getA--}
```
public int getA()
```


获取或设置 A 分量。

值：A 组件。

**Returns:**
int
### setA(int value) {#setA-int-}
```
public void setA(int value)
```


获取或设置 A 分量。

值：A 组件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getB() {#getB--}
```
public int getB()
```


获取或设置 B 分量。

值：B 组件。

**Returns:**
int
### setB(int value) {#setB-int-}
```
public void setB(int value)
```


获取或设置 B 分量。

值：B 组件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getL() {#getL--}
```
public float getL()
```


获取或设置 L 分量。

值：L 组件。

**Returns:**
float
### setL(float value) {#setL-float-}
```
public void setL(float value)
```


获取或设置 L 分量。

值：L 组件。

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
