---
title: Size
second_title: Aspose.Imaging for Java API Reference
description: Represents size.
type: docs
weight: 105
url: /java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Represents size.
## Constructors

| Constructor | Description |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Initializes a new instance of the `Aspose.Imaging.Size` structure from the specified `Aspose.Imaging.Point`. |
| [Size(int width, int height)](#Size-int-int-) | Initializes a new instance of the `Aspose.Imaging.Size` structure from the specified dimensions. |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets a new instance of the `Aspose.Imaging.Size` structure that has `Aspose.Imaging.Size.Width` and `Aspose.Imaging.Size.Height` values set to zero. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this `Aspose.Imaging.Size` has width and height of 0. |
| [getWidth()](#getWidth--) | Gets or sets the horizontal component of this `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets the horizontal component of this `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Gets or sets the vertical component of this `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets the vertical component of this `Aspose.Imaging.Size`. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Converts the specified `Aspose.Imaging.Size` to a `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Adds the width and height of one `Aspose.Imaging.Size` structure to the width and height of another `Aspose.Imaging.Size` structure. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtracts the width and height of one `Aspose.Imaging.Size` structure from the width and height of another `Aspose.Imaging.Size` structure. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Tests whether two `Aspose.Imaging.Size` structures are equal. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Tests whether two `Aspose.Imaging.Size` structures are different. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Converts the specified `Aspose.Imaging.Size` to a `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Adds the width and height of one `Aspose.Imaging.Size` structure to the width and height of another `Aspose.Imaging.Size` structure. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by rounding the values of the `Aspose.Imaging.Size` structure to the next higher integer values. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtracts the width and height of one `Aspose.Imaging.Size` structure from the width and height of another `Aspose.Imaging.Size` structure. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by truncating the values of the `Aspose.Imaging.SizeF` structure to the next lower integer values. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by rounding the values of the `Aspose.Imaging.SizeF` structure to the nearest integer values. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests to see whether the specified object is a `Aspose.Imaging.Size` with the same dimensions as this `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Returns a hash code for this `Aspose.Imaging.Size` structure. |
| [toString()](#toString--) | Creates a human-readable string that represents this `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Initializes a new instance of the `Aspose.Imaging.Size` structure from the specified `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The `Aspose.Imaging.Point` from which to initialize this `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initializes a new instance of the `Aspose.Imaging.Size` structure from the specified dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width component of the new `Aspose.Imaging.Size`. |
| height | int | The height component of the new `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Gets a new instance of the `Aspose.Imaging.Size` structure that has `Aspose.Imaging.Size.Width` and `Aspose.Imaging.Size.Height` values set to zero.

**Returns:**
[Size](../../com.aspose.imaging/size)
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this `Aspose.Imaging.Size` has width and height of 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets the horizontal component of this `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets the horizontal component of this `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the vertical component of this `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets the vertical component of this `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Converts the specified `Aspose.Imaging.Size` to a `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` to convert. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Adds the width and height of one `Aspose.Imaging.Size` structure to the width and height of another `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The first `Aspose.Imaging.Size` to add. |
| size2 | [Size](../../com.aspose.imaging/size) | The second `Aspose.Imaging.Size` to add. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Subtracts the width and height of one `Aspose.Imaging.Size` structure from the width and height of another `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the left side of the subtraction operator. |
| size2 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the right side of the subtraction operator. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Tests whether two `Aspose.Imaging.Size` structures are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the left side of the equality operator. |
| size2 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the right of the equality operator. |

**Returns:**
boolean - True if `size1` and `size2` have equal width and height; otherwise, false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Tests whether two `Aspose.Imaging.Size` structures are different.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the left of the inequality operator. |
| size2 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the right of the inequality operator. |

**Returns:**
boolean - True if `size1` and `size2` differ either in width or height; false if `size1` and `size2` are equal.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Converts the specified `Aspose.Imaging.Size` to a `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` to convert. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Adds the width and height of one `Aspose.Imaging.Size` structure to the width and height of another `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The first `Aspose.Imaging.Size` to add. |
| size2 | [Size](../../com.aspose.imaging/size) | The second `Aspose.Imaging.Size` to add. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by rounding the values of the `Aspose.Imaging.Size` structure to the next higher integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure to convert. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Subtracts the width and height of one `Aspose.Imaging.Size` structure from the width and height of another `Aspose.Imaging.Size` structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the left side of the subtraction operator. |
| size2 | [Size](../../com.aspose.imaging/size) | The `Aspose.Imaging.Size` structure on the right side of the subtraction operator. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by truncating the values of the `Aspose.Imaging.SizeF` structure to the next lower integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure to convert. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Converts the specified `Aspose.Imaging.SizeF` structure to a `Aspose.Imaging.Size` structure by rounding the values of the `Aspose.Imaging.SizeF` structure to the nearest integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | The `Aspose.Imaging.SizeF` structure to convert. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests to see whether the specified object is a `Aspose.Imaging.Size` with the same dimensions as this `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to test. |

**Returns:**
boolean - True if `obj` is a `Aspose.Imaging.Size` and has the same width and height as this `Aspose.Imaging.Size`; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this `Aspose.Imaging.Size` structure.

**Returns:**
int - An integer value that specifies a hash value for this `Aspose.Imaging.Size` structure.
### toString() {#toString--}
```
public String toString()
```


Creates a human-readable string that represents this `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - A string that represents this `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
