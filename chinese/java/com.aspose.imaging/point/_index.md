---
title: "Point"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示整数 x、y 坐标的有序对，用于定义二维平面中的一点。"
type: docs
weight: 86
url: /zh/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

表示整数 x、y 坐标的有序对，用于定义二维平面中的一点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 使用指定的坐标初始化 `Aspose.Imaging.Point` 结构的新实例。 |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | 从 `Aspose.Imaging.Size` 结构初始化 `Aspose.Imaging.Point` 结构的新实例。 |
| [Point(int dw)](#Point-int-) | 使用整数值指定的坐标初始化 `Aspose.Imaging.Point` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个 `Aspose.Imaging.Point` 结构的新实例，其 `Aspose.Imaging.Point.X` 和 `Aspose.Imaging.Point.Y` 值均为零。 |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 将指定的 `Aspose.Imaging.Size` 添加到指定的 `Aspose.Imaging.Point`。 |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 返回从指定的 `Aspose.Imaging.Point` 中减去指定的 `Aspose.Imaging.Size` 的结果。 |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | 通过将 `Aspose.Imaging.PointF` 的值向上取整为下一个更大的整数，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point`。 |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | 通过将 `Aspose.Imaging.Point` 的值四舍五入到最近的整数，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point` 对象。 |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | 通过截断 `Aspose.Imaging.Point` 的值，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point`。 |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 按给定的 `Aspose.Imaging.Size` 平移 `Aspose.Imaging.Point`。 |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 按给定的 `Aspose.Imaging.Size` 的负值平移 `Aspose.Imaging.Point`。 |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 比较两个 `Aspose.Imaging.Point` 对象。 |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 比较两个 `Aspose.Imaging.Point` 对象。 |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | 将指定的 `Aspose.Imaging.Point` 结构转换为 `Aspose.Imaging.Size` 结构。 |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | 将指定的 `Point` 结构转换为 `PointF` 结构。 |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | 将打包在 long 对象中的 Point 对象解构为单独的 X 和 Y 整数值。 |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `Aspose.Imaging.Point` 是否为空。 |
| [getX()](#getX--) | 获取或设置此 `Aspose.Imaging.Point` 的 x 坐标。 |
| [setX(int value)](#setX-int-) | 获取或设置此 `Aspose.Imaging.Point` 的 x 坐标。 |
| [getY()](#getY--) | 获取或设置此 `Aspose.Imaging.Point` 的 y 坐标。 |
| [setY(int value)](#setY-int-) | 获取或设置此 `Aspose.Imaging.Point` 的 y 坐标。 |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | 按指定的 `Aspose.Imaging.Point` 平移此 `Aspose.Imaging.Point`。 |
| [offset(int dx, int dy)](#offset-int-int-) | 按指定的量平移此 `Aspose.Imaging.Point`。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定此 `Aspose.Imaging.Point` 是否包含与指定的 `System.Object` 相同的坐标。 |
| [hashCode()](#hashCode--) | 返回此 `Aspose.Imaging.Point` 的哈希码。 |
| [toLong()](#toLong--) | 将此 Point 转换为单个 long 值，其中高位和低位分别包含 X 和 Y 坐标。 |
| [toString()](#toString--) | 将此 `Aspose.Imaging.Point` 转换为可读的字符串。 |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


使用指定的坐标初始化 `Aspose.Imaging.Point` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 点的水平位置。 |
| y | int | 点的垂直位置。 |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


从 `Aspose.Imaging.Size` 结构初始化 `Aspose.Imaging.Point` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | 包含新的点坐标。 |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


使用整数值指定的坐标初始化 `Aspose.Imaging.Point` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dw | int | 一个 32 位整数，指定新点的坐标。 |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


获取一个 `Aspose.Imaging.Point` 结构的新实例，其 `Aspose.Imaging.Point.X` 和 `Aspose.Imaging.Point.Y` 值均为零。

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


将指定的 `Aspose.Imaging.Size` 添加到指定的 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要添加到的 `Aspose.Imaging.Point`。 |
| size | [Size](../../com.aspose.imaging/size) | 要添加到 `point` 的 `Aspose.Imaging.Size`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


返回从指定的 `Aspose.Imaging.Point` 中减去指定的 `Aspose.Imaging.Size` 的结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要被减去的 `Aspose.Imaging.Point`。 |
| size | [Size](../../com.aspose.imaging/size) | 要从 `point` 中减去的 `Aspose.Imaging.Size`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


通过将 `Aspose.Imaging.PointF` 的值向上取整为下一个更大的整数，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `Aspose.Imaging.PointF`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


通过将 `Aspose.Imaging.Point` 的值四舍五入到最近的整数，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point` 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `Aspose.Imaging.PointF`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


通过截断 `Aspose.Imaging.Point` 的值，将指定的 `Aspose.Imaging.PointF` 转换为 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `Aspose.Imaging.PointF`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


按给定的 `Aspose.Imaging.Size` 平移 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要平移的 `Aspose.Imaging.Point`。 |
| size | [Size](../../com.aspose.imaging/size) | 指定要加到 `point` 坐标的数字对的 `Aspose.Imaging.Size`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


按给定的 `Aspose.Imaging.Size` 的负值平移 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要平移的 `Aspose.Imaging.Point`。 |
| size | [Size](../../com.aspose.imaging/size) | 指定要从 `point` 坐标中减去的数字对的 `Aspose.Imaging.Size`。 |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


比较两个 `Aspose.Imaging.Point` 对象。结果指示这两个 `Aspose.Imaging.Point` 对象的 `Aspose.Imaging.Point.X` 和 `Aspose.Imaging.Point.Y` 属性的值是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | 要比较的第一个 `Aspose.Imaging.Point`。 |
| point2 | [Point](../../com.aspose.imaging/point) | 要比较的第二个 `Aspose.Imaging.Point`。 |

**Returns:**
布尔值 - 如果 `point1` 和 `point2` 的 `Aspose.Imaging.Point.X` 和 `Aspose.Imaging.Point.Y` 值相等，则为 True；否则为 false。
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


比较两个 `Aspose.Imaging.Point` 对象。结果指示这两个 `Aspose.Imaging.Point` 对象的 `Aspose.Imaging.Point.X` 或 `Aspose.Imaging.Point.Y` 属性的值是否不相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | 要比较的第一个 `Aspose.Imaging.Point`。 |
| point2 | [Point](../../com.aspose.imaging/point) | 要比较的第二个 `Aspose.Imaging.Point`。 |

**Returns:**
布尔值 - 如果 `point1` 和 `point2` 的 `Aspose.Imaging.Point.X` 属性或 `Aspose.Imaging.Point.Y` 属性的值任一不同，则为 True；否则为 false。
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


将指定的 `Aspose.Imaging.Point` 结构转换为 `Aspose.Imaging.Size` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要转换的 `Aspose.Imaging.Point`。 |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


将指定的 `Point` 结构转换为 `PointF` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要转换的 `Point`。 |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


将打包在 long 对象中的 Point 对象解构为单独的 X 和 Y 整数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| packedPoint | long | 打包为单个 long 值的 Point 对象。 |
| x | int[] | 从打包的 Point 中提取的 X 值。 |
| y | int[] | 从打包的 Point 中提取的 Y 值。 |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `Aspose.Imaging.Point` 是否为空。

**Returns:**
布尔值 - 如果 `Aspose.Imaging.Point.X` 和 `Aspose.Imaging.Point.Y` 均为 0，则为 True；否则为 false。
### getX() {#getX--}
```
public int getX()
```


获取或设置此 `Aspose.Imaging.Point` 的 x 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


获取或设置此 `Aspose.Imaging.Point` 的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


获取或设置此 `Aspose.Imaging.Point` 的 y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


获取或设置此 `Aspose.Imaging.Point` 的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


按指定的 `Aspose.Imaging.Point` 平移此 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 用于偏移此 `Aspose.Imaging.Point` 的 `Aspose.Imaging.Point`。 |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


按指定的量平移此 `Aspose.Imaging.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dx | int | 用于偏移 x 坐标的量。 |
| dy | int | 用于偏移 y 坐标的量。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定此 `Aspose.Imaging.Point` 是否包含与指定的 `System.Object` 相同的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
布尔值 - 如果 `obj` 是 `Aspose.Imaging.Point` 并且其坐标与此 `Aspose.Imaging.Point` 相同，则为 True。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 `Aspose.Imaging.Point` 的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### toLong() {#toLong--}
```
public final long toLong()
```


将此 Point 转换为单个 long 值，其中高位和低位分别包含 X 和 Y 坐标。

**Returns:**
long - 打包为单个 long 值的 Point 对象。
### toString() {#toString--}
```
public String toString()
```


将此 `Aspose.Imaging.Point` 转换为可读的字符串。

**Returns:**
java.lang.String - 表示此实例的 `System.String`。
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
