---
title: Point
second_title: Aspose.Imaging for Java API Reference
description: Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 87
url: /java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initializes a new instance of the `Aspose.Imaging.Point` structure with the specified coordinates. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Initializes a new instance of the `Aspose.Imaging.Point` structure from the `Aspose.Imaging.Size` structure. |
| [Point(int dw)](#Point-int-) | Initializes a new instance of the `Aspose.Imaging.Point` structure using coordinates specified by an integer value. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `Aspose.Imaging.Point` structure that has `Aspose.Imaging.Point.X` and `Aspose.Imaging.Point.Y` values set to zero. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this `Aspose.Imaging.Point` is empty. |
| [getX()](#getX--) | Gets or sets the x-coordinate of this `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Gets or sets the x-coordinate of this `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Gets or sets the y-coordinate of this `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Gets or sets the y-coordinate of this `Aspose.Imaging.Point`. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Adds the specified `Aspose.Imaging.Size` to the specified `Aspose.Imaging.Point`. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Returns the result of subtracting specified `Aspose.Imaging.Size` from the specified `Aspose.Imaging.Point`. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` by rounding the values of the `Aspose.Imaging.PointF` to the next higher integer values. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` object by rounding the `Aspose.Imaging.Point` values to the nearest integer. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` by truncating the values of the `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Translates a `Aspose.Imaging.Point` by a given `Aspose.Imaging.Size`. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Translates a `Aspose.Imaging.Point` by the negative of a given `Aspose.Imaging.Size`. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compares two `Aspose.Imaging.Point` objects. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Compares two `Aspose.Imaging.Point` objects. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Converts the specified `Aspose.Imaging.Point` structure to a `Aspose.Imaging.Size` structure. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Converts the specified `Point` structure to the `PointF` structure. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Translates this `Aspose.Imaging.Point` by the specified `Aspose.Imaging.Point`. |
| [offset(int dx, int dy)](#offset-int-int-) | Translates this `Aspose.Imaging.Point` by the specified amount. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifies whether this `Aspose.Imaging.Point` contains the same coordinates as the specified `System.Object`. |
| [hashCode()](#hashCode--) | Returns a hash code for this `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Convert this Point to a single long value, containing X and Y coordinates in high and low bits. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Deconstruct a Point object packed into a long object to separate X and Y int values. |
| [toString()](#toString--) | Converts this `Aspose.Imaging.Point` to a human-readable string. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initializes a new instance of the `Aspose.Imaging.Point` structure with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The horizontal position of the point. |
| y | int | The vertical position of the point. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Initializes a new instance of the `Aspose.Imaging.Point` structure from the `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Contains the new point coordinates. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initializes a new instance of the `Aspose.Imaging.Point` structure using coordinates specified by an integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dw | int | A 32-bit integer that specifies the coordinates for the new point. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Gets a new instance of the `Aspose.Imaging.Point` structure that has `Aspose.Imaging.Point.X` and `Aspose.Imaging.Point.Y` values set to zero.

**Returns:**
[Point](../../com.aspose.imaging/point)
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this `Aspose.Imaging.Point` is empty.

**Returns:**
boolean - True if both `Aspose.Imaging.Point.X` and `Aspose.Imaging.Point.Y` are 0; otherwise, false.
### getX() {#getX--}
```
public int getX()
```


Gets or sets the x-coordinate of this `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Gets or sets the x-coordinate of this `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


Gets or sets the y-coordinate of this `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Gets or sets the y-coordinate of this `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Adds the specified `Aspose.Imaging.Size` to the specified `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` to add to. |
| size | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` to add to the `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Returns the result of subtracting specified `Aspose.Imaging.Size` from the specified `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` to be subtracted from. |
| size | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` to subtract from the `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` by rounding the values of the `Aspose.Imaging.PointF` to the next higher integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `Aspose.Imaging.PointF` to convert. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` object by rounding the `Aspose.Imaging.Point` values to the nearest integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `Aspose.Imaging.PointF` to convert. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Converts the specified `Aspose.Imaging.PointF` to a `Aspose.Imaging.Point` by truncating the values of the `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `Aspose.Imaging.PointF` to convert. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Translates a `Aspose.Imaging.Point` by a given `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` to translate. |
| size | [Size](../../com.aspose.imaging/size) | A `Aspose.Imaging.Size` that specifies the pair of numbers to add to the coordinates of `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Translates a `Aspose.Imaging.Point` by the negative of a given `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` to translate. |
| size | [Size](../../com.aspose.imaging/size) | A `Aspose.Imaging.Size` that specifies the pair of numbers to subtract from the coordinates of `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compares two `Aspose.Imaging.Point` objects. The result specifies whether the values of the `Aspose.Imaging.Point.X` and `Aspose.Imaging.Point.Y` properties of the two `Aspose.Imaging.Point` objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | A first `Aspose.Imaging.Point` to compare. |
| point2 | [Point](../../com.aspose.imaging/point) | A second `Aspose.Imaging.Point` to compare. |

**Returns:**
boolean - True if the `Aspose.Imaging.Point.X` and `Aspose.Imaging.Point.Y` values of `point1` and `point2` are equal; otherwise, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compares two `Aspose.Imaging.Point` objects. The result specifies whether the values of the `Aspose.Imaging.Point.X` or `Aspose.Imaging.Point.Y` properties of the two `Aspose.Imaging.Point` objects are unequal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | A first `Aspose.Imaging.Point` to compare. |
| point2 | [Point](../../com.aspose.imaging/point) | A second `Aspose.Imaging.Point` to compare. |

**Returns:**
boolean - True if the values of either the `Aspose.Imaging.Point.X` properties or the `Aspose.Imaging.Point.Y` properties of `point1` and `point2` differ; otherwise, false.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Converts the specified `Aspose.Imaging.Point` structure to a `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` to be converted. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Converts the specified `Point` structure to the `PointF` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Point` to be converted. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Translates this `Aspose.Imaging.Point` by the specified `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` used to offset this `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Translates this `Aspose.Imaging.Point` by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | int | The amount to offset the x-coordinate. |
| dy | int | The amount to offset the y-coordinate. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifies whether this `Aspose.Imaging.Point` contains the same coordinates as the specified `System.Object`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - True if `obj` is a `Aspose.Imaging.Point` and has the same coordinates as this `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this `Aspose.Imaging.Point`.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### toLong() {#toLong--}
```
public final long toLong()
```


Convert this Point to a single long value, containing X and Y coordinates in high and low bits.

**Returns:**
long - The Point object packed into one long value.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Deconstruct a Point object packed into a long object to separate X and Y int values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| packedPoint | long | The Point object packed into one long value. |
| x | int[] | The extracted from the packed Point X value. |
| y | int[] | The extracted from the packed Point Y value. |

### toString() {#toString--}
```
public String toString()
```


Converts this `Aspose.Imaging.Point` to a human-readable string.

**Returns:**
java.lang.String - A `System.String` that represents this instance.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
