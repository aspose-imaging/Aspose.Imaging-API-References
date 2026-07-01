---
title: "矩形"
second_title: "Aspose.Imaging for Java API 参考"
description: "存储表示矩形位置和大小的四个整数。"
type: docs
weight: 93
url: /zh/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

存储表示矩形位置和大小的四个整数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 使用指定的位置和大小初始化 `com.aspose.imaging.Rectangle` 结构的新实例。 |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 使用指定的位置和大小初始化 `com.aspose.imaging.Rectangle` 结构的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEmpty()](#getEmpty--) | 获取一个 `com.aspose.imaging.Rectangle` 结构的新实例，其 `com.aspose.imaging.Rectangle.X`、`com.aspose.imaging.Rectangle.Y`、`com.aspose.imaging.Rectangle.Width` 和 `com.aspose.imaging.Rectangle.Height` 值均为零。 |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 根据指定的两个点创建一个新的 `Rectangle`。 |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | 通过将 `com.aspose.imaging.RectangleF` 的值向上取整为下一个更高的整数，将指定的 `com.aspose.imaging.RectangleF` 结构转换为 `com.aspose.imaging.Rectangle` 结构。 |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | 将指定的 `com.aspose.imaging.RectangleF` 转换为 `com.aspose.imaging.Rectangle`，通过截断 `com.aspose.imaging.RectangleF` 的值。 |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | 将指定的 `com.aspose.imaging.RectangleF` 转换为 `com.aspose.imaging.Rectangle`，通过将 `com.aspose.imaging.RectangleF` 的值四舍五入为最接近的整数。 |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | 创建并返回指定的 `com.aspose.imaging.Rectangle` 结构的膨胀副本。 |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | 返回第三个 `com.aspose.imaging.Rectangle` 结构，表示另外两个 `com.aspose.imaging.Rectangle` 结构的交集。 |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | 获取一个包含两个 `com.aspose.imaging.Rectangle` 结构并集的 `com.aspose.imaging.Rectangle` 结构。 |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | 测试两个 `com.aspose.imaging.Rectangle` 结构是否具有相同的位置和大小。 |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | 测试两个 `com.aspose.imaging.Rectangle` 结构在位置或大小上是否不同。 |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | 使用指定的边缘位置创建一个 `com.aspose.imaging.Rectangle` 结构。 |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的坐标。 |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的坐标。 |
| [getSize()](#getSize--) | 获取或设置此 `com.aspose.imaging.Rectangle` 的大小。 |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | 获取或设置此 `com.aspose.imaging.Rectangle` 的大小。 |
| [getX()](#getX--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。 |
| [setX(int value)](#setX-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。 |
| [getY()](#getY--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。 |
| [setY(int value)](#setY-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。 |
| [getWidth()](#getWidth--) | 获取此 `com.aspose.imaging.Rectangle` 结构的宽度。 |
| [setWidth(int value)](#setWidth-int-) | 设置此 `com.aspose.imaging.Rectangle` 结构的宽度。 |
| [getHeight()](#getHeight--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的高度。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的高度。 |
| [getLeft()](#getLeft--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。 |
| [getTop()](#getTop--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构顶部边缘的 y 坐标。 |
| [setTop(int value)](#setTop-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构顶部边缘的 y 坐标。 |
| [getRight()](#getRight--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的 x 坐标，该坐标为 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 属性值之和。 |
| [setRight(int value)](#setRight-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的 x 坐标，该坐标为 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 属性值之和。 |
| [getBottom()](#getBottom--) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的 y 坐标，该坐标为 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 属性值之和。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置此 `com.aspose.imaging.Rectangle` 结构的 y 坐标，该坐标为 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 属性值之和。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此 `com.aspose.imaging.Rectangle` 的所有数值属性是否为零。 |
| [contains(int x, int y)](#contains-int-int-) | 确定指定的点是否包含在此 `com.aspose.imaging.Rectangle` 结构中。 |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | 确定指定的点是否包含在此 `com.aspose.imaging.Rectangle` 结构中。 |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | 确定由 `rect` 表示的矩形区域是否完全包含在此 `com.aspose.imaging.Rectangle` 结构中。 |
| [inflate(int width, int height)](#inflate-int-int-) | 按指定量膨胀此 `com.aspose.imaging.Rectangle`。 |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | 按指定量膨胀此 `com.aspose.imaging.Rectangle`。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | 用此 `com.aspose.imaging.Rectangle` 与指定的 `com.aspose.imaging.Rectangle` 的交集替换此 `com.aspose.imaging.Rectangle`。 |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | 确定此矩形是否与 `rect` 相交。 |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | 按指定量调整此矩形的位置。 |
| [offset(int x, int y)](#offset-int-int-) | 按指定量调整此矩形的位置。 |
| [normalize()](#normalize--) | 通过使矩形的宽度和高度为正、左侧小于右侧、顶部小于底部来标准化该矩形。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试 `obj` 是否为具有与此 `com.aspose.imaging.Rectangle` 结构相同位置和大小的 `com.aspose.imaging.Rectangle` 结构。 |
| [hashCode()](#hashCode--) | 返回此 `com.aspose.imaging.Rectangle` 结构的哈希码。 |
| [toString()](#toString--) | 将此 `com.aspose.imaging.Rectangle` 的属性转换为可读的字符串。 |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


使用指定的位置和大小初始化 `com.aspose.imaging.Rectangle` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 矩形左上角的 x 坐标。 |
| y | int | 矩形左上角的 y 坐标。 |
| width | int | 矩形的宽度。 |
| height | int | 矩形的高度。 |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


使用指定的位置和大小初始化 `com.aspose.imaging.Rectangle` 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | 表示矩形区域左上角的 `com.aspose.imaging.Point`。 |
| size | [Size](../../com.aspose.imaging/size) | 表示矩形区域宽度和高度的 `com.aspose.imaging.Size`。 |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


获取一个 `com.aspose.imaging.Rectangle` 结构的新实例，其 `com.aspose.imaging.Rectangle.X`、`com.aspose.imaging.Rectangle.Y`、`com.aspose.imaging.Rectangle.Width` 和 `com.aspose.imaging.Rectangle.Height` 值均为零。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


根据指定的两个点创建一个新的 `Rectangle`。创建的 `Rectangle` 的两个垂直边将等于传入的 `point1` 和 `point2`。这些通常是相对的顶点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | 新矩形的第一个 `Point`。 |
| point2 | [Point](../../com.aspose.imaging/point) | 新矩形的第二个 `Point`。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


通过将 `com.aspose.imaging.RectangleF` 的值向上取整为下一个更高的整数，将指定的 `com.aspose.imaging.RectangleF` 结构转换为 `com.aspose.imaging.Rectangle` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 要转换的 `com.aspose.imaging.RectangleF` 结构。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


将指定的 `com.aspose.imaging.RectangleF` 转换为 `com.aspose.imaging.Rectangle`，通过截断 `com.aspose.imaging.RectangleF` 的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 要转换的 `com.aspose.imaging.RectangleF`。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


将指定的 `com.aspose.imaging.RectangleF` 转换为 `com.aspose.imaging.Rectangle`，通过将 `com.aspose.imaging.RectangleF` 的值四舍五入为最接近的整数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 要转换的 `com.aspose.imaging.RectangleF`。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


创建并返回指定 `com.aspose.imaging.Rectangle` 结构的膨胀副本。副本按指定的量进行膨胀。原始的 `com.aspose.imaging.Rectangle` 结构保持不变。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于开始的 `com.aspose.imaging.Rectangle`。此矩形不会被修改。 |
| x | int | 水平膨胀此 `com.aspose.imaging.Rectangle` 的量。 |
| y | int | 垂直膨胀此 `com.aspose.imaging.Rectangle` 的量。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


返回第三个 `com.aspose.imaging.Rectangle` 结构，表示另外两个 `com.aspose.imaging.Rectangle` 结构的交集。如果没有交集，则返回一个空的 `com.aspose.imaging.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | 第一个用于交集的矩形。 |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | 第二个用于交集的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


获取一个包含两个 `com.aspose.imaging.Rectangle` 结构并集的 `com.aspose.imaging.Rectangle` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | 第一个用于并集的矩形。 |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | 第二个用于并集的矩形。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


测试两个 `com.aspose.imaging.Rectangle` 结构是否具有相同的位置和大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | 等号运算符左侧的 `com.aspose.imaging.Rectangle` 结构。 |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | 等号运算符右侧的 `com.aspose.imaging.Rectangle` 结构。 |

**Returns:**
boolean - 如果两个 `com.aspose.imaging.Rectangle` 结构的 `com.aspose.imaging.Rectangle.X`、`com.aspose.imaging.Rectangle.Y`、`com.aspose.imaging.Rectangle.Width` 和 `com.aspose.imaging.Rectangle.Height` 属性相等，则此运算符返回 true。
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


测试两个 `com.aspose.imaging.Rectangle` 结构在位置或大小上是否不同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | 不等号运算符左侧的 `com.aspose.imaging.Rectangle` 结构。 |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | 不等号运算符右侧的 `com.aspose.imaging.Rectangle` 结构。 |

**Returns:**
boolean - 如果两个 `com.aspose.imaging.Rectangle` 结构的 `com.aspose.imaging.Rectangle.X`、`com.aspose.imaging.Rectangle.Y`、`com.aspose.imaging.Rectangle.Width` 或 `com.aspose.imaging.Rectangle.Height` 属性中任意一个不相等，则此运算符返回 true；否则返回 false。
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


使用指定的边缘位置创建一个 `com.aspose.imaging.Rectangle` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | int | 此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。 |
| 上 | int | 此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。 |
| 右 | int | 此 `com.aspose.imaging.Rectangle` 结构右下角的 x 坐标。 |
| 下 | int | 此 `com.aspose.imaging.Rectangle` 结构右下角的 y 坐标。 |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的坐标。

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | 表示此 `com.aspose.imaging.Rectangle` 结构左上角的 `Point`。 |

### getSize() {#getSize--}
```
public Size getSize()
```


获取或设置此 `com.aspose.imaging.Rectangle` 的大小。

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | 表示此 `com.aspose.imaging.Rectangle` 结构宽度和高度的 `com.aspose.imaging.Size`。 |

### getX() {#getX--}
```
public int getX()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构左上角的 x 坐标。 |

### getY() {#getY--}
```
public int getY()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构左上角的 y 坐标。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取此 `com.aspose.imaging.Rectangle` 结构的宽度。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构的宽度。
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


设置此 `com.aspose.imaging.Rectangle` 结构的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构的宽度。 |

### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的高度。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构的高度。
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构的高度。 |

### getLeft() {#getLeft--}
```
public int getLeft()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构左边缘的 x 坐标。 |

### getTop() {#getTop--}
```
public int getTop()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构顶部边缘的 y 坐标。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 结构上边缘的 y 坐标。
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构顶部边缘的 y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 结构上边缘的 y 坐标。 |

### getRight() {#getRight--}
```
public int getRight()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的 x 坐标，该坐标为 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 属性值之和。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 的 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 的和所得到的 x 坐标。
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的 x 坐标，该坐标为 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 属性值之和。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 的 `com.aspose.imaging.Rectangle.X` 与 `com.aspose.imaging.Rectangle.Width` 的和所得到的 x 坐标。 |

### getBottom() {#getBottom--}
```
public int getBottom()
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的 y 坐标，该坐标为 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 属性值之和。

**Returns:**
int - 此 `com.aspose.imaging.Rectangle` 的 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 的和所得到的 y 坐标。
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


获取或设置此 `com.aspose.imaging.Rectangle` 结构的 y 坐标，该坐标为 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 属性值之和。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 此 `com.aspose.imaging.Rectangle` 的 `com.aspose.imaging.Rectangle.Y` 与 `com.aspose.imaging.Rectangle.Height` 的和所得到的 y 坐标。 |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此 `com.aspose.imaging.Rectangle` 的所有数值属性是否为零。

**Returns:**
boolean - 如果此 `com.aspose.imaging.Rectangle` 的 `com.aspose.imaging.Rectangle.Width`、`com.aspose.imaging.Rectangle.Height`、`com.aspose.imaging.Rectangle.X` 和 `com.aspose.imaging.Rectangle.Y` 属性全部为零，则此属性返回 true；否则返回 false。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


确定指定的点是否包含在此 `com.aspose.imaging.Rectangle` 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 要测试的点的 x 坐标。 |
| y | int | 要测试的点的 y 坐标。 |

**Returns:**
boolean - 如果由 `x` 和 `y` 定义的点位于此 `com.aspose.imaging.Rectangle` 结构内部，则此方法返回 true；否则返回 false。
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


确定指定的点是否包含在此 `com.aspose.imaging.Rectangle` 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | 要测试的 `com.aspose.imaging.Point`。 |

**Returns:**
boolean - 如果由 `point` 表示的点位于此 `com.aspose.imaging.Rectangle` 结构内部，则此方法返回 true；否则返回 false。
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


确定由 `rect` 表示的矩形区域是否完全包含在此 `com.aspose.imaging.Rectangle` 结构中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 要测试的 `com.aspose.imaging.Rectangle`。 |

**Returns:**
boolean - 如果由 `rect` 表示的矩形区域完全位于此 `com.aspose.imaging.Rectangle` 结构内部，则此方法返回 true；否则返回 false。
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


按指定量膨胀此 `com.aspose.imaging.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 水平膨胀此 `com.aspose.imaging.Rectangle` 的量。 |
| height | int | 垂直膨胀此 `com.aspose.imaging.Rectangle` 的量。 |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


按指定量膨胀此 `com.aspose.imaging.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | 膨胀此矩形的量。 |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


用此 `com.aspose.imaging.Rectangle` 与指定的 `com.aspose.imaging.Rectangle` 的交集替换此 `com.aspose.imaging.Rectangle`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 用于相交的 `com.aspose.imaging.Rectangle`。 |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


确定此矩形是否与 `rect` 相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 要测试的矩形。 |

**Returns:**
boolean - 如果存在任何交叉，则此方法返回 true；否则返回 false。
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | 位置的偏移量。 |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


按指定量调整此矩形的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 水平偏移量。 |
| y | int | 垂直偏移量。 |

### normalize() {#normalize--}
```
public void normalize()
```


通过使矩形的宽度和高度为正、左侧小于右侧、顶部小于底部来标准化该矩形。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试 `obj` 是否为具有与此 `com.aspose.imaging.Rectangle` 结构相同位置和大小的 `com.aspose.imaging.Rectangle` 结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于测试的 `System.Object`。 |

**Returns:**
boolean - 如果 `obj` 是 `com.aspose.imaging.Rectangle` 结构，并且其 `com.aspose.imaging.Rectangle.X`、`com.aspose.imaging.Rectangle.Y`、`com.aspose.imaging.Rectangle.Width` 和 `com.aspose.imaging.Rectangle.Height` 属性等于此 `com.aspose.imaging.Rectangle` 结构的相应属性，则此方法返回 true；否则返回 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此 `com.aspose.imaging.Rectangle` 结构的哈希码。

**Returns:**
int - 表示此矩形哈希码的整数。
### toString() {#toString--}
```
public String toString()
```


将此 `com.aspose.imaging.Rectangle` 的属性转换为可读的字符串。

**Returns:**
java.lang.String - 包含此 `com.aspose.imaging.Rectangle` 结构的位置、宽度和高度的字符串。
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
