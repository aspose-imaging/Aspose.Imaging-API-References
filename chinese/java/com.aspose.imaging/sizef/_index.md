---
title: "SizeF"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "存储一对有序的浮点数，通常是矩形的宽度和高度。"
type: docs
weight: 105
url: /zh/java/com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

存储一对有序的浮点数，通常是矩形的宽度和高度。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | 从指定的 `Aspose.Imaging.SizeF` 初始化 `Aspose.Imaging.SizeF` 结构的新实例。 |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | 从指定的 `Aspose.Imaging.PointF` 初始化 `Aspose.Imaging.SizeF` 结构的新实例。 |
| [SizeF(float width, float height)](#SizeF-float-float-) | 从指定的尺寸初始化 `Aspose.Imaging.SizeF` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个新的 `Aspose.Imaging.SizeF` 结构实例，其 `Aspose.Imaging.SizeF.Width` 和 `Aspose.Imaging.SizeF.Height` 值均为零。 |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 将一个 `Aspose.Imaging.SizeF` 结构的宽度和高度加到另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度上。 |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 从另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度中减去一个 `Aspose.Imaging.SizeF` 结构的宽度和高度。 |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 测试两个 `Aspose.Imaging.SizeF` 结构是否相等。 |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 测试两个 `Aspose.Imaging.SizeF` 结构是否不同。 |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | 将指定的 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.PointF`。 |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 将一个 `Aspose.Imaging.SizeF` 结构的宽度和高度加到另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度上。 |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | 从另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度中减去一个 `Aspose.Imaging.SizeF` 结构的宽度和高度。 |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `Aspose.Imaging.SizeF` 的宽度和高度是否为零。 |
| [getWidth()](#getWidth--) | 获取或设置此 `Aspose.Imaging.SizeF` 的水平分量。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置此 `Aspose.Imaging.SizeF` 的水平分量。 |
| [getHeight()](#getHeight--) | 获取或设置此 `Aspose.Imaging.SizeF` 的垂直分量。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置此 `Aspose.Imaging.SizeF` 的垂直分量。 |
| [toPointF()](#toPointF--) | 将 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.PointF`。 |
| [toSize()](#toSize--) | 将 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.Size` 结构，使用截断后的尺寸值。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为具有与此 `Aspose.Imaging.SizeF` 相同尺寸的 `Aspose.Imaging.SizeF`。 |
| [hashCode()](#hashCode--) | 返回此 `Aspose.Imaging.Size` 结构的哈希码。 |
| [toString()](#toString--) | 创建一个可读的字符串，表示此 `Aspose.Imaging.SizeF`。 |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


从指定的 `Aspose.Imaging.SizeF` 初始化 `Aspose.Imaging.SizeF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 用于创建新 `Aspose.Imaging.SizeF` 的 `Aspose.Imaging.SizeF`。 |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


从指定的 `Aspose.Imaging.PointF` 初始化 `Aspose.Imaging.SizeF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 用于初始化此 `Aspose.Imaging.SizeF` 的 `Aspose.Imaging.PointF`。 |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


从指定的尺寸初始化 `Aspose.Imaging.SizeF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | float | 新 `Aspose.Imaging.SizeF` 的宽度分量。 |
| 高度 | float | 新 `Aspose.Imaging.SizeF` 的高度分量。 |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


获取一个新的 `Aspose.Imaging.SizeF` 结构实例，其 `Aspose.Imaging.SizeF.Width` 和 `Aspose.Imaging.SizeF.Height` 值均为零。

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


将一个 `Aspose.Imaging.SizeF` 结构的宽度和高度加到另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 要相加的第一个 `Aspose.Imaging.SizeF`。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 第二个要添加的 `Aspose.Imaging.SizeF`。 |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


从另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度中减去一个 `Aspose.Imaging.SizeF` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 在减法运算符左侧的 `Aspose.Imaging.SizeF`。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 在减法运算符右侧的 `Aspose.Imaging.SizeF`。 |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


测试两个 `Aspose.Imaging.SizeF` 结构是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 在等号运算符左侧的 `Aspose.Imaging.SizeF` 结构。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 在等号运算符右侧的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
boolean - 如果 `size1` 和 `size2` 的宽度和高度相等，则此运算符返回 true；否则返回 false。
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


测试两个 `Aspose.Imaging.SizeF` 结构是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 在不等号运算符左侧的 `Aspose.Imaging.SizeF` 结构。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 在不等号运算符右侧的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
boolean - 如果 `size1` 和 `size2` 在宽度或高度任一方面不同，则此运算符返回 true；如果 `size1` 和 `size2` 相等，则返回 false。
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


将指定的 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 待转换的 `Aspose.Imaging.SizeF` 结构 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


将一个 `Aspose.Imaging.SizeF` 结构的宽度和高度加到另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度上。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 要相加的第一个 `Aspose.Imaging.SizeF`。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 第二个要添加的 `Aspose.Imaging.SizeF`。 |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


从另一个 `Aspose.Imaging.SizeF` 结构的宽度和高度中减去一个 `Aspose.Imaging.SizeF` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | 在减法运算符左侧的 `Aspose.Imaging.SizeF` 结构。 |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | 在减法运算符右侧的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `Aspose.Imaging.SizeF` 的宽度和高度是否为零。

**Returns:**
boolean - 当此 `Aspose.Imaging.SizeF` 的宽度和高度均为零时，此属性返回 true；否则返回 false。
### getWidth() {#getWidth--}
```
public float getWidth()
```


获取或设置此 `Aspose.Imaging.SizeF` 的水平分量。

**Returns:**
float - 此 `Aspose.Imaging.SizeF` 的水平分量，通常以像素为单位。
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


获取或设置此 `Aspose.Imaging.SizeF` 的水平分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


获取或设置此 `Aspose.Imaging.SizeF` 的垂直分量。

**Returns:**
float - 此 `Aspose.Imaging.SizeF` 的垂直分量，通常以像素为单位。
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


获取或设置此 `Aspose.Imaging.SizeF` 的垂直分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### toPointF() {#toPointF--}
```
public PointF toPointF()
```


将 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.PointF`。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


将 `Aspose.Imaging.SizeF` 转换为 `Aspose.Imaging.Size` 结构，使用截断后的尺寸值。

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为具有与此 `Aspose.Imaging.SizeF` 相同尺寸的 `Aspose.Imaging.SizeF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
boolean - 如果 `obj` 是 `Aspose.Imaging.SizeF` 且其宽度和高度与此 `Aspose.Imaging.SizeF` 相同，则此方法返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 `Aspose.Imaging.Size` 结构的哈希码。

**Returns:**
整数型 - 指定此 `Aspose.Imaging.Size` 结构的哈希值的整数。
### toString() {#toString--}
```
public String toString()
```


创建一个可读的字符串，表示此 `Aspose.Imaging.SizeF`。

**Returns:**
java.lang.String - 表示此 `Aspose.Imaging.SizeF` 的字符串。
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
