---
title: RectangleF
second_title: Aspose.Imaging for Java API Reference
description: Stores a set of four floating-point numbers that represent the location and size of a rectangle.
type: docs
weight: 95
url: /com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Stores a set of four floating-point numbers that represent the location and size of a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initializes a new instance of the `com.aspose.imaging.RectangleF` structure with the specified location and size. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Initializes a new instance of the `com.aspose.imaging.RectangleF` structure with the specified location and size. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `com.aspose.imaging.RectangleF` structure that has `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` and `com.aspose.imaging.RectangleF.Height` values set to zero. |
| [getLocation()](#getLocation--) | Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [getSize()](#getSize--) | Gets or sets the size of this `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Gets or sets the size of this `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure. |
| [getWidth()](#getWidth--) | Gets or sets the width of this `com.aspose.imaging.RectangleF` structure. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width of this `com.aspose.imaging.RectangleF` structure. |
| [getHeight()](#getHeight--) | Gets or sets the height of this `com.aspose.imaging.RectangleF` structure. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height of this `com.aspose.imaging.RectangleF` structure. |
| [getLeft()](#getLeft--) | Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.RectangleF` structure. |
| [setLeft(float value)](#setLeft-float-) | Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.RectangleF` structure. |
| [getTop()](#getTop--) | Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.RectangleF` structure. |
| [setTop(float value)](#setTop-float-) | Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.RectangleF` structure. |
| [getRight()](#getRight--) | Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.RectangleF.X` and `com.aspose.imaging.RectangleF.Width` of this `com.aspose.imaging.RectangleF` structure. |
| [setRight(float value)](#setRight-float-) | Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.RectangleF.X` and `com.aspose.imaging.RectangleF.Width` of this `com.aspose.imaging.RectangleF` structure. |
| [getBottom()](#getBottom--) | Gets or sets the y-coordinate that is the sum of `com.aspose.imaging.RectangleF.Y` and `com.aspose.imaging.RectangleF.Height` of this `com.aspose.imaging.RectangleF` structure. |
| [setBottom(float value)](#setBottom-float-) | Gets or sets the y-coordinate that is the sum of `com.aspose.imaging.RectangleF.Y` and `com.aspose.imaging.RectangleF.Height` of this `com.aspose.imaging.RectangleF` structure. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether the `com.aspose.imaging.RectangleF.Width` or `com.aspose.imaging.RectangleF.Height` property of this `com.aspose.imaging.RectangleF` has a value of zero. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Creates a new `Rectangle` from two points specified. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Creates and returns an inflated copy of the specified `com.aspose.imaging.RectangleF` structure. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Returns a `com.aspose.imaging.RectangleF` structure that represents the intersection of two rectangles. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Tests whether two `com.aspose.imaging.RectangleF` structures have equal location and size. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Tests whether two `com.aspose.imaging.RectangleF` structures differ in location or size. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implements the operator \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implements the operator /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Converts the specified `com.aspose.imaging.Rectangle` structure to a `com.aspose.imaging.RectangleF` structure. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Creates a `com.aspose.imaging.RectangleF` structure with upper-left corner and lower-right corner at the specified locations. |
| [normalize()](#normalize--) | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [contains(float x, float y)](#contains-float-float-) | Determines if the specified point is contained within this `com.aspose.imaging.RectangleF` structure. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Determines if the specified point is contained within this `com.aspose.imaging.RectangleF` structure. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Determines if the rectangular region represented by `rect` is entirely contained within this `com.aspose.imaging.RectangleF` structure. |
| [inflate(float x, float y)](#inflate-float-float-) | Inflates this `com.aspose.imaging.RectangleF` structure by the specified amount. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Inflates this `com.aspose.imaging.RectangleF` by the specified amount. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Replaces this `com.aspose.imaging.RectangleF` structure with the intersection of itself and the specified `com.aspose.imaging.RectangleF` structure. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Determines if this rectangle intersects with `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Adjusts the location of this rectangle by the specified amount. |
| [offset(float x, float y)](#offset-float-float-) | Adjusts the location of this rectangle by the specified amount. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether `obj` is a `com.aspose.imaging.RectangleF` with the same location and size of this `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Gets the hash code for this `com.aspose.imaging.RectangleF` structure. |
| [toString()](#toString--) | Converts the attributes of this `com.aspose.imaging.RectangleF` to a human-readable string. |
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


Initializes a new instance of the `com.aspose.imaging.RectangleF` structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle. |
| y | float | The y-coordinate of the upper-left corner of the rectangle. |
| width | float | The width of the rectangle. |
| height | float | The height of the rectangle. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initializes a new instance of the `com.aspose.imaging.RectangleF` structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` that represents the upper-left corner of the rectangular region. |
| size | [SizeF](../../com.aspose.imaging/sizef) | A `com.aspose.imaging.SizeF` that represents the width and height of the rectangular region. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Gets a new instance of the `com.aspose.imaging.RectangleF` structure that has `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` and `com.aspose.imaging.RectangleF.Height` values set to zero.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Gets or sets the size of this `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Gets or sets the size of this `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The x-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The y-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Gets or sets the width of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The width of this `com.aspose.imaging.RectangleF` structure.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Gets or sets the width of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Gets or sets the height of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The height of this `com.aspose.imaging.RectangleF` structure.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Gets or sets the height of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The x-coordinate of the left edge of this `com.aspose.imaging.RectangleF` structure.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The y-coordinate of the top edge of this `com.aspose.imaging.RectangleF` structure.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.RectangleF.X` and `com.aspose.imaging.RectangleF.Width` of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The x-coordinate that is the sum of `com.aspose.imaging.RectangleF.X` and `com.aspose.imaging.RectangleF.Width` of this `com.aspose.imaging.RectangleF` structure.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.RectangleF.X` and `com.aspose.imaging.RectangleF.Width` of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Gets or sets the y-coordinate that is the sum of `com.aspose.imaging.RectangleF.Y` and `com.aspose.imaging.RectangleF.Height` of this `com.aspose.imaging.RectangleF` structure.

**Returns:**
float - The y-coordinate that is the sum of `com.aspose.imaging.RectangleF.Y` and `com.aspose.imaging.RectangleF.Height` of this `com.aspose.imaging.RectangleF` structure.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Gets or sets the y-coordinate that is the sum of `com.aspose.imaging.RectangleF.Y` and `com.aspose.imaging.RectangleF.Height` of this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether the `com.aspose.imaging.RectangleF.Width` or `com.aspose.imaging.RectangleF.Height` property of this `com.aspose.imaging.RectangleF` has a value of zero.

**Returns:**
boolean - This property returns true if the `com.aspose.imaging.RectangleF.Width` or `com.aspose.imaging.RectangleF.Height` property of this `com.aspose.imaging.RectangleF` has a value of zero; otherwise, false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Creates a new `Rectangle` from two points specified. Two verticles of the created `Rectangle` will be equal to the passed `point1` and `point2`. These would be typically the opposite vertices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | The first `Point` for the new rectangle. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | The second `Point` for the new rectangle. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Creates and returns an inflated copy of the specified `com.aspose.imaging.RectangleF` structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` to be copied. This rectangle is not modified. |
| x | float | The amount to inflate the copy of the rectangle horizontally. |
| y | float | The amount to inflate the copy of the rectangle vertically. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Returns a `com.aspose.imaging.RectangleF` structure that represents the intersection of two rectangles. If there is no intersection, and empty `com.aspose.imaging.RectangleF` is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | A first rectangle to intersect. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | A second rectangle to intersect. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Creates the smallest possible third rectangle that can contain both of two rectangles that form a union.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | A first rectangle to union. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | A second rectangle to union. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Tests whether two `com.aspose.imaging.RectangleF` structures have equal location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure that is to the left of the equality operator. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure that is to the right of the equality operator. |

**Returns:**
boolean - This operator returns true if the two specified `com.aspose.imaging.RectangleF` structures have equal `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width`, and `com.aspose.imaging.RectangleF.Height` properties.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Tests whether two `com.aspose.imaging.RectangleF` structures differ in location or size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure that is to the left of the inequality operator. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure that is to the right of the inequality operator. |

**Returns:**
boolean - This operator returns true if any of the `com.aspose.imaging.RectangleF.X` , `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width`, or `com.aspose.imaging.RectangleF.Height` properties of the two `com.aspose.imaging.RectangleF` structures are unequal; otherwise false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implements the operator \*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| multiplier | float | The multiplier. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implements the operator /.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle. |
| divider | float | The divider. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Converts the specified `com.aspose.imaging.Rectangle` structure to a `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure to convert. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Creates a `com.aspose.imaging.RectangleF` structure with upper-left corner and lower-right corner at the specified locations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | float | The x-coordinate of the upper-left corner of the rectangular region. |
| top | float | The y-coordinate of the upper-left corner of the rectangular region. |
| right | float | The x-coordinate of the lower-right corner of the rectangular region. |
| bottom | float | The y-coordinate of the lower-right corner of the rectangular region. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determines if the specified point is contained within this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the point defined by `x` and `y` is contained within this `com.aspose.imaging.RectangleF` structure; otherwise false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Determines if the specified point is contained within this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to test. |

**Returns:**
boolean - This method returns true if the point represented by the `point` parameter is contained within this `com.aspose.imaging.RectangleF` structure; otherwise false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determines if the rectangular region represented by `rect` is entirely contained within this `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` to test. |

**Returns:**
boolean - This method returns true if the rectangular region represented by `rect` is entirely contained within the rectangular region represented by this `com.aspose.imaging.RectangleF`; otherwise false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Inflates this `com.aspose.imaging.RectangleF` structure by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The amount to inflate this `com.aspose.imaging.RectangleF` structure horizontally. |
| y | float | The amount to inflate this `com.aspose.imaging.RectangleF` structure vertically. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Inflates this `com.aspose.imaging.RectangleF` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The amount to inflate this rectangle. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Replaces this `com.aspose.imaging.RectangleF` structure with the intersection of itself and the specified `com.aspose.imaging.RectangleF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle to intersect. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determines if this rectangle intersects with `rect`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle to test. |

**Returns:**
boolean - This method returns true if there is any intersection.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | The amount to offset the location. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The amount to offset the location horizontally. |
| y | float | The amount to offset the location vertically. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether `obj` is a `com.aspose.imaging.RectangleF` with the same location and size of this `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - This method returns true if `obj` is a `com.aspose.imaging.RectangleF` and its X, Y, Width, and Height properties are equal to the corresponding properties of this `com.aspose.imaging.RectangleF`; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this `com.aspose.imaging.RectangleF` structure.

**Returns:**
int - The hash code for this `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Converts the attributes of this `com.aspose.imaging.RectangleF` to a human-readable string.

**Returns:**
java.lang.String - A string that contains the position, width, and height of this `com.aspose.imaging.RectangleF` structure.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
