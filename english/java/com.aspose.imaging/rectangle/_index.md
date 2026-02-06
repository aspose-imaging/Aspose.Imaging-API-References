---
title: Rectangle
second_title: Aspose.Imaging for Java API Reference
description: Stores a set of four integers that represent the location and size of a rectangle.
type: docs
weight: 93
url: /java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Stores a set of four integers that represent the location and size of a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initializes a new instance of the `com.aspose.imaging.Rectangle` structure with the specified location and size. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Initializes a new instance of the `com.aspose.imaging.Rectangle` structure with the specified location and size. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `com.aspose.imaging.Rectangle` structure that has `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` and `com.aspose.imaging.Rectangle.Height` values set to zero. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Creates a new `Rectangle` from two points specified. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Converts the specified `com.aspose.imaging.RectangleF` structure to a `com.aspose.imaging.Rectangle` structure by rounding the `com.aspose.imaging.RectangleF` values to the next higher integer values. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Converts the specified `com.aspose.imaging.RectangleF` to a `com.aspose.imaging.Rectangle` by truncating the `com.aspose.imaging.RectangleF` values. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Converts the specified `com.aspose.imaging.RectangleF` to a `com.aspose.imaging.Rectangle` by rounding the `com.aspose.imaging.RectangleF` values to the nearest integer values. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Creates and returns an inflated copy of the specified `com.aspose.imaging.Rectangle` structure. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Returns a third `com.aspose.imaging.Rectangle` structure that represents the intersection of two other `com.aspose.imaging.Rectangle` structures. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Gets a `com.aspose.imaging.Rectangle` structure that contains the union of two `com.aspose.imaging.Rectangle` structures. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Tests whether two `com.aspose.imaging.Rectangle` structures have equal location and size. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Tests whether two `com.aspose.imaging.Rectangle` structures differ in location or size. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Creates a `com.aspose.imaging.Rectangle` structure with the specified edge locations. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [getSize()](#getSize--) | Gets or sets the size of this `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Gets or sets the size of this `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [setX(int value)](#setX-int-) | Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [setY(int value)](#setY-int-) | Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| [getWidth()](#getWidth--) | Gets the width of this `com.aspose.imaging.Rectangle` structure. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of this `com.aspose.imaging.Rectangle` structure. |
| [getHeight()](#getHeight--) | Gets or sets the height of this `com.aspose.imaging.Rectangle` structure. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets the height of this `com.aspose.imaging.Rectangle` structure. |
| [getLeft()](#getLeft--) | Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure. |
| [getTop()](#getTop--) | Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure. |
| [setTop(int value)](#setTop-int-) | Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure. |
| [getRight()](#getRight--) | Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` property values of this `com.aspose.imaging.Rectangle` structure. |
| [setRight(int value)](#setRight-int-) | Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` property values of this `com.aspose.imaging.Rectangle` structure. |
| [getBottom()](#getBottom--) | Gets or sets the y-coordinate that is the sum of the `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` property values of this `com.aspose.imaging.Rectangle` structure. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the y-coordinate that is the sum of the `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` property values of this `com.aspose.imaging.Rectangle` structure. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether all numeric properties of this `com.aspose.imaging.Rectangle` have values of zero. |
| [contains(int x, int y)](#contains-int-int-) | Determines if the specified point is contained within this `com.aspose.imaging.Rectangle` structure. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Determines if the specified point is contained within this `com.aspose.imaging.Rectangle` structure. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Determines if the rectangular region represented by `rect` is entirely contained within this `com.aspose.imaging.Rectangle` structure. |
| [inflate(int width, int height)](#inflate-int-int-) | Inflates this `com.aspose.imaging.Rectangle` by the specified amount. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Inflates this `com.aspose.imaging.Rectangle` by the specified amount. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Replaces this `com.aspose.imaging.Rectangle` with the intersection of itself and the specified `com.aspose.imaging.Rectangle`. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Determines if this rectangle intersects with `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Adjusts the location of this rectangle by the specified amount. |
| [offset(int x, int y)](#offset-int-int-) | Adjusts the location of this rectangle by the specified amount. |
| [normalize()](#normalize--) | Normalizes the rectangle by making its width and height positive, left less than right and top less than bottom. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether `obj` is a `com.aspose.imaging.Rectangle` structure with the same location and size of this `com.aspose.imaging.Rectangle` structure. |
| [hashCode()](#hashCode--) | Returns the hash code for this `com.aspose.imaging.Rectangle` structure. |
| [toString()](#toString--) | Converts the attributes of this `com.aspose.imaging.Rectangle` to a human-readable string. |
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


Initializes a new instance of the `com.aspose.imaging.Rectangle` structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle. |
| y | int | The y-coordinate of the upper-left corner of the rectangle. |
| width | int | The width of the rectangle. |
| height | int | The height of the rectangle. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Initializes a new instance of the `com.aspose.imaging.Rectangle` structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | A `com.aspose.imaging.Point` that represents the upper-left corner of the rectangular region. |
| size | [Size](../../com.aspose.imaging/size) | A `com.aspose.imaging.Size` that represents the width and height of the rectangular region. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gets a new instance of the `com.aspose.imaging.Rectangle` structure that has `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` and `com.aspose.imaging.Rectangle.Height` values set to zero.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Creates a new `Rectangle` from two points specified. Two verticals of the created `Rectangle` will be equal to the passed `point1` and `point2`. These would be typically the opposite vertices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | The first `Point` for the new rectangle. |
| point2 | [Point](../../com.aspose.imaging/point) | The second `Point` for the new rectangle. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converts the specified `com.aspose.imaging.RectangleF` structure to a `com.aspose.imaging.Rectangle` structure by rounding the `com.aspose.imaging.RectangleF` values to the next higher integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` structure to be converted. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converts the specified `com.aspose.imaging.RectangleF` to a `com.aspose.imaging.Rectangle` by truncating the `com.aspose.imaging.RectangleF` values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` to be converted. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converts the specified `com.aspose.imaging.RectangleF` to a `com.aspose.imaging.Rectangle` by rounding the `com.aspose.imaging.RectangleF` values to the nearest integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | The `com.aspose.imaging.RectangleF` to be converted. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Creates and returns an inflated copy of the specified `com.aspose.imaging.Rectangle` structure. The copy is inflated by the specified amount. The original `com.aspose.imaging.Rectangle` structure remains unmodified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this `com.aspose.imaging.Rectangle` horizontally. |
| y | int | The amount to inflate this `com.aspose.imaging.Rectangle` vertically. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Returns a third `com.aspose.imaging.Rectangle` structure that represents the intersection of two other `com.aspose.imaging.Rectangle` structures. If there is no intersection, an empty `com.aspose.imaging.Rectangle` is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | A first rectangle to intersect. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | A second rectangle to intersect. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Gets a `com.aspose.imaging.Rectangle` structure that contains the union of two `com.aspose.imaging.Rectangle` structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | A first rectangle to union. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | A second rectangle to union. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Tests whether two `com.aspose.imaging.Rectangle` structures have equal location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure that is to the left of the equality operator. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure that is to the right of the equality operator. |

**Returns:**
boolean - This operator returns true if the two `com.aspose.imaging.Rectangle` structures have equal `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width`, and `com.aspose.imaging.Rectangle.Height` properties.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Tests whether two `com.aspose.imaging.Rectangle` structures differ in location or size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure that is to the left of the inequality operator. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` structure that is to the right of the inequality operator. |

**Returns:**
boolean - This operator returns true if any of the `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` or `com.aspose.imaging.Rectangle.Height` properties of the two `com.aspose.imaging.Rectangle` structures are unequal; otherwise false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Creates a `com.aspose.imaging.Rectangle` structure with the specified edge locations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| top | int | The y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |
| right | int | The x-coordinate of the lower-right corner of this `com.aspose.imaging.Rectangle` structure. |
| bottom | int | The y-coordinate of the lower-right corner of this `com.aspose.imaging.Rectangle` structure. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Gets or sets the coordinates of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | A `Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |

### getSize() {#getSize--}
```
public Size getSize()
```


Gets or sets the size of this `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Gets or sets the size of this `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure. |

### getX() {#getX--}
```
public int getX()
```


Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Gets or sets the x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |

### getY() {#getY--}
```
public int getY()
```


Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Gets or sets the y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate of the upper-left corner of this `com.aspose.imaging.Rectangle` structure. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The width of this `com.aspose.imaging.Rectangle` structure.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Sets the width of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of this `com.aspose.imaging.Rectangle` structure. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the height of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The height of this `com.aspose.imaging.Rectangle` structure.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets the height of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of this `com.aspose.imaging.Rectangle` structure. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Gets or sets the x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate of the left edge of this `com.aspose.imaging.Rectangle` structure. |

### getTop() {#getTop--}
```
public int getTop()
```


Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Gets or sets the y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate of the top edge of this `com.aspose.imaging.Rectangle` structure. |

### getRight() {#getRight--}
```
public int getRight()
```


Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` property values of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` of this `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Gets or sets the x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` property values of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate that is the sum of `com.aspose.imaging.Rectangle.X` and `com.aspose.imaging.Rectangle.Width` of this `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Gets or sets the y-coordinate that is the sum of the `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` property values of this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - The y-coordinate that is the sum of `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` of this `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Gets or sets the y-coordinate that is the sum of the `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` property values of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate that is the sum of `com.aspose.imaging.Rectangle.Y` and `com.aspose.imaging.Rectangle.Height` of this `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether all numeric properties of this `com.aspose.imaging.Rectangle` have values of zero.

**Returns:**
boolean - This property returns true if the `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X`, and `com.aspose.imaging.Rectangle.Y` properties of this `com.aspose.imaging.Rectangle` all have values of zero; otherwise, false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determines if the specified point is contained within this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the point defined by `x` and `y` is contained within this `com.aspose.imaging.Rectangle` structure; otherwise false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Determines if the specified point is contained within this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `com.aspose.imaging.Point` to test. |

**Returns:**
boolean - This method returns true if the point represented by `point` is contained within this `com.aspose.imaging.Rectangle` structure; otherwise false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determines if the rectangular region represented by `rect` is entirely contained within this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` to test. |

**Returns:**
boolean - This method returns true if the rectangular region represented by `rect` is entirely contained within this `com.aspose.imaging.Rectangle` structure; otherwise false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Inflates this `com.aspose.imaging.Rectangle` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The amount to inflate this `com.aspose.imaging.Rectangle` horizontally. |
| height | int | The amount to inflate this `com.aspose.imaging.Rectangle` vertically. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Inflates this `com.aspose.imaging.Rectangle` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | The amount to inflate this rectangle. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Replaces this `com.aspose.imaging.Rectangle` with the intersection of itself and the specified `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The `com.aspose.imaging.Rectangle` with which to intersect. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determines if this rectangle intersects with `rect`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle to test. |

**Returns:**
boolean - This method returns true if there is any intersection, otherwise false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Amount to offset the location. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The horizontal offset. |
| y | int | The vertical offset. |

### normalize() {#normalize--}
```
public void normalize()
```


Normalizes the rectangle by making its width and height positive, left less than right and top less than bottom.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether `obj` is a `com.aspose.imaging.Rectangle` structure with the same location and size of this `com.aspose.imaging.Rectangle` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - This method returns true if `obj` is a `com.aspose.imaging.Rectangle` structure and its `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width`, and `com.aspose.imaging.Rectangle.Height` properties are equal to the corresponding properties of this `com.aspose.imaging.Rectangle` structure; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this `com.aspose.imaging.Rectangle` structure.

**Returns:**
int - An integer that represents the hash code for this rectangle.
### toString() {#toString--}
```
public String toString()
```


Converts the attributes of this `com.aspose.imaging.Rectangle` to a human-readable string.

**Returns:**
java.lang.String - A string that contains the position, width, and height of this `com.aspose.imaging.Rectangle` structure.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
