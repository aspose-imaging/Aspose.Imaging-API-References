---
title: PointF
second_title: Aspose.Imaging for Java API Reference
description: Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 88
url: /com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
## Constructors

| Constructor | Description |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initializes a new instance of the `com.aspose.imaging.PointF` structure with the specified coordinates. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `com.aspose.imaging.PointF` structure that has `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` values set to zero. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this `com.aspose.imaging.PointF` is empty. |
| [getX()](#getX--) | Gets or sets the x-coordinate of this `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of this `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Gets or sets the y-coordinate of this `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of this `com.aspose.imaging.PointF`. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translates a `com.aspose.imaging.PointF` by a given `com.aspose.imaging.Size`. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translates a `com.aspose.imaging.PointF` by the negative of a given `com.aspose.imaging.Size`. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translates the `com.aspose.imaging.PointF` by the specified `com.aspose.imaging.SizeF`. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translates a `com.aspose.imaging.PointF` by the negative of a specified `com.aspose.imaging.SizeF`. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Compares two `com.aspose.imaging.PointF` structures. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Determines whether the coordinates of the specified points are not equal. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translates a given `com.aspose.imaging.PointF` by the specified `com.aspose.imaging.Size`. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Translates a `com.aspose.imaging.PointF` by the negative of a specified size. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translates a given `com.aspose.imaging.PointF` by a specified `com.aspose.imaging.SizeF`. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Translates a `com.aspose.imaging.PointF` by the negative of a specified size. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifies whether this `com.aspose.imaging.PointF` contains the same coordinates as the specified `System.Object`. |
| [hashCode()](#hashCode--) | Returns a hash code for this `com.aspose.imaging.PointF` structure. |
| [toString()](#toString--) | Converts this `com.aspose.imaging.PointF` to a human readable string. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initializes a new instance of the `com.aspose.imaging.PointF` structure with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The horizontal position of the point. |
| y | float | The vertical position of the point. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Gets a new instance of the `com.aspose.imaging.PointF` structure that has `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` values set to zero.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this `com.aspose.imaging.PointF` is empty.

**Returns:**
boolean - True if both `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` are 0; otherwise, false.
### getX() {#getX--}
```
public float getX()
```


Gets or sets the x-coordinate of this `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Gets or sets the x-coordinate of this `com.aspose.imaging.PointF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


Gets or sets the y-coordinate of this `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Gets or sets the y-coordinate of this `com.aspose.imaging.PointF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Translates a `com.aspose.imaging.PointF` by a given `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [Size](../../com.aspose.imaging/size) | A `com.aspose.imaging.Size` that specifies the pair of numbers to add to the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Translates a `com.aspose.imaging.PointF` by the negative of a given `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | A `com.aspose.imaging.PointF` to translate. |
| size | [Size](../../com.aspose.imaging/size) | A `com.aspose.imaging.Size` that specifies the numbers to subtract from the x- and y-coordinates of the `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Translates the `com.aspose.imaging.PointF` by the specified `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `com.aspose.imaging.SizeF` that specifies the numbers to add to the x- and y-coordinates of the `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Translates a `com.aspose.imaging.PointF` by the negative of a specified `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `com.aspose.imaging.SizeF` that specifies the numbers to subtract from the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Compares two `com.aspose.imaging.PointF` structures. The result specifies whether the values of the `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` properties of the two `com.aspose.imaging.PointF` structures are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | A first `com.aspose.imaging.PointF` to compare. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | A second `com.aspose.imaging.PointF` to compare. |

**Returns:**
boolean - True if the `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` values of the first and second `com.aspose.imaging.PointF` structures are equal; otherwise, false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Determines whether the coordinates of the specified points are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | A first `com.aspose.imaging.PointF` to compare. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | A second `com.aspose.imaging.PointF` to compare. |

**Returns:**
boolean - True to indicate the `com.aspose.imaging.PointF.X` and `com.aspose.imaging.PointF.Y` values of `point1` and `point2` are not equal; otherwise, false.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Translates a given `com.aspose.imaging.PointF` by the specified `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [Size](../../com.aspose.imaging/size) | The `com.aspose.imaging.Size` that specifies the numbers to add to the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Translates a `com.aspose.imaging.PointF` by the negative of a specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [Size](../../com.aspose.imaging/size) | The `com.aspose.imaging.Size` that specifies the numbers to subtract from the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Translates a given `com.aspose.imaging.PointF` by a specified `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `com.aspose.imaging.SizeF` that specifies the numbers to add to the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Translates a `com.aspose.imaging.PointF` by the negative of a specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | The `com.aspose.imaging.PointF` to translate. |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `com.aspose.imaging.SizeF` that specifies the numbers to subtract from the coordinates of `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifies whether this `com.aspose.imaging.PointF` contains the same coordinates as the specified `System.Object`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - This method returns true if `obj` is a `com.aspose.imaging.PointF` and has the same coordinates as this `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this `com.aspose.imaging.PointF` structure.

**Returns:**
int - An integer value that specifies a hash value for this `com.aspose.imaging.PointF` structure.
### toString() {#toString--}
```
public String toString()
```


Converts this `com.aspose.imaging.PointF` to a human readable string.

**Returns:**
java.lang.String - A string that represents this `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
