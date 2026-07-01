---
title: "PointF"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示浮点数 x 和 y 坐标的有序对，用于定义二维平面上的一点。"
type: docs
weight: 87
url: /zh/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

表示浮点数 x 和 y 坐标的有序对，用于定义二维平面上的一点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 使用指定的坐标初始化 `com.aspose.imaging.PointF` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个 `com.aspose.imaging.PointF` 结构的新实例，其 `com.aspose.imaging.PointF.X` 和 `com.aspose.imaging.PointF.Y` 值设为零。 |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | 按给定的 `com.aspose.imaging.Size` 平移 `com.aspose.imaging.PointF`。 |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | 按给定的 `com.aspose.imaging.Size` 的相反方向平移 `com.aspose.imaging.PointF`。 |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | 按指定的 `com.aspose.imaging.SizeF` 平移 `com.aspose.imaging.PointF`。 |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | 按指定的 `com.aspose.imaging.SizeF` 的相反方向平移 `com.aspose.imaging.PointF`。 |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 比较两个 `com.aspose.imaging.PointF` 结构。 |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 确定指定点的坐标是否不相等。 |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | 按指定的 `com.aspose.imaging.Size` 平移给定的 `com.aspose.imaging.PointF`。 |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | 按指定尺寸的相反方向平移 `com.aspose.imaging.PointF`。 |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | 按指定的 `com.aspose.imaging.SizeF` 平移给定的 `com.aspose.imaging.PointF`。 |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | 按指定尺寸的相反方向平移 `com.aspose.imaging.PointF`。 |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | 获取指示此 `com.aspose.imaging.PointF` 是否为空的值。 |
| [getX()](#getX--) | 获取或设置此 `com.aspose.imaging.PointF` 的 x 坐标。 |
| [setX(float value)](#setX-float-) | 获取或设置此 `com.aspose.imaging.PointF` 的 x 坐标。 |
| [getY()](#getY--) | 获取或设置此 `com.aspose.imaging.PointF` 的 y 坐标。 |
| [setY(float value)](#setY-float-) | 获取或设置此 `com.aspose.imaging.PointF` 的 y 坐标。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 `com.aspose.imaging.PointF` 是否包含与指定的 `System.Object` 相同的坐标。 |
| [hashCode()](#hashCode--) | 返回此 `com.aspose.imaging.PointF` 结构的哈希码。 |
| [toString()](#toString--) | 将此 `com.aspose.imaging.PointF` 转换为可读的字符串。 |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


使用指定的坐标初始化 `com.aspose.imaging.PointF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 点的水平位置。 |
| y | float | 点的垂直位置。 |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


获取一个 `com.aspose.imaging.PointF` 结构的新实例，其 `com.aspose.imaging.PointF.X` 和 `com.aspose.imaging.PointF.Y` 值设为零。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


按给定的 `com.aspose.imaging.Size` 平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [Size](../../com.aspose.imaging/size) | 一个 `com.aspose.imaging.Size`，指定要添加到 `point` 坐标的两个数字。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


按给定的 `com.aspose.imaging.Size` 的相反方向平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [Size](../../com.aspose.imaging/size) | 一个 `com.aspose.imaging.Size`，指定要从 `point` 的 x 和 y 坐标中减去的数字。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


按指定的 `com.aspose.imaging.SizeF` 平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [SizeF](../../com.aspose.imaging/sizef) | 指定要添加到 `point` 的 x 和 y 坐标的数字的 `com.aspose.imaging.SizeF`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


按指定的 `com.aspose.imaging.SizeF` 的相反方向平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [SizeF](../../com.aspose.imaging/sizef) | 指定要从 `point` 坐标中减去的数字的 `com.aspose.imaging.SizeF`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


比较两个 `com.aspose.imaging.PointF` 结构。结果指定这两个 `com.aspose.imaging.PointF` 结构的 `com.aspose.imaging.PointF.X` 和 `com.aspose.imaging.PointF.Y` 属性的值是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | 要比较的第一个 `com.aspose.imaging.PointF`。 |
| point2 | [PointF](../../com.aspose.imaging/pointf) | 要比较的第二个 `com.aspose.imaging.PointF`。 |

**Returns:**
boolean - 如果第一个和第二个 `com.aspose.imaging.PointF` 结构的 `com.aspose.imaging.PointF.X` 和 `com.aspose.imaging.PointF.Y` 值相等，则为 True；否则为 false。
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


确定指定点的坐标是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | 要比较的第一个 `com.aspose.imaging.PointF`。 |
| point2 | [PointF](../../com.aspose.imaging/pointf) | 要比较的第二个 `com.aspose.imaging.PointF`。 |

**Returns:**
boolean - True 表示 `point1` 和 `point2` 的 `com.aspose.imaging.PointF.X` 与 `com.aspose.imaging.PointF.Y` 值不相等；否则为 false。
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


按指定的 `com.aspose.imaging.Size` 平移给定的 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [Size](../../com.aspose.imaging/size) | 指定要添加到 `point` 坐标的数字的 `com.aspose.imaging.Size`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


按指定尺寸的相反方向平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [Size](../../com.aspose.imaging/size) | 指定要从 `point` 坐标中减去的数字的 `com.aspose.imaging.Size`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


按指定的 `com.aspose.imaging.SizeF` 平移给定的 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [SizeF](../../com.aspose.imaging/sizef) | 指定要添加到 `point` 坐标的数字的 `com.aspose.imaging.SizeF`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


按指定尺寸的相反方向平移 `com.aspose.imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `com.aspose.imaging.PointF`。 |
| size | [SizeF](../../com.aspose.imaging/sizef) | 指定要从 `point` 坐标中减去的数字的 `com.aspose.imaging.SizeF`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取指示此 `com.aspose.imaging.PointF` 是否为空的值。

**Returns:**
boolean - 如果 `com.aspose.imaging.PointF.X` 和 `com.aspose.imaging.PointF.Y` 均为 0，则为 True；否则为 false。
### getX() {#getX--}
```
public float getX()
```


获取或设置此 `com.aspose.imaging.PointF` 的 x 坐标。

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


获取或设置此 `com.aspose.imaging.PointF` 的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getY() {#getY--}
```
public float getY()
```


获取或设置此 `com.aspose.imaging.PointF` 的 y 坐标。

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


获取或设置此 `com.aspose.imaging.PointF` 的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定此 `com.aspose.imaging.PointF` 是否包含与指定的 `System.Object` 相同的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
boolean - 如果 `obj` 是 `com.aspose.imaging.PointF` 且其坐标与此 `com.aspose.imaging.Point` 相同，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 `com.aspose.imaging.PointF` 结构的哈希码。

**Returns:**
int - 指定此 `com.aspose.imaging.PointF` 结构的哈希值的整数。
### toString() {#toString--}
```
public String toString()
```


将此 `com.aspose.imaging.PointF` 转换为可读的字符串。

**Returns:**
java.lang.String - 表示此 `com.aspose.imaging.PointF` 的字符串。
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
