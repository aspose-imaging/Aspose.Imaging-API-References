---
title: "大小"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示大小。"
type: docs
weight: 104
url: /zh/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

表示大小。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | 从指定的 `Aspose.Imaging.Point` 初始化 `Aspose.Imaging.Size` 结构的新实例。 |
| [Size(int width, int height)](#Size-int-int-) | 从指定的尺寸初始化 `Aspose.Imaging.Size` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个新的 `Aspose.Imaging.Size` 结构实例，其 `Aspose.Imaging.Size.Width` 和 `Aspose.Imaging.Size.Height` 值设置为零。 |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | 将指定的 `Aspose.Imaging.Size` 转换为 `Aspose.Imaging.SizeF`。 |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 将一个 `Aspose.Imaging.Size` 结构的宽度和高度添加到另一个 `Aspose.Imaging.Size` 结构的宽度和高度。 |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 从另一个 `Aspose.Imaging.Size` 结构的宽度和高度中减去一个 `Aspose.Imaging.Size` 结构的宽度和高度。 |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 测试两个 `Aspose.Imaging.Size` 结构是否相等。 |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 测试两个 `Aspose.Imaging.Size` 结构是否不同。 |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | 将指定的 `Aspose.Imaging.Size` 转换为 `Aspose.Imaging.Point`。 |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 将一个 `Aspose.Imaging.Size` 结构的宽度和高度添加到另一个 `Aspose.Imaging.Size` 结构的宽度和高度。 |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | 通过将 `Aspose.Imaging.SizeF` 结构的值向上取整到下一个更高的整数，将其转换为 `Aspose.Imaging.Size` 结构。 |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | 从另一个 `Aspose.Imaging.Size` 结构的宽度和高度中减去一个 `Aspose.Imaging.Size` 结构的宽度和高度。 |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | 通过将 `Aspose.Imaging.SizeF` 结构的值截断为下一个更低的整数，将其转换为 `Aspose.Imaging.Size` 结构。 |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | 通过将 `Aspose.Imaging.SizeF` 结构的值四舍五入到最近的整数，将其转换为 `Aspose.Imaging.Size` 结构。 |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `Aspose.Imaging.Size` 的宽度和高度是否为 0。 |
| [getWidth()](#getWidth--) | 获取或设置此 `Aspose.Imaging.Size` 的水平分量。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置此 `Aspose.Imaging.Size` 的水平分量。 |
| [getHeight()](#getHeight--) | 获取或设置此 `Aspose.Imaging.Size` 的垂直分量。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置此 `Aspose.Imaging.Size` 的垂直分量。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试以确定指定的对象是否为具有与此 `Aspose.Imaging.Size` 相同尺寸的 `Aspose.Imaging.Size`。 |
| [hashCode()](#hashCode--) | 返回此 `Aspose.Imaging.Size` 结构的哈希码。 |
| [toString()](#toString--) | 创建一个可读的字符串，表示此 `Aspose.Imaging.Size`。 |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


从指定的 `Aspose.Imaging.Point` 初始化 `Aspose.Imaging.Size` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 用于初始化此 `Aspose.Imaging.Size` 的 `Aspose.Imaging.Point`。 |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


从指定的尺寸初始化 `Aspose.Imaging.Size` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 新 `Aspose.Imaging.Size` 的宽度分量。 |
| 高度 | int | 新 `Aspose.Imaging.Size` 的高度分量。 |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


获取一个新的 `Aspose.Imaging.Size` 结构实例，其 `Aspose.Imaging.Size.Width` 和 `Aspose.Imaging.Size.Height` 值设置为零。

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


将指定的 `Aspose.Imaging.Size` 转换为 `Aspose.Imaging.SizeF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | 要转换的 `Aspose.Imaging.Size`。 |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


将一个 `Aspose.Imaging.Size` 结构的宽度和高度添加到另一个 `Aspose.Imaging.Size` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 要相加的第一个 `Aspose.Imaging.Size`。 |
| size2 | [Size](../../com.aspose.imaging/size) | 要相加的第二个 `Aspose.Imaging.Size`。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


从另一个 `Aspose.Imaging.Size` 结构的宽度和高度中减去一个 `Aspose.Imaging.Size` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 减法运算符左侧的 `Aspose.Imaging.Size` 结构。 |
| size2 | [Size](../../com.aspose.imaging/size) | 减法运算符右侧的 `Aspose.Imaging.Size` 结构。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


测试两个 `Aspose.Imaging.Size` 结构是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 等于运算符左侧的 `Aspose.Imaging.Size` 结构。 |
| size2 | [Size](../../com.aspose.imaging/size) | 等于运算符右侧的 `Aspose.Imaging.Size` 结构。 |

**Returns:**
布尔型 - 如果 `size1` 和 `size2` 的宽度和高度相等则为 True；否则为 false。
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


测试两个 `Aspose.Imaging.Size` 结构是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 不等于运算符左侧的 `Aspose.Imaging.Size` 结构。 |
| size2 | [Size](../../com.aspose.imaging/size) | 不等于运算符右侧的 `Aspose.Imaging.Size` 结构。 |

**Returns:**
布尔型 - 如果 `size1` 和 `size2` 在宽度或高度上任一不同则为 True；如果 `size1` 和 `size2` 相等则为 false。
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


将指定的 `Aspose.Imaging.Size` 转换为 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | 要转换的 `Aspose.Imaging.Size`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


将一个 `Aspose.Imaging.Size` 结构的宽度和高度添加到另一个 `Aspose.Imaging.Size` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 要相加的第一个 `Aspose.Imaging.Size`。 |
| size2 | [Size](../../com.aspose.imaging/size) | 要相加的第二个 `Aspose.Imaging.Size`。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


通过将 `Aspose.Imaging.SizeF` 结构的值向上取整到下一个更高的整数，将其转换为 `Aspose.Imaging.Size` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 要转换的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


从另一个 `Aspose.Imaging.Size` 结构的宽度和高度中减去一个 `Aspose.Imaging.Size` 结构的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | 减法运算符左侧的 `Aspose.Imaging.Size` 结构。 |
| size2 | [Size](../../com.aspose.imaging/size) | 减法运算符右侧的 `Aspose.Imaging.Size` 结构。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


通过将 `Aspose.Imaging.SizeF` 结构的值截断为下一个更低的整数，将其转换为 `Aspose.Imaging.Size` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 要转换的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


通过将 `Aspose.Imaging.SizeF` 结构的值四舍五入到最近的整数，将其转换为 `Aspose.Imaging.Size` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 要转换的 `Aspose.Imaging.SizeF` 结构。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `Aspose.Imaging.Size` 的宽度和高度是否为 0。

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置此 `Aspose.Imaging.Size` 的水平分量。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置此 `Aspose.Imaging.Size` 的水平分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置此 `Aspose.Imaging.Size` 的垂直分量。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置此 `Aspose.Imaging.Size` 的垂直分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试以确定指定的对象是否为具有与此 `Aspose.Imaging.Size` 相同尺寸的 `Aspose.Imaging.Size`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
布尔型 - 如果 `obj` 是 `Aspose.Imaging.Size` 且其宽度和高度与此 `Aspose.Imaging.Size` 相同则为 True；否则为 false。
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


创建一个可读的字符串，表示此 `Aspose.Imaging.Size`。

**Returns:**
java.lang.String - 表示此 `Aspose.Imaging.Size` 的字符串。
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
