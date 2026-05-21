---
title: "RectangleF"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "存储表示矩形位置和大小的四个浮点数。"
type: docs
weight: 94
url: /zh/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

存储表示矩形位置和大小的四个浮点数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 使用指定的位置和大小初始化 `com.aspose.imaging.RectangleF` 结构的新实例。 |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | 使用指定的位置和大小初始化 `com.aspose.imaging.RectangleF` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个新的 `com.aspose.imaging.RectangleF` 结构实例，其 `com.aspose.imaging.RectangleF.X`、`com.aspose.imaging.RectangleF.Y`、`com.aspose.imaging.RectangleF.Width` 和 `com.aspose.imaging.RectangleF.Height` 的值均为零。 |
| [getLocation()](#getLocation--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的坐标。 |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的坐标。 |
| [getSize()](#getSize--) | 获取或设置此 `com.aspose.imaging.RectangleF` 的大小。 |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | 获取或设置此 `com.aspose.imaging.RectangleF` 的大小。 |
| [getX()](#getX--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 X 坐标。 |
| [setX(float value)](#setX-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 X 坐标。 |
| [getY()](#getY--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 Y 坐标。 |
| [setY(float value)](#setY-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 Y 坐标。 |
| [getWidth()](#getWidth--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构的宽度。 |
| [setWidth(float value)](#setWidth-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构的宽度。 |
| [getHeight()](#getHeight--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构的高度。 |
| [setHeight(float value)](#setHeight-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构的高度。 |
| [getLeft()](#getLeft--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左边缘的 X 坐标。 |
| [setLeft(float value)](#setLeft-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构左边缘的 X 坐标。 |
| [getTop()](#getTop--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构顶部边缘的 Y 坐标。 |
| [setTop(float value)](#setTop-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构顶部边缘的 Y 坐标。 |
| [getRight()](#getRight--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.X` 与 `com.aspose.imaging.RectangleF.Width` 的和所对应的 X 坐标。 |
| [setRight(float value)](#setRight-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.X` 与 `com.aspose.imaging.RectangleF.Width` 的和所对应的 X 坐标。 |
| [getBottom()](#getBottom--) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.Y` 与 `com.aspose.imaging.RectangleF.Height` 的和所对应的 Y 坐标。 |
| [setBottom(float value)](#setBottom-float-) | 获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.Y` 与 `com.aspose.imaging.RectangleF.Height` 的和所对应的 Y 坐标。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `com.aspose.imaging.RectangleF` 的 `com.aspose.imaging.RectangleF.Width` 或 `com.aspose.imaging.RectangleF.Height` 属性是否为零。 |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 根据指定的两个点创建一个新的 `Rectangle`。 |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | 创建并返回指定的 `com.aspose.imaging.RectangleF` 结构的膨胀副本。 |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | 返回一个表示两个矩形交集的 `com.aspose.imaging.RectangleF` 结构。 |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | 创建能够包含两个矩形（形成并集）的最小可能的第三个矩形。 |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | 测试两个 `com.aspose.imaging.RectangleF` 结构的位置信息和大小是否相等。 |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | 测试两个 `com.aspose.imaging.RectangleF` 结构的位置信息或大小是否不同。 |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | 实现运算符 \\*。 |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | 实现运算符 /。 |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | 将指定的 `com.aspose.imaging.Rectangle` 结构转换为 `com.aspose.imaging.RectangleF` 结构。 |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | 使用指定位置的左上角和右下角创建一个 `com.aspose.imaging.RectangleF` 结构。 |
| [normalize()](#normalize--) | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [contains(float x, float y)](#contains-float-float-) | 确定指定的点是否位于此 `com.aspose.imaging.RectangleF` 结构内部。 |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | 确定指定的点是否位于此 `com.aspose.imaging.RectangleF` 结构内部。 |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | 确定由 `rect` 表示的矩形区域是否完全包含在此 `com.aspose.imaging.RectangleF` 结构中。 |
| [inflate(float x, float y)](#inflate-float-float-) | 按指定量膨胀此 `com.aspose.imaging.RectangleF` 结构。 |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | 按指定量膨胀此 `com.aspose.imaging.RectangleF`。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | 用自身与指定的 `com.aspose.imaging.RectangleF` 结构的交集替换此 `com.aspose.imaging.RectangleF` 结构。 |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | 确定此矩形是否与 `rect` 相交。 |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | 按指定量调整此矩形的位置。 |
| [offset(float x, float y)](#offset-float-float-) | 按指定量调整此矩形的位置。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试 `obj` 是否为具有与此 `com.aspose.imaging.RectangleF` 相同位置和大小的 `com.aspose.imaging.RectangleF`。 |
| [hashCode()](#hashCode--) | 获取此 `com.aspose.imaging.RectangleF` 结构的哈希码。 |
| [toString()](#toString--) | 将此 `com.aspose.imaging.RectangleF` 的属性转换为可读的字符串。 |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


使用指定的位置和大小初始化 `com.aspose.imaging.RectangleF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 矩形左上角的 x 坐标。 |
| y | float | 矩形左上角的 y 坐标。 |
| 宽度 | float | 矩形的宽度。 |
| 高度 | float | 矩形的高度。 |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


使用指定的位置和大小初始化 `com.aspose.imaging.RectangleF` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | 一个表示矩形区域左上角的 `com.aspose.imaging.PointF`。 |
| size | [SizeF](../../com.aspose.imaging/sizef) | 一个表示矩形区域宽度和高度的 `com.aspose.imaging.SizeF`。 |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


获取一个新的 `com.aspose.imaging.RectangleF` 结构实例，其 `com.aspose.imaging.RectangleF.X`、`com.aspose.imaging.RectangleF.Y`、`com.aspose.imaging.RectangleF.Width` 和 `com.aspose.imaging.RectangleF.Height` 的值均为零。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的坐标。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


获取或设置此 `com.aspose.imaging.RectangleF` 的大小。

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 X 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构左上角的 x 坐标。
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 Y 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构左上角的 y 坐标。
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左上角的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构的宽度。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构的宽度。
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构的高度。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构的高度。
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左边缘的 X 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构左边缘的 x 坐标。
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构左边缘的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构顶部边缘的 Y 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构上边缘的 y 坐标。
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构顶部边缘的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.X` 与 `com.aspose.imaging.RectangleF.Width` 的和所对应的 X 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构的 `com.aspose.imaging.RectangleF.X` 与 `com.aspose.imaging.RectangleF.Width` 的和对应的 x 坐标。
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.X` 与 `com.aspose.imaging.RectangleF.Width` 的和所对应的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.Y` 与 `com.aspose.imaging.RectangleF.Height` 的和所对应的 Y 坐标。

**Returns:**
float - 此 `com.aspose.imaging.RectangleF` 结构的 `com.aspose.imaging.RectangleF.Y` 与 `com.aspose.imaging.RectangleF.Height` 的和对应的 y 坐标。
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


获取或设置此 `com.aspose.imaging.RectangleF` 结构中 `com.aspose.imaging.RectangleF.Y` 与 `com.aspose.imaging.RectangleF.Height` 的和所对应的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `com.aspose.imaging.RectangleF` 的 `com.aspose.imaging.RectangleF.Width` 或 `com.aspose.imaging.RectangleF.Height` 属性是否为零。

**Returns:**
boolean - 如果此 `com.aspose.imaging.RectangleF` 的 `com.aspose.imaging.RectangleF.Width` 或 `com.aspose.imaging.RectangleF.Height` 属性的值为零，则此属性返回 true；否则返回 false。
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


从指定的两个点创建一个新的 `Rectangle`。创建的 `Rectangle` 的两个顶点将等于传入的 `point1` 和 `point2`。这些通常是相对的顶点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | 新矩形的第一个 `Point`。 |
| point2 | [PointF](../../com.aspose.imaging/pointf) | 新矩形的第二个 `Point`。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


创建并返回指定 `com.aspose.imaging.RectangleF` 结构的膨胀副本。副本按指定的量进行膨胀。原始矩形保持不变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要复制的 `com.aspose.imaging.RectangleF`。此矩形不会被修改。 |
| x | float | 水平膨胀矩形副本的量。 |
| y | float | 垂直膨胀矩形副本的量。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


返回表示两个矩形交集的 `com.aspose.imaging.RectangleF` 结构。如果没有交集，则返回一个空的 `com.aspose.imaging.RectangleF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | 第一个用于交集的矩形。 |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | 第二个用于交集的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


创建能够包含两个矩形（形成并集）的最小可能的第三个矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | 第一个用于并集的矩形。 |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | 第二个用于并集的矩形。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


测试两个 `com.aspose.imaging.RectangleF` 结构的位置信息和大小是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | 等号运算符左侧的 `com.aspose.imaging.RectangleF` 结构。 |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | 等号运算符右侧的 `com.aspose.imaging.RectangleF` 结构。 |

**Returns:**
boolean - 如果两个指定的 `com.aspose.imaging.RectangleF` 结构的 `com.aspose.imaging.RectangleF.X`、`com.aspose.imaging.RectangleF.Y`、`com.aspose.imaging.RectangleF.Width` 和 `com.aspose.imaging.RectangleF.Height` 属性相等，则此运算符返回 true。
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


测试两个 `com.aspose.imaging.RectangleF` 结构的位置信息或大小是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | 不等号运算符左侧的 `com.aspose.imaging.RectangleF` 结构。 |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | 不等号运算符右侧的 `com.aspose.imaging.RectangleF` 结构。 |

**Returns:**
boolean - 如果两个 `com.aspose.imaging.RectangleF` 结构的 `com.aspose.imaging.RectangleF.X`、`com.aspose.imaging.RectangleF.Y`、`com.aspose.imaging.RectangleF.Width` 或 `com.aspose.imaging.RectangleF.Height` 属性中任意一个不相等，则此运算符返回 true；否则返回 false。
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


实现运算符 \\*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 矩形。 |
| 乘数 | float | 乘数。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


实现运算符 /。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | 矩形。 |
| 除数 | float | 除数。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


将指定的 `com.aspose.imaging.Rectangle` 结构转换为 `com.aspose.imaging.RectangleF` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 要转换的 `com.aspose.imaging.Rectangle` 结构。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


使用指定位置的左上角和右下角创建一个 `com.aspose.imaging.RectangleF` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | float | 矩形区域左上角的 x 坐标。 |
| 上 | float | 矩形区域左上角的 y 坐标。 |
| 右 | float | 矩形区域右下角的 x 坐标。 |
| 下 | float | 矩形区域右下角的 y 坐标。 |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


确定指定的点是否位于此 `com.aspose.imaging.RectangleF` 结构内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 要测试的点的 x 坐标。 |
| y | float | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 此方法返回 true，如果由 `x` 和 `y` 定义的点位于此 `com.aspose.imaging.RectangleF` 结构内；否则返回 false。
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


确定指定的点是否位于此 `com.aspose.imaging.RectangleF` 结构内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要测试的 `com.aspose.imaging.PointF`。 |

**Returns:**
boolean - 此方法返回 true，如果 `point` 参数表示的点位于此 `com.aspose.imaging.RectangleF` 结构内；否则返回 false。
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


确定由 `rect` 表示的矩形区域是否完全包含在此 `com.aspose.imaging.RectangleF` 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要测试的 `com.aspose.imaging.RectangleF`。 |

**Returns:**
boolean - 此方法返回 true，如果 `rect` 表示的矩形区域完全位于此 `com.aspose.imaging.RectangleF` 表示的矩形区域内；否则返回 false。
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


按指定量膨胀此 `com.aspose.imaging.RectangleF` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 水平膨胀此 `com.aspose.imaging.RectangleF` 结构的量。 |
| y | float | 垂直膨胀此 `com.aspose.imaging.RectangleF` 结构的量。 |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


按指定量膨胀此 `com.aspose.imaging.RectangleF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | 膨胀此矩形的量。 |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


用自身与指定的 `com.aspose.imaging.RectangleF` 结构的交集替换此 `com.aspose.imaging.RectangleF` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要相交的矩形。 |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


确定此矩形是否与 `rect` 相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 要测试的矩形。 |

**Returns:**
boolean - 此方法返回 true，如果存在任何交集。
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | 位移位置的量。 |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 水平偏移位置的量。 |
| y | float | 垂直偏移位置的量。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试 `obj` 是否为具有与此 `com.aspose.imaging.RectangleF` 相同位置和大小的 `com.aspose.imaging.RectangleF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
boolean - 如果 `obj` 是 `com.aspose.imaging.RectangleF`，并且其 X、Y、Width 和 Height 属性等于此 `com.aspose.imaging.RectangleF` 的相应属性，则此方法返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此 `com.aspose.imaging.RectangleF` 结构的哈希码。

**Returns:**
int - 此 `com.aspose.imaging.RectangleF` 的哈希码。
### toString() {#toString--}
```
public String toString()
```


将此 `com.aspose.imaging.RectangleF` 的属性转换为可读的字符串。

**Returns:**
java.lang.String - 包含此 `com.aspose.imaging.RectangleF` 结构的位置、宽度和高度的字符串。
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
